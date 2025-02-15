Sign Up Wallet: Blockchain-Based Digital Identity Management

Overview

The Sign Up Wallet is a blockchain-based self-sovereign identity (SSI) system designed to enhance digital identity management. By leveraging blockchain and machine learning, it provides users with complete control over their personally identifiable information (PII), ensuring privacy and security.

Features

- Self-Sovereign Identity (SSI): Enables decentralized digital identity management.
- Blockchain Integration: Stores identity data securely and immutably.
- Machine Learning-Based Trust Prediction: Uses Logistic Regression to determine the trustworthiness of service providers.
- UPI Code for Secure Registration: Generates a Unique Personal Identifier (UPI) Code for streamlined verification.
- Masked Credential Generation: Uses Lookup Substitution Algorithm for privacy-preserving verification.
- WalletChain Traceability: Ensures secure and auditable transactions.
- User Dashboard: Provides an intuitive interface for managing digital identities.

## Technology Stack

### Backend

- Python 3.8 (Flask framework)
- MySQL 5 (Database)
- WAMP Server

### Frontend

- HTML, CSS, JavaScript
- Bootstrap**

### Additional Libraries & Tools

- Machine Learning: Scikit-Learn (Logistic Regression)
- Data Processing:Pandas, NumPy
- Cryptography: AES Encryption, RSA, ECDSA
- Blockchain: WalletChain Implementation

## System Architecture

The system consists of the following key modules:

1. Sign Up Wallet Web App – A user-friendly interface for managing identities.
2. WalletChain Integration– Secure storage and verification using blockchain.
3. Trusted Website Classification – ML-based website trust prediction.
4. Sign Up Wallet Registration API – Facilitates identity authentication.
5. User Dashboard– Enables users to manage their credentials.
6. WalletChain Traceability– Maintains a secure log of transactions.
7. Notification System– Sends real-time alerts for identity activities.

## Installation Guide

### Prerequisites

Ensure the following dependencies are installed:

- Python 3.8+
- Flask
- MySQL Server
- WAMP Server
- Required Python libraries (install using `pip`):
  ```sh
  pip install flask pandas numpy scikit-learn cryptography mysql-connector-python
  ```

### Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/signup-wallet.git
   cd signup-wallet
   ```
2. Configure the database:
   - Create a MySQL database named `signup_wallet`.
   - Import the provided SQL schema.
3. Update the database credentials in `config.py`:
   ```python
   DB_HOST = "localhost"
   DB_USER = "root"
   DB_PASSWORD = "yourpassword"
   DB_NAME = "signup_wallet"
   ```
4. Run the application:
   ```sh
   python app.py
   ```
5. Access the web app at `http://localhost:5000`.

Usage

1. User Registration: Create an account and receive a UPI Code.
2. Login: Secure access using cryptographic authentication.
3. Service Registration: Register with trusted websites using the UPI Code.
4. Identity Verification:Authenticate credentials without exposing raw data.
5. Track Transactions: Monitor activities via the WalletChain dashboard.


