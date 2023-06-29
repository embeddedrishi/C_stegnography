# C_stegnography
Steganography in C

This repository contains a C implementation of steganography techniques for encoding and decoding data within image files. The code allows you to hide a secret file within a cover image and retrieve the hidden data using LSB (least significant bit) manipulation.
Features

    Encoding: The encoding program takes a cover image file and a secret file as input. It embeds the secret file within the cover image by manipulating the LSB of the image pixels.
    Decoding: The decoding program reads a stego image file (an encoded image) and retrieves the hidden secret file by extracting the LSB of the image pixels.

Prerequisites

    C compiler (supporting C99 or later)
Usage

    Clone the repository:

    shell

git clone https://github.com/your-username/steganography-c.git

Compile the code:

shell

cd steganography-c
gcc encode.c decode.c main.c -o steganography

Run the program:

    Encoding:

    shell

./steganography -e cover_image.bmp secret_file.txt

Decoding:

shell

        ./steganography -d stego_image.bmp

    Make sure to replace cover_image.bmp with your own cover image file and secret_file.txt with your own secret file.

Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
License

T

Feel free to customize the content and structure of the README file according to your project's needs. Make sure to update the repository link in the "Clone the repository" section with your own GitHub repository URL.

Happy coding and collaborating!
