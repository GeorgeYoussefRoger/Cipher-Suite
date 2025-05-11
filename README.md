# CipherSuite
**CipherSuite** is a C++-based command-line application designed for encrypting and decrypting messages using ten cryptographic ciphers. Developed as a collaborative team project, this repository includes a single program implementing:
Affine, Route, Atbash, Vigenere, Baconian, Simple Substitution, Polybius Square, Morse Code, XOR and Rail-fence ciphers

## Features
- Encrypt and decrypt messages using ten distinct ciphers.
- Supports key-based ciphers (e.g., Vigenere, Simple Substitution, XOR).
- Handles specialized outputs like Morse code (dots/dashes) and Baconian (A/B codes).
- Input validation to ensure valid inputs (e.g., alphabetic characters, numeric keys).

## My Contributions
- Developed the **Baconian Cipher**, enabling encryption (letters to 5-bit A/B codes) and decryption (reconstructing letters from A/B sequences).
- Implemented the **Simple Substitution Cipher**, supporting encryption and decryption with a 5-letter key for alphabet remapping, including inverse mapping.
- Created the **Morse Code Cipher**, handling encryption (alphanumeric to dots/dashes) and decryption (reconstructing text from Morse sequences) for letters, numbers, and punctuation.