# C_stegnography
Steganography in C

This repository contains a C implementation of steganography techniques for encoding and decoding data within image files. The code allows you to hide a secret file within a cover image and retrieve the hidden data using LSB (least significant bit) manipulation.
Features

    Encoding: The encoding program takes a cover image file and a secret file as input. It embeds the secret file within the cover image by manipulating the LSB of the image pixels.
    Decoding: The decoding program reads a stego image file (an encoded image) and retrieves the hidden secret file by extracting the LSB of the image pixels.

Prerequisites

    C compiler (supporting C99 or later)

