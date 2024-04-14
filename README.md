

# Cipher Program

This program allows users to encrypt and decrypt messages using various cipher techniques. Below is a brief overview of each cipher implemented in the program:

## XOR Cipher

- The XOR cipher is a simple encryption algorithm that operates on binary data.
- It performs an exclusive OR (XOR) operation between the plaintext and a secret key.
- To encrypt a message, each character of the message is XORed with the corresponding character of the key.
- To decrypt the message, the same key is used to XOR the ciphertext, resulting in the original plaintext.

## Atbash Cipher

- The Atbash cipher is a substitution cipher where each letter in the plaintext is replaced with its reverse alphabet counterpart.
- For example, 'A' is replaced with 'Z', 'B' with 'Y', and so on.
- It preserves spaces and other non-alphabetic characters.

## Baconian Cipher

- The Baconian cipher encodes messages using a binary system where each letter of the alphabet is represented by a sequence of five binary digits.
- In this implementation, 'A' is represented as 'aaaaa' and 'B' is represented as 'aaaab', and so on.
- The cipher can encode and decode messages based on these binary sequences.

## Morse Code Cipher

- The Morse code cipher encodes and decodes messages using the Morse code alphabet, where each letter is represented by a series of dots and dashes.
- This implementation supports encoding and decoding messages using Morse code.

## Affine Cipher

- The Affine cipher is a type of substitution cipher where each letter in the plaintext is mapped to its numerical equivalent, encrypted, and then converted back to a letter.
- It uses a pair of keys: one for encryption and one for decryption.
- This implementation supports both encryption and decryption using the Affine cipher algorithm.

## Simple Substitution Cipher

- The Simple Substitution cipher is a substitution cipher where each letter in the plaintext is replaced with another letter based on a key.
- This implementation allows users to provide a key consisting of 5 unique letters, which are used to create a substitution alphabet.
- It supports both encryption and decryption of messages using the substitution alphabet.

## Rail Fence Cipher

- The Rail Fence cipher is a transposition cipher that rearranges the characters of a message by writing them in a zigzag pattern.
- This implementation supports encrypting messages using the Rail Fence algorithm.

## Vigenere Cipher

- The Vigenere cipher is a polyalphabetic substitution cipher that uses a keyword to shift letters in the plaintext by different amounts.
- This implementation supports both encryption and decryption using the Vigenere cipher algorithm.
