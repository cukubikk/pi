# Concepts and Security Measurements
This document outlines the concepts and security measures implemented in pi. 

## End-to-End Encryption
All data managed by **pi** is encrypted using AES-256 encryption. End-to-end encryption guarantees that even if our servers are compromised, your data remains secure.

## Zero-Knowledge Architecture
**pi** is built on a zero-knowledge architecture. Even the **pi** team cannot view your passwords.

## Encryption
**pi** uses AES 256-bit encryption.

pi **always** encrypts your data on your local device before anything is sent to cloud servers. **pi servers are only used for storing encrypted data.**

All the data can only be decrypted using the key derived from your master password.