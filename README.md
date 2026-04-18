## Disclaimers: This project demonstrates fundamental encryption concepts and is not intended for secure use and XOR encryption with a repeating key is not secure and can be broken with analysis.
|
|
|
 # Features:
. Encrypt and decrypt text using XOR cipher
. Rotating (repeating) key system
. Base64 encoding for readable output
. Basic error handling and input validation
. Simple command-line interface

 # How it works: 
Each character in the message is XORed with a character from the key
The key repeats (rotates) if it is shorter than the message
The result is encoded using Base64 so it can be displayed safely
Decryption reverses the process using the same key

 # How to run: 
Make sure Python is installed
Download the file or clone the repo
Run the program and run 
python xor_tool.py 

# When working:
Example: <img width="1919" height="1001" alt="image" src="https://github.com/user-attachments/assets/7fe15349-aac7-41a6-a24f-1a05a8d1e3f6" />

Author: HsBitCoder
