# ECC Concepts Implementation

## Introduction
This Python script implements various concepts of Elliptic Curve Cryptography (ECC). ECC is a powerful cryptographic technique that offers efficiency and security in key exchange, encryption, and decryption operations.

## Implementation Details
The script includes the following components:

1. **ECCPoint Class**:
   - Represents a point on an elliptic curve.
   - Includes methods for checking curve validity, point presence on the curve, point addition, and scalar multiplication.

2. **DH_key_exchange Function**:
   - Implements ECC-based Diffie-Hellman key exchange.
   - Generates public keys, computes shared secrets.

3. **Encrypt and Decrypt Functions**:
   - Perform public key-based encryption and decryption using ECC.

4. **Menu-Driven Interface**:
   - Provides a user-friendly menu for interacting with ECC functionalities.
   - Options include curve validation, point verification, key exchange, encryption, and decryption.

## Usage
1. Define the elliptic curve parameters (`p`, `a`, `b`) and the base point (`base_point`) in the script.
2. Run the script.
3. Choose options from the menu to perform ECC operations.

## Requirements
- Python 3.x

## How to Run
1. Clone or download the repository containing the script.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script using the command `python ecc_script.py`.

## Example Usage
```bash
python ecc_script.py
