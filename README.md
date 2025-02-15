# Cryptography Comparative Analysis  

A performance and security analysis of various cryptographic algorithms, including **hashing, symmetric encryption, and asymmetric encryption**. The study evaluates algorithm efficiency based on **speed, resource usage, collision resistance, and brute-force resistance** using practical experiments in Python.

## Tech Stack  

- Python  
- matplotlib (Data Visualization)  
- hashlib (Hashing)  
- cryptography (Encryption)  
- psutil (Resource Monitoring)  
- csv (Data Storage)  

## Features  

### Hashing Algorithms Analysis  
- **Performance Testing**: Measures hashing speed (MBps) for MD5, SHA-1, SHA-256, and BLAKE2.  
- **Resource Usage**: CPU and memory consumption for each hashing algorithm.  
- **Collision Resistance**: Tests for hash collisions in MD5, SHA-1, SHA-256, and BLAKE2.  

### Symmetric Encryption Analysis  
- **Algorithms Tested**: AES, 3DES, and Blowfish.  
- **Encryption & Decryption Speed**: Performance comparison in MBps.  
- **Resource Efficiency**: CPU and memory usage monitoring.  
- **Brute-Force Resistance**: Simulation of exhaustive key search for AES, 3DES, and Blowfish.  

### Asymmetric Encryption Analysis  
- **Algorithms Tested**: RSA, ECC, and ElGamal.  
- **Performance Comparison**: Encryption and decryption speeds.  
- **Ciphertext Size Growth**: Analyzes ciphertext expansion for different plaintext sizes.  
- **Brute-Force Feasibility**: Tests computational effort required for breaking RSA, ECC, and ElGamal encryption.  

### Data Visualization  
- **Graphical Analysis**: Performance results plotted using Matplotlib.  
- **Hashing Speed & CPU Usage Charts**.  
- **Encryption/Decryption Speed Comparisons**.  
- **Ciphertext Size Growth Overhead Analysis**.  
