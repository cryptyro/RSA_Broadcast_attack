# E=3 RSA Broadcast attack
An attacker can trivially decrypt your message, by:
- Capturing any 3 of the ciphertexts and their corresponding pubkeys
- Using the CRT to solve for the number represented by the three ciphertexts (which are residues mod their respective pubkeys)
- Taking the cube root of the resulting number


Example Usage:
- The main function demonstrates how to use the rsa_broadcast_attack function with three public keys and corresponding ciphertexts.
- The result is the recovered plaintext message.
