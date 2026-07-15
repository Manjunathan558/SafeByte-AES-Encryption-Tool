Project Overview

SafeByte is a Python-based security application that provides secure text and file encryption using the Advanced Encryption Standard (AES-128) in CBC mode. It also includes an encrypted chat module for secure communication over TCP/IP.

The project demonstrates practical implementation of modern cryptography concepts including AES encryption, secure key generation, file protection, and encrypted client-server communication.

Features
AES-128 Encryption (CBC Mode)
Secure File Encryption & Decryption
Text Encryption (Hex & Base64 Output)
Password-Based Key Derivation (scrypt)
PKCS#7 Padding
Data Compression using zlib
Encrypted Client-Server Chat
Automatic Random IV Generation
Input Validation
Command Line Interface
Technologies Used
Python
PyCryptodome
Socket Programming
Threading
Colorama
zlib
Installation
git clone https://github.com/yourusername/SafeByte-AES-Encryption-Tool.git

cd SafeByte-AES-Encryption-Tool

pip install -r requirements.txt
Run
python main.py
Project Architecture
Plaintext
     │
     ▼
Compression
     │
     ▼
AES Encryption (CBC)
     │
     ▼
Ciphertext
     │
     ▼
Transmission / Storage
     │
     ▼
AES Decryption
     │
     ▼
Original Data
Project Screenshots

(Add screenshots here)

Main Menu
Text Encryption
File Encryption
Chat Application
Future Improvements
GUI using Tkinter
AES-256 Support
RSA Key Exchange
Digital Signatures
Secure Cloud Storage
REST API Integration
Skills Demonstrated
Cryptography
Python Development
Secure File Handling
Socket Programming
Networking
Modular Programming
Secure Communication
