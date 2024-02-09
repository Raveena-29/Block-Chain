# BLOCK CHAIN

## What is block chain?
- A blockchain is a decentralized, distributed and public digital ledger that is used to record transactions across many computers so that the record cannot be altered retroactively without the alteration of all subsequent blocks and the consensus of the network.
<br>

**ENCRYPTION**
-  Encryption is the process of protecting information or data by using mathematical models to scramble it in such a way that only the parties who have the key to unscramble it can access it.
-  There are two types of encryption in widespread use today:
  - Symmetric encryption.
  - Asymmetric encryption. 
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
