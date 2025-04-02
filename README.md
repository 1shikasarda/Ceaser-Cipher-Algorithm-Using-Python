# *Caesar Cipher Tool🔒*
## *Overview*
It is a Python program that can encrypt and decrypt text using the Caesar Cipher algorithm and allow users to input a message and a shift value to perform encryption and decryption.This Python script implements the classic Caesar cipher 🤫, allowing users to encrypt and decrypt messages using a simple shift algorithm 🔩. 

## *Features*
- Bidirectional functionality: Encrypt or decrypt messages 🔀
- Case preservation: Maintains original letter cases 📝
- Non-alphabetic handling: Leaves numbers and symbols unchanged 🤖
- Simple interface: Easy-to-use command line interaction 📊
- Customizable shift: Supports any integer shift value 🔧

## *Technical Details 🔍*
### *Algorithm*
The cipher works by shifting each letter in the plaintext by a fixed number down or up the alphabet:
- Encryption: E(x) = (x + n) mod 26 🔒
- Decryption: D(x) = (x - n) mod 26 🔓
Where:
- x is the letter's position in the alphabet (0-25) 
- n is the shift value 

## *Implementation Notes*
- Only alphabetic characters are transformed 🔠
- Case is preserved (uppercase remains uppercase, lowercase remains lowercase) 📝
- Non-alphabetic characters are passed through unchanged 🤖
- Supports both positive and negative shift values 🔢
- Handles shifts greater than 26 through modulo operation 🔄
