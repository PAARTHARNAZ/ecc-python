#ecc-python

Implementation of ECC in python

ECC Concepts Implementation
Introduction

This Python script implements various concepts of Elliptic Curve Cryptography (ECC). ECC is a powerful cryptographic technique that offers efficiency and security in key exchange, encryption, and decryption operations.
Implementation Details

The script includes the following components:

    ECCPoint Class:
        Represents a point on an elliptic curve.
        Includes methods for checking curve validity, point presence on the curve, point addition, and scalar multiplication.

    DH_key_exchange Function:
        Implements ECC-based Diffie-Hellman key exchange.
        Generates public keys, computes shared secrets.

    Encrypt and Decrypt Functions:
        Perform public key-based encryption and decryption using ECC.

    Menu-Driven Interface:
        Provides a user-friendly menu for interacting with ECC functionalities.
        Options include curve validation, point verification, key exchange, encryption, and decryption.

Usage

    Define the elliptic curve parameters (p, a, b) and the base point (base_point) in the script.
    Run the script.
    Choose options from the menu to perform ECC operations.

Requirements

    Python 3.x

How to Run

    Clone or download the repository containing the script.
    Open a terminal or command prompt.
    Navigate to the directory containing the script.
    Run the script using the command python ecc_script.py.

Example Usage

python ecc_script.py