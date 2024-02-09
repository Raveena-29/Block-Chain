# BLOCK CHAIN

## What is block chain?
- A blockchain is a decentralized, distributed and public digital ledger that is used to record transactions across many computers so that the record cannot be altered retroactively without the alteration of all subsequent blocks and the consensus of the network.
<br>

**ENCRYPTION**
-  Encryption is the process of protecting information or data by using mathematical models to scramble it in such a way that only the parties who have the key to unscramble it can access it.
-  There are two types of encryption in widespread use today:
  - Symmetric encryption.
  - Asymmetric encryption.
- Encryption is the process of encoding information in such a way that only authorized parties can access it.
- Encryption is widely used to protect sensitive data, such as personal information, financial transactions, and government communications, from unauthorized access.
- There are many encryption algorithms and techniques, each with its own strengths and weaknesses, but they all serve the same fundamental purpose of securing information.
<br>

**SYMMETRIC ENCRYPTION**
- Symmetric encryption is a cryptographic method where the same key is used for both encryption and decryption of data.
-  In this scheme, the sender and receiver share a common secret key, which they use to both encrypt and decrypt messages.
-  Symmetric encryption algorithms are generally faster and more efficient than asymmetric algorithms, making them suitable for encrypting large amounts of data.
-  However, the challenge with symmetric encryption lies in securely sharing the secret key between the communicating parties. If an unauthorized party gains access to the key, they can decrypt all encrypted messages.
-  Common symmetric encryption algorithms include:
  - Advanced Encryption Standard (AES)
  - Data Encryption Standard (DES)
  - Triple DES (3DES)
  - These algorithms employ various techniques to scramble the data using the shared key, making it unreadable to anyone without the key.
<br>

**ASYMMETRIC ENCRYPTION**
- Asymmetric encryption, also known as public-key cryptography, is a cryptographic method where two different keys are used: one for encryption and another for decryption.
- Each user has a pair of keys:
  - a public key :
    - The public key is freely available to anyone and is used to encrypt data
  - a private key:
    -  the private key is kept secret and is used to decrypt the data.
- The main advantage of asymmetric encryption is its ability to provide secure communication without requiring the exchange of secret keys between parties. This eliminates the need for a secure channel to exchange keys, which is a challenge in symmetric encryption.
- Asymmetric encryption is commonly used for various purposes, including secure communication, digital signatures, and key exchange protocols.
-  Some popular asymmetric encryption algorithms include:
  - RSA (Rivest-Shamir-Adleman)
  - Diffie-Hellman key exchange
  - Elliptic Curve Cryptography (ECC).
- While asymmetric encryption offers greater security and flexibility compared to symmetric encryption, it is typically slower and computationally more intensive. As a result, asymmetric encryption is often used for key exchange and digital signatures, while symmetric encryption is used for encrypting the actual data.
<br>

**PLAIN TEXT**
- Plain text refers to any data or information that is unencrypted and easily readable by humans.
- It is the original, unaltered form of data before any encryption or encoding has been applied.
- Plain text can include letters, numbers, symbols, and whitespace, and it is typically represented using a standard character encoding such as ASCII or Unicode.
- In the context of encryption:
  - plain text is the input data that undergoes encryption to produce cipher text, which is the encrypted form of the data.
  - Conversely, when cipher text is decrypted, it is converted back into plain text, restoring the original, readable form of the data.
  - While plain text is easy for humans to understand, it is vulnerable to interception and unauthorized access when transmitted over unsecured channels, such as the internet.
  - Encryption techniques, such as symmetric and asymmetric encryption, are used to protect sensitive plain text data from unauthorized access by converting it into unreadable cipher text that can only be deciphered with the appropriate decryption key.
<br>

**ENCODING IN BLOCKCHAIN**
- Encoding is primarily used to represent data in a standardized format for storage on the blockchain or for transmission between network participants. However, it's important to note that encoding in blockchain typically refers to the conversion of data into a specific format rather than encryption or compression.
- Here are a few ways encoding is used in blockchain:
  - 1. **Transaction Encoding**: When creating transactions in a blockchain network, data such as sender addresses, recipient addresses, and transaction amounts need to be formatted in a specific way before being included in a block. This often involves encoding the data according to predefined standards or protocols, such as the Bitcoin Transaction Encoding format (BTE).
    2. **Smart Contract Encoding**: Smart contracts, which are self-executing contracts with the terms of the agreement directly written into code, often involve encoding data structures and function calls in a format that can be interpreted by the blockchain's virtual machine. For example, in Ethereum, smart contracts are typically written in Solidity and compiled into bytecode, which is an encoded representation of the contract's functionality.
    3. **Data Encoding in Blocks**: The data stored within blocks on a blockchain network, such as transaction data or smart contract code, may be encoded using specific serialization formats like Protocol Buffers (protobuf) or JSON (JavaScript Object Notation) to ensure efficient storage and transmission across the network.
    4. **Address Encoding**: Public addresses associated with cryptocurrency wallets are often encoded using specific algorithms or formats to ensure their uniqueness and compatibility with the underlying blockchain protocol. For example, Bitcoin addresses are encoded using Base58Check encoding.
- Overall, encoding in blockchain serves to standardize the representation of data within the network, ensuring interoperability between different systems and participants while maintaining data integrity and security.
<br>

**HASHING**
- Hashing is a process of converting input data, such as text or numbers, into a fixed-size string of characters, typically through a mathematical algorithm.
- The output, called a hash value or hash code, is unique to the input data.
- Hashing is widely used in computer science for various purposes, including data storage, cryptography, and data integrity verification.
- In hashing, the input data can be of any length, but the output hash value will always have a fixed length.
  - This property makes hashing useful for tasks like storing passwords securely, as it allows systems to store only the hashed values rather than the actual passwords.
- Common hashing algorithms include;
  - MD5 (Message Digest Algorithm 5)
  -  SHA-1 (Secure Hash Algorithm 1)
  -  SHA-256, and many others.
  -  These algorithms vary in terms of their speed, security, and the length of the hash they produce.
- enerally, more secure hashing algorithms produce longer hash values and are less prone to collisions, where two different inputs produce the same hash value.

- **Hash functions should have several key properties:**
  - 1. Deterministic: The same input will always produce the same output hash value.
    2. Fast computation: Hashing should be computationally efficient.
    3. Avalanche effect: A small change in the input should result in a significantly different hash value.
    4. Pre-image resistance: It should be computationally infeasible to reverse-engineer the original input from its hash value.
    5. Collision resistance: It should be unlikely for two different inputs to produce the same hash value.

- Despite its usefulness, it's important to note that hashing is not encryption. _Hashing is a one-way function_, meaning that it's designed to be irreversible. Once data is hashed, it cannot be feasibly converted back to its original form.
<br>

**P-256**
- P-256 refers to the elliptic curve cryptography (ECC) curve named NIST P-256, also known as secp256r1. It's defined by the National Institute of Standards and Technology (NIST) and is widely used for implementing public-key cryptography.
- The "P" in P-256 stands for "prime," indicating that the curve is defined over a prime field. The number "256" refers to the size of the key, measured in bits. In this case, P-256 provides a security level equivalent to using a 128-bit symmetric key.
- P-256 is commonly used in various cryptographic protocols and applications, including SSL/TLS for secure web browsing, digital signatures, and secure communication in various systems. It's particularly popular for its balance between security and efficiency, making it suitable for a wide range of applications, including those with limited computational resources such as embedded systems and IoT devices.
- Here are some common applications and use cases:

1. **Secure Communication**: P-256 is used in protocols like SSL/TLS to establish secure communication channels over the internet, ensuring that data exchanged between a client and a server remains confidential and cannot be tampered with by unauthorized parties.

2. **Digital Signatures**: P-256 is used for generating and verifying digital signatures. Digital signatures are essential for ensuring the authenticity and integrity of messages or documents in scenarios like email communication, software distribution, and financial transactions.

3. **Key Exchange**: P-256 is used in key exchange protocols such as Diffie-Hellman key exchange to securely establish shared secret keys between parties. These shared keys can then be used for encrypting and decrypting messages.

4. **Authentication**: P-256 is used for user authentication in various systems, such as secure login processes for websites and online services. It allows users to prove their identity securely without transmitting sensitive information like passwords over insecure channels.

5. **Blockchain and Cryptocurrencies**: P-256 is used in blockchain technologies, including cryptocurrencies like Bitcoin and Ethereum, for generating public-private key pairs and signing transactions. It ensures the security and integrity of transactions recorded on the blockchain.

6. **Embedded Systems and IoT**: P-256's efficiency makes it suitable for use in resource-constrained environments, such as embedded systems and IoT devices, where computational resources like memory and processing power are limited. It enables secure communication and authentication in these devices.

Overall, P-256 plays a crucial role in ensuring the confidentiality, integrity, and authenticity of data in various applications and environments where security is paramount.

<BR>

**POLYGON** : 
- Polygon is a blockchain platform which aims to create a multi-chain blockchain system compatible with Ethereum.
- As with Ethereum, it uses a proof-of-stake consensus mechanism for processing transactions on-chain.
- Polygon's native token is named MATIC.
- Initial release date: 2017
- Block explorer: polygonscan.com
- Code: $MATIC
- Developer(s): Polygon Technology
- Ledger start: June 1, 2020; 3 years ago
- Original author(s): Jaynti Kanani, Sandeep Nailwal, Anurag Arjun, and Mihailo Bjelic
- Source model: Open source
