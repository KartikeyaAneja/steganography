# Steganography

The practice of encrypting text message, audio, video in another file, image or video.

# Encryption

In this program I encrypt the message by changing the last bit of the "Red" color value of each pixel which will correspond to a bit of the message. If the message is longer than the pixels, the encryption will carry into the "Blue" color value of each pixel and then "Green".

## Encryption Algorithm

The way I changed the last bits of the pixels is by checking if the integer color value is even and if the color value is even but the bit to encode is a 1, 1 is subtracted from the integer color value. Same for vice versa

# Files:

[Encryption Notebook](https://nbviewer.jupyter.org/github/KartikeyaAneja/steganography/blob/main/Encrypt.ipynb)

[Decryption Notebook](https://nbviewer.jupyter.org/github/KartikeyaAneja/steganography/blob/main/Decrypt.ipynb)

