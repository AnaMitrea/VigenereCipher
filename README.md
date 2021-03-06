# Vigenere-Cipher
-

The Vignere Cipher is a method of encryting alphabetic text by using a series of interwoven Caesar ciphers, based on the letters of a keyword.

Encryption
-
-  Each letter is transformed into the ASCII value. In this way we work with the values 0-25 to calculate how much the filtered text shifts and in which letter the current letter is transformed.
-  A key is needed in order to algebrically encrypt the plain text.
- Rule: ![Encryption rule](https://wikimedia.org/api/rest_v1/media/math/render/svg/099f63c1c54cf9196d44a9210a275ae3b9121ec1)

Decryption
-
- Rule: ![Decryption rule](https://wikimedia.org/api/rest_v1/media/math/render/svg/c9b6e7fd40c1c31b56d00bc85cfe0563be8a8952)

Cryptanalysis
-
- The idea behind the Vigenère cipher, like all other polyalphabetic ciphers, is to disguise the plaintext letter frequency to interfere with a straightforward application of frequency analysis.
- Friedman test
  - Index of coincidence:
    -  Rule: ![IOC rule](https://wikimedia.org/api/rest_v1/media/math/render/svg/63c33432649ee77f4cb1bbbbaefb67cf0ebdb0df)
