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
---

## Installation

1.Clone the repository:
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
---

# Usage

## Encrypting a File

1.Run the script:
```bash
python encrypt_decrypt.py
```


2.Select the encryption option.

3.Enter the path to the file you want to encrypt.

4.Provide a password. The tool generates an encrypted file with a .enc extension.

## Decrypting a File

1.Run the script:

```bash
python encrypt_decrypt.py
```

2.Select the decryption option.

3.Enter the path to the encrypted file.

4.Provide the same password used during encryption. The tool generates a decrypted file with `_decrypted` added to its name.

---

# Example
## Input File
- `example.txt`: Contains sample data for encryption.

## Encryption Process

1.Original file: `example.txt`

2.Encrypted file: `example.txt.enc`

## Decryption Process
1.Encrypted file: `example.txt.enc`

2.Decrypted file: `example_decrypted.txt`

---


# Use Cases
This tool is ideal for:

1.Data Security:

- Protect sensitive files from unauthorized access.

- Ensure confidentiality for personal and professional data.

2.Data Backup:

- Encrypt backup files to prevent data leaks during storage or transfer.

3.Compliance:

- Secure files to comply with regulations like GDPR, HIPAA, or PCI-DSS.

4.Personal Use:

- Encrypt personal documents, such as financial records or photos, for added security.

---

# Acknowledgments
This project was completed under the mentorship of Neela Santosh as part of the internship at CODTECH IT SOLUTIONS. Special thanks to:

- YouTube Tutorials: For insights into encryption techniques.

- Cryptography Library Documentation: For clear and concise usage guidelines.

- ChatGPT: For assistance with development and documentation.

---

# Future Improvements
Here are some enhancements planned for this tool:

1.Graphical User Interface (GUI):

- Add a user-friendly interface for encryption and decryption tasks.

2.Real-Time Encryption:

- Enable on-the-fly encryption for active data streams.

3.Additional Algorithms:

- Support other encryption methods, such as RSA or Blowfish.

4.Batch Processing:

- Add functionality to encrypt/decrypt multiple files in a single session.

