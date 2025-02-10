# Web-Based-end-to-end-encrypted-file-transfer
Web-Based End-to-End Encrypted File Transfer

Overview

This is a Flask-based web application that enables secure, end-to-end encrypted file transfers. It ensures that files are encrypted before transmission and can only be decrypted by the intended recipient.

Features

End-to-End Encryption: Utilizes AES and RSA encryption for secure file transfer.

Flask Web Interface: Provides an intuitive UI for sending and receiving files.

Secure Key Exchange: RSA public-private key encryption ensures safe transmission of AES keys.

Socket-Based File Transfer: Enables real-time, peer-to-peer encrypted file sharing.

Customizable Key Size: Supports key sizes from 128-bit to 1024-bit.

Flash Notifications: Displays success or error messages in the UI.

Technologies Used

Python (Flask, pyAesCrypt, Crypto)

Socket Programming (for file transmission)

RSA & AES Encryption (PyCryptodome for encryption & decryption)

HTML, CSS (for web UI)

Installation Guide

1. Prerequisites

Ensure you have the following installed:

Python 3.x

Flask (pip install flask)

PyAesCrypt (pip install pyaescrypt)

PyCryptodome (pip install pycryptodome)

2. Setup & Run the Application

# Clone the repository
git clone https://github.com/your-repo/web-file-transfer.git
cd web-file-transfer

# Install dependencies
pip install -r requirements.txt

# Run the application
python web_based_end_to_end_file_transfer.py

3. Usage Instructions

Start the application: The Flask server will run on http://127.0.0.1:5000/

Send a file:

Enter the receiver's IP address.

Select the file and key size.

Click Send File.

Receive a file:

Click Receive File.

Accept the incoming transfer.

The decrypted file will be saved.

Security Measures

AES Encryption: Encrypts file content before transmission.

RSA Key Exchange: Public-key encryption ensures secure AES key transfer.

Timeout Handling: Prevents connection delays or attacks.

License

This project is licensed under the MIT License.

Contribution

Pull requests are welcome. Please open an issue to discuss changes before making modifications.

Contact

For inquiries, open a GitHub issue or reach out via email.
