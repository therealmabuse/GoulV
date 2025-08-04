# GOUL-V Dual-Layer Military Grade Encryption Tool

## Overview

GOUL-V is a client-side, dual-layer military grade encryption tool that provides robust protection for both files and text. It implements two independent layers of AES-256 encryption with PBKDF2 key derivation, HMAC integrity verification, and unique initialization vectors for each encryption operation. 

Just drag the GOUL-V file onto a flash drive and you've got powerful encryption anywhere - no install needed, works on any computer.
Super easy to use - if you can click buttons and type passwords, you can keep your files locked down tight. No tech skills required!

This tool is made to encrypt small files, images and text. Not really suitable for huge files!

## Key Features

🔒 Dual-Layer AES-256 Encryption

Two independent encryption layers with separate keys

Each layer uses different IVs and salts

Enforces different passphrases for maximum security

## 🛡️ Enhanced Security Protocols

PBKDF2 key derivation with configurable iterations (default: 100,000)

HMAC-SHA256 integrity verification for each layer

Cryptographically secure random IVs (16 bytes) for each operation

## 🌐 Client-Side Processing

All encryption/decryption happens in your browser

No data is ever sent to any server

Complete privacy for your sensitive information

## 📁 File & Text Support

Encrypt/decrypt any file type

Works with text content directly

Preserves original filenames (adds .denc extension for encrypted files)

## 🟥 Installation

##### No installation required! 

Download the goul.html file

Open it in any modern web browser

Start encrypting/decrypting immediately

## ⚠️ Security Recommendations

Use strong, unique passphrases for each layer (minimum 12 characters, mix of character types)

Keep your passphrases long and safe - if lost, your data cannot be recovered

Consider increasing PBKDF2 iterations for high-security needs (balance with performance)

Verify the integrity of the HTML file before use if downloaded from untrusted sources

Technical Details

    Encryption: AES-256-CBC (two independent layers)
    Key Derivation: PBKDF2 with SHA-256
    Integrity: HMAC-SHA256 for each layer
    Random Generation: Web Crypto API's getRandomValues()
    Metadata Version: 4.0 (includes all parameters needed for decryption)

## License

This project is licensed under the MIT License.

## Disclaimer

This tool is provided for educational and legitimate privacy purposes only. The developers assume no responsibility for how this tool is used. Always comply with local laws and regulations regarding encryption.
