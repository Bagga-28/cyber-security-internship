# Introduction to Cryptography: Encryption and Hashing

## Objective

The objective of this task is to understand the fundamentals of cryptography, including encryption and hashing techniques used to protect data and secure communications.

---

# What is Cryptography?

Cryptography is the practice of securing information by converting it into a form that unauthorized users cannot understand.

## Importance of Cryptography

* Protects sensitive information
* Secures online transactions
* Ensures data confidentiality
* Verifies data integrity
* Supports authentication

---

# Symmetric Encryption

Symmetric encryption uses the same key for both encryption and decryption.

## How It Works

1. Plain text is encrypted using a secret key.
2. The encrypted data (ciphertext) is transmitted.
3. The same key is used to decrypt the data.

## Advantages

* Fast encryption and decryption
* Efficient for large amounts of data

## Disadvantages

* Secure key sharing is difficult
* If the key is compromised, all data is exposed

## Examples

* AES (Advanced Encryption Standard)
* DES (Data Encryption Standard)

---

# Asymmetric Encryption

Asymmetric encryption uses two keys:

* Public Key
* Private Key

## How It Works

1. Data is encrypted using a public key.
2. Only the corresponding private key can decrypt it.

## Advantages

* More secure key management
* Enables secure communication over public networks

## Disadvantages

* Slower than symmetric encryption

## Examples

* RSA
* ECC (Elliptic Curve Cryptography)

---

# Symmetric vs Asymmetric Encryption

| Feature   | Symmetric Encryption   | Asymmetric Encryption   |
| --------- | ---------------------- | ----------------------- |
| Keys Used | One Key                | Two Keys                |
| Speed     | Faster                 | Slower                  |
| Security  | Depends on key secrecy | Stronger key management |
| Examples  | AES, DES               | RSA, ECC                |

---

# Hashing

Hashing converts data into a fixed-length value called a hash.

## Characteristics

* One-way process
* Cannot be reversed
* Same input always produces the same output

## Uses

* Password storage
* Data integrity verification
* Digital signatures

## Common Hashing Algorithms

* SHA-256
* SHA-512
* MD5 (legacy, not recommended for security)

---

# Python Hashing Example

```python
import hashlib

text = "CyberSecurity"

hash_value = hashlib.sha256(text.encode())

print(hash_value.hexdigest())
```

### Output Example

```text
f0c7f0b7e0fbcf5f...
```

---

# Real-World Applications

* HTTPS websites
* Online banking
* Digital certificates
* Password protection
* Secure messaging applications

---

# Conclusion

Cryptography is a critical component of cybersecurity. Symmetric encryption provides fast data protection, asymmetric encryption enables secure communication, and hashing ensures data integrity. Together, these technologies help secure modern digital systems.

## Learning Outcome

Through this task, I learned the differences between symmetric and asymmetric encryption, the role of hashing algorithms, and how cryptography is applied in real-world cybersecurity systems.
