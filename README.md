# PRODIGY_TrackCode_01
Implement Caesar Cipher

Create a Python program that can encrypt and decrypt text using the Caesar Cipher algorithm. Allow users to input a message and a shift value to perform encryption and decryption.

How it works:

Encryption: The function caesar_encrypt shifts each alphabetic character by the given shift value. It wraps around if the shift exceeds 'Z' or 'z'. Non-alphabetic characters are left unchanged.

Decryption: The caesar_decrypt function is simply the inverse of encryption. It shifts the characters back by the negative of the original shift value.
The program first encrypts the message and then decrypts it back to the original text.

Caesar Cipher Program

Enter the message: Hello World

Enter the shift value (integer): 3

Encrypted Message: Khoor Zruog

Decrypted Message: Hello World
