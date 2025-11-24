# Python Secure Text Encryptor

A simple but secure command-line tool to encrypt and decrypt text messages using a custom passkey.

## 🚀 Features

- **AES Encryption:** Uses the Fernet (Symmetric Encryption) standard for high security.
- **SHA-256 Key Derivation:** Converts any user password into a valid 32-byte encryption key using SHA-256 hashing.
- **Base64 Encoding:** Ensures encrypted output is safe for text storage or transmission.
- **User-Friendly CLI:** Simple menu-driven interface (Select 1 for Encrypt, 2 for Decrypt).

## 🛠️ Technologies Used

- Python 3.x
- `cryptography` library
- `hashlib` (Built-in)
- `base64` (Built-in)

## 📦 Installation

1. 
