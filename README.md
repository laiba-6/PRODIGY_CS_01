Encrypt Function:

Takes a text and a shift value.
Iterates over each character in the text.
If the character is a letter, it shifts it by the provided shift value, wrapping around using modulo 26.
Non-alphabetical characters are appended unchanged.

Decrypt Function:

Uses the encrypt function with a negative shift to decrypt the text.

Main Function:

Provides a simple command-line interface.
Asks the user whether they want to encrypt, decrypt, or quit.
Based on the choice, it takes the text and shift value from the user and calls the appropriate function.

-You can run this script in a Python environment. It will prompt you to input the text and shift value and then provide the encrypted or decrypted text based on your choice.
