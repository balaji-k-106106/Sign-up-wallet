Sign Up Wallet: Blockchain-Based Digital Identity Management

Overview

The Sign Up Wallet is a blockchain-based self-sovereign identity (SSI) system designed to enhance digital identity management.
By leveraging blockchain and machine learning, it provides users with complete control over their personally identifiable information (PII), ensuring privacy and security.

Features

Self-Sovereign Identity (SSI): Enables decentralized digital identity management.

Blockchain Integration: Stores identity data securely and immutably.

Machine Learning-Based Trust Prediction: Uses Logistic Regression to determine the trustworthiness of service providers.

UPI Code for Secure Registration: Generates a Unique Personal Identifier (UPI) Code for streamlined verification.

Masked Credential Generation: Uses Lookup Substitution Algorithm for privacy-preserving verification.

WalletChain Traceability: Ensures secure and auditable transactions.

User Dashboard: Provides an intuitive interface for managing digital identities.

Technology Stack

Backend

Python 3.8 (Flask framework)

MySQL 5 (Database)

WAMP Server

Frontend

HTML, CSS, JavaScript

Bootstrap

Additional Libraries & Tools

Machine Learning: Scikit-Learn (Logistic Regression)

Data Processing: Pandas, NumPy

Cryptography: AES Encryption, RSA, ECDSA

Blockchain: WalletChain Implementation

System Architecture

The system consists of the following key modules:

Sign Up Wallet Web App – A user-friendly interface for managing identities.

WalletChain Integration – Secure storage and verification using blockchain.

Trusted Website Classification – ML-based website trust prediction.

Sign Up Wallet Registration API – Facilitates identity authentication.

User Dashboard – Enables users to manage their credentials.

WalletChain Traceability – Maintains a secure log of transactions.

Notification System – Sends real-time alerts for identity activities.

Installation Guide

Prerequisites

Ensure the following dependencies are installed:

Python 3.8+

Flask

MySQL Server

WAMP Server

Required Python libraries (install using pip):

pip install flask pandas numpy scikit-learn cryptography mysql-connector-python

Setup Instructions

Clone the repository:

git clone https://github.com/yourusername/signup-wallet.git
cd signup-wallet

Configure the database:

Create a MySQL database named signup_wallet.

Import the provided SQL schema.

Update the database credentials in config.py:

DB_HOST = "localhost"
DB_USER = "root"
DB_PASSWORD = "yourpassword"
DB_NAME = "signup_wallet"

Run the application:

python app.py

Access the web app at http://localhost:5000.

Usage

User Registration: Create an account and receive a UPI Code.

Login: Secure access using cryptographic authentication.

Service Registration: Register with trusted websites using the UPI Code.

Identity Verification: Authenticate credentials without exposing raw data.

Track Transactions: Monitor activities via the WalletChain dashboard.
