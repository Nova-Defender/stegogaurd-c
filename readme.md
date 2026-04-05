# StegoGuard-C

## Project Overview
**StegoGuard-C** is a C-based application for hiding secret text messages inside BMP image files using steganography. The program manipulates the least significant bits (LSB) of image pixels to embed information, keeping the image visually unchanged while securely storing hidden messages.

---

## Problem Statement
In digital communication, sensitive information is at risk of interception. Traditional encryption is often detectable and may attract attention. StegoGuard-C addresses this problem by embedding messages within images, preserving image quality and allowing secure retrieval of the hidden data.

---

## Features
- Hide secret text messages in BMP images.
- Extract hidden messages from images.
- Maintains original image quality.
- Lightweight and portable C program.

---

## Folder Structure
```text
StegoGuard-C/
│
├── src/             # C source files
│   ├── main.c
│   ├── encode.c
│   ├── encode.h
│   ├── decode.c
│   ├── decode.h
│   └── common.h
├── sample.bmp       # Sample image for testing
├── secret.txt       # Text file containing message to hide
├── output.bmp       # Image after hiding the message
└── README.md        # Project documentation
