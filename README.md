# Caesar Cipher Implementation
This Python program implements the **Caesar Cipher**, a simple encryption and decryption technique where each letter in the text is shifted by a specific number of positions in the alphabet.

## Features
- Encrypt (**encode**) a message by shifting letters forward.
- Decrypt (**decode**) a message by shifting letters backward.
- Handles wrap-around for letters (e.g., shifting **z** forward results in **a**).
- Maintains spaces and special characters without altering them.
- Efficient handling of large shift values by reducing them modulo 26.
- User-friendly interface allowing repeated operations until the user decides to exit.

## How It Works
1. The user selects whether to **encode** or **decode** a message.
2. The program asks for the message and the shift number.
3. It processes the message using the Caesar Cipher logic:
   - For **encode**, letters are shifted forward by the shift value.
   - For **decode**, letters are shifted backward by the shift value.
4. The result is displayed to the user.
5. The user can choose to restart or exit the program.
