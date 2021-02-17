Program Assignment 1: DES simulation

Due: 2PM on Thursday, 2/18/2021

DES program consists of several classes: 

1. DES_Simultion
   - Main simulation engine
   - Completed (do not modify)
   
2. Conversion
   - Provides utility functions for conversion between a string 
     of characters and a binary string
   - Completed (do not modify)

3. DES
   - Includes encryption and decryption algorithms
   - Completed (do not modify)


3. IP
   - Initial permutation
   - Completed (do not modify)

4. FeisteNetwork
   - Consists of 16 rounds. 
   - This class includes the f-function with four steps: Expansion, Xor, S-box substitution, Permutation 
   - To be completed


5. IPinverse
   - Final permutation, inverse of the initial permutation
   - To be completed  

6. KeySchedule
  - Includes key scheduling algorithms for both encryption and decryption
  - To be completed
--------------------------------------------------------

Program Execution and Expected output:

   Provide two command line arguments (file names for plaintext and key) 
   
             java DES_Simulation input.txt key.txt
   
   With the given txt files, your program output must be:

ciphertext: 1100100011010010001000001001111011111011011101001101100110000101
Success
recoverted Text: 
Hi World

----------------------------------------------------------

Provided data files:
   - The input.txt file contains exactly 8 characters which fit in a block of 64 bits. 
   - The key.txt file contains a key of 64 bits.
   - You may choose different plaintext and keys.
 
 
   
    