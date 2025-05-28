# Advanced Encryption Tool

## Internship Details
- **Company**: CODTECH IT SOLUTIONS
- **Name**: KASULA SHIVA
- **Intern ID**: CT08DM748
- **Domain**: Cyber Security & Ethical Hacking
- **Duration**: 8 Weeks
- **Mentor**: NEELA SANTOSH

---

## Overview
The **Advanced Encryption Tool** is a Python-based project developed as part of an internship with CODTECH IT SOLUTIONS in the **Cyber Security & Ethical Hacking** domain. This tool focuses on securing files by implementing the **AES-256 encryption algorithm**, one of the most secure and widely used encryption standards today.

Encryption is an essential part of cybersecurity and helps protect sensitive information from unauthorized access. This project allows users to encrypt their files securely and decrypt them later using a password-based key. The tool is designed to handle text, documents, and other sensitive data efficiently.

By combining simplicity and robust security, the tool caters to users with minimal technical knowledge while meeting advanced security requirements.

---

## Features
This project includes the following features:
1. **Strong Encryption**:
   - Utilizes AES-256 (Advanced Encryption Standard) for robust file encryption.
   - Ensures high security with a random salt and initialization vector (IV) for each encryption session.

2. **Password-Based Key Derivation**:
   - Uses a secure password-to-key mechanism (PBKDF2) to derive encryption keys.
   - Prevents brute-force attacks by introducing random salt.

3. **File Handling**:
   - Supports the encryption of various file types, including `.txt`, `.csv`, and `.docx`.
   - Generates encrypted files with a `.enc` extension for easy identification.

4. **User-Friendly Interface**:
   - Provides a simple command-line interface (CLI) for encrypting and decrypting files.
   - Displays helpful prompts for user input.

5. **Cross-Platform Compatibility**:
   - Runs seamlessly on Windows, macOS, and Linux.

---

## Requirements
To use this tool, ensure you have the following:
- **Python**:
  - Version: 3.6 or higher
  - Install from [python.org](https://www.python.org/).
- **Libraries**:
  - `cryptography`: Provides encryption algorithms and utilities.
  - `os`: Handles file operations.
  - `base64`: Encodes and decodes binary data.

Install the required library with:
```bash
pip install cryptography
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shivakasula48/Advanced-Encryption-Tool.git
   ```
2.Navigate to the project directory:
   ```bash
   cd Advanced-Encryption-Tool
```
3.Install the required libraries:
```bash
pip install cryptography
```
# Usage

1.Run the script:
```bash
python encrypt_decrypt.py
```


2.Follow the prompts to:

   - Encrypt a file: Provide the file path and a password.

   - Decrypt a file: Provide the encrypted file path and the same password used for encryption.

