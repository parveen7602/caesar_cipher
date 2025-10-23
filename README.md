# caesar_cipher
This project implements the Caesar Cipher, one of the simplest and most well-known encryption techniques. It works by shifting the letters of a message by a fixed number of positions in the alphabet, providing basic text encryption and decryption functionality.

The Caesar Cipher works by replacing each letter in the plaintext with another letter a certain number of positions down the alphabet.  
For example, with a shift of `3`:
A → D, B → E, C → F, ...
Decryption reverses the process by shifting letters back by the same number.

This program allows users to:
- Encrypt a message  
- Decrypt an encrypted text  
- Specify any integer as a shift key  

# Features
✅ Encrypt and decrypt text messages  
✅ Works for both uppercase and lowercase letters  
✅ Ignores spaces and special characters  
✅ Simple command-line user interface  

# Example for encryption
Enter message: HELLO
Enter shift: 3
Encrypted text: KHOOR
# Example for decryption
Enter message: KHOOR
Enter shift: 3
Decrypted text: HELLO
