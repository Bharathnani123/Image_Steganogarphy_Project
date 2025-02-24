# Image_Steganogarphy_Project
Secure data hiding in Image using steganography

Abstract

With the rise of digital communication, the security of confidential information has become crucial. This project presents a secure image steganography system that combines Least Significant Bit (LSB) substitution with AES encryption to ensure hidden data remains secure. The system provides a user-friendly interface to encode and decode messages inside images while protecting them from unauthorized access.

Introduction

Steganography is the practice of hiding information within digital media to ensure covert communication. Unlike cryptography, which scrambles data to make it unreadable, steganography conceals data in such a way that its presence remains undetectable. This project leverages the LSB substitution technique to embed secret messages into images and further enhances security using AES encryption.

Objectives

1.To develop a secure image steganography system.

2.To enhance data protection using AES encryption.

3.To create an easy-to-use GUI-based application.

4.To ensure data is embedded without noticeable visual distortion.

Methodology

Least Significant Bit (LSB) Encoding
LSB steganography embeds secret messages into the least significant bits of pixel values. This method ensures that visual changes remain imperceptible.

Convert message into binary.

Embed binary data into the least significant bits of image pixels.

Save the modified image.

AES Encryption for Security
Before embedding, the secret message is encrypted using AES (Advanced Encryption Standard). This ensures that even if the message is extracted, it remains unreadable without the correct decryption key.

Encrypt message using Fernet encryption.

Embed encrypted message into the image.

Extract and decrypt during retrieval.

GUI Implementation (Tkinter)
To ensure ease of use, the project provides a Graphical User Interface (GUI) using Tkinter. Users can:

Select an image to encode a message.

Enter a secret message for encryption and embedding.

Decode messages from an encoded image using the correct key.

Implementation Details

The project is implemented in Python using:

1.OpenCV for image processing.

2.NumPy for pixel manipulation.

3.Cryptography module for AES encryption.

4.Tkinter for GUI interaction.

Results and Analysis

Visual Quality: The modified images show negligible changes compared to the original.

Security Enhancement: Encrypted messages ensure data protection even if extracted.

Usability: The GUI provides a seamless experience for both encoding and decoding.

Conclusion and Future Scope

This project successfully implements a secure and user-friendly image steganography system. By integrating AES encryption, it enhances data security beyond simple LSB steganography.

Future Enhancements:

Support for other image formats (JPEG, BMP, etc.).

Integration with mobile applications.

Use of AI for steganalysis resistance.
