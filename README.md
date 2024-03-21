# Cryptography Application

## About

This Cryptography Application is a versatile tool designed for educational purposes, providing users with the ability to encrypt and decrypt messages using various algorithms. It supports the Caesar Cipher, RSA encryption, and Diffie-Hellman Key Exchange (DHK), offering a user-friendly interface for cryptography enthusiasts and learners to explore the basics of encryption and decryption techniques.

## Features

- **Encrypt & Decrypt Messages**: Users can choose between multiple encryption algorithms to securely encrypt their messages or decrypt ciphertext to plain text.
- **Support for Multiple Algorithms**: Including Caesar Cipher, RSA, and Diffie-Hellman Key Exchange.
- **No User Login Required**: Simplifies access and use without the need for account creation or login.
- **History of Encryptions**: View a history of encrypted messages and used keys (optional feature based on final implementation).

## How It Works

1. **Select Encryption Algorithm**: Choose from the Caesar Cipher, RSA, or DHK from the dropdown menu.
2. **Input Message**: Enter the text you wish to encrypt or decrypt.
3. **Specify Key/Shift (if applicable)**: For the Caesar Cipher, input the shift amount. For RSA, ensure you have the correct keys.
4. **Encrypt/Decrypt**: Click the "Encrypt/Decrypt" button to process your input.
5. **View Output**: The encrypted or decrypted message will be displayed on the screen.

## Installation

1. Clone the repository to your local machine:
    ```
    git clone https://github.com/yourusername/cryptography-application.git
    ```
2. Navigate to the project directory:
    ```
    cd cryptography-application
    ```
3. Install dependencies (example for a Python project):
    ```
    pip install -r requirements.txt
    ```
4. Run the application (example command):
    ```
    python app.py
    ```

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Python with Flask/Django (adjust according to your implementation)
- Database: SQLite/PostgreSQL (based on the schema provided)

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

- This project is intended for educational purposes and aims to introduce users to the fundamentals of cryptography.
