# Encryption Program using Ceasar Cipher  
This encryption program has been further improved compared to the original Ceasar Cipher.   
Improvements in this program has been made to improve its security to prevent breach and also eliminate the use of brute force attack in decrypting texts.  

# The mode of Operation in carrying out the encryption in this code can be explained below:
A Ceasar cipher makes use of key size to perform its encrypting operations.  The number of English alphabet is 26, incases of brute force attack on a ceasar cipher with an encryption list of 26. 
It will take 26 number of exhaustive methods to get the correct shift key. 
In tackling this, I used 70 elements conisisting of the English alphabets, numbers and special symbols. Use of Brute force in this approach will require 70 exhaustive methods of trial to get the shift key which is much more exhaustive.  
To make its security much more efficient, a complex sequence for my encryption list was formed.  

An encryption list is a list that contains the elements in which the Ceasar's encryption will be performed on by just shifting elements  in that list based on the value of the shift key. 
Encryption list was formed by forming a sequence of:  
lowercase alphabets  + numbers + Uppercase alphabets + numbers + Uppercase alphabets and symbols + numbers + Lowercase alphabets and symbols. 
This encryption list makes it more complicated to crack encrypted text, has the correct sequence of the encryption list must be gotten first.  
Before proceeding towards getting the value of the shift key or number of times it was rotated to fully decrypt the texts encrypted.  

# Running the code: 
The user is prompted to enter text to be decrypted, the program return the same text in an encryption form based on Caesar's algorithm   To decrypt the encrypted texts that will be shown, the remaining line of code at the end of the notebook can be Uncommented The program prompts the user for the value of the shift key in place of a password. If the user gets it right, it displays the decrypted text,
if the user fails the password. The program is terminated.    

# Considerations 
The code was developed and improved having the security and efficiency of the Ceasar's Cipher in mind. 
This makes its encryption very effective and it's code much more efficient.
