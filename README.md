# RSA-Exploration
This project is an in-depth exploration of **RSA**, one of the most widely used public-key encryption schemes. Built entirely from scratch using Python, the notebook walks through all the essential components and theoretical foundations required to implement RSA encryption and decryption.

## 📚 Table of Contents

1. [Introduction](#1-introduction)
2. [RSA Code Package](#2-rsa-code-package)  
   2.1 [Basic Tool Set](#21-basic-tool-set)  
   2.2 [First Tool Set](#22-first-tool-set)  
   2.3 [Second Tool Set](#23-second-tool-set)  
3. [RSA: Encode & Decode](#3-rsa-encode--decode)  
4. [Demo](#4-demo)  
5. [Code Exchange Results](#5-code-exchange-results)  
6. [Narrative](#6-narrative)  
7. [Why FME?](#7-why-fme)  
8. [Code Breaking](#8-code-breaking)  
9. [Breaking RSA: Complete Examples](#9-breaking-rsa-complete-examples)  
10. [Custom Features & Advanced Options](#10-custom-features--advanced-options)

---

## 1. 📌 Introduction

RSA (Rivest–Shamir–Adleman) is a cornerstone of modern cryptography. This project dissects RSA from both theoretical and practical lenses, covering key number theory concepts like:

- Prime Factorization
- Modular Arithmetic
- Euclidean and Extended Euclidean Algorithms
- Fast Modular Exponentiation

These principles are then translated into a working RSA encryption and decryption system.

---

## 2. 🛠️ RSA Code Package

### 2.1 Basic Tool Set

Tools to clean, convert, and prepare plaintext messages before encryption and after decryption.

### 2.2 First Tool Set

Core mathematical functions:
- Euclidean Algorithm
- Extended Euclidean Algorithm
- Modular Inverses

### 2.3 Second Tool Set

Tools for:
- Key generation
- Encrypting and decrypting messages
- Prime checking and generation

---

## 3. 🔐 RSA: Encode & Decode

Functions that:
- Generate public and private key pairs
- Encode a given message using the public key
- Decode the encrypted message using the private key

---

## 4. 🧪 Demo

A full walkthrough example showing:
- Key generation
- Message encryption
- Cipher decryption

All steps are visible and clearly annotated for understanding the full encryption lifecycle.

---

## 5. 🔁 Code Exchange Results

A log of interactions where this RSA implementation was used to:
- Encode personal messages
- Exchange encrypted content with peers
- Decode received ciphers

---

## 6. 📝 Narrative

An in-depth explanation of:
- Learning outcomes
- Project goals
- Reflections on challenges and implementation choices

---

## 7. 💡 Why FME?

A dedicated section discussing why **FME** (Foundations of Mathematical Encryption) was selected as the methodology and its relevance in real-world security systems.

---

## 8. 🧠 Code Breaking

A look into the vulnerabilities of RSA and how, under certain conditions, encoded messages can be cracked using:
- Brute force
- Factoring weak keys
- Timing analysis (conceptually)

---

## 9. 🧨 Breaking RSA: Complete Examples

Illustrated attempts to break sample RSA implementations to understand weaknesses and how to avoid them when building a secure encryption system.

---

## 10. 🧬 Custom Features & Advanced Options

Additional features:
- Configurable key sizes
- Custom encoding alphabets
- User-defined encryption parameters
- Robust error handling

---

## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- Built-in libraries: `math`, `random`, `string`
