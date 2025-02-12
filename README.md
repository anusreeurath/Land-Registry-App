# Land-Registry-App
A decentralized land registry DApp using Ethereum blockchain and Solidity smart contracts for secure land registration and ownership transfer.<br>

# Problem Statement
Traditional land registry systems suffer from fraud, corruption, lack of transparency, and inefficiencies due to manual record-keeping. There is a need for a <br>secure, decentralized, and tamper-proof system that ensures land ownership authenticity and enables seamless ownership transfers.
This project aims to build a decentralized application (DApp) for land registry using Ethereum smart contracts to provide:         
  1.Tamper-proof land records stored on the blockchain.
  2.Secure and verifiable land ownership transfer without intermediaries.
  3.Transparency and trust in property transactions.
  4.Elimination of fraudulent land ownership claims.
The system will allow users to register land parcels, transfer ownership, and verify land details in a secure and efficient manner.

# Objectives
1.Land Registration – Allow users to register land parcels with unique IDs, location details, and ownership information.
2.Ownership Transfer – Enable secure transfer of land ownership without intermediaries, ensuring authenticity.
3.Verification & Transparency – Provide a publicly verifiable and tamper-proof record of land ownership.
4.Security & Fraud Prevention – Reduce the risk of fraudulent land sales and illegal modifications to records.

# Features
*Blockchain-based Storage – All land records are stored on Ethereum’s blockchain, ensuring transparency and security.
*Smart Contract Execution – Automated transactions remove the need for third-party verification.
*Decentralization – Eliminates single points of failure and enhances trust among users.
*Ownership Verification – Any user can verify ownership details by querying the smart contract.
*Immutable Transactions – Once a land parcel is registered or ownership is transferred, it cannot be altered fraudulently.

# Technologies Used
*Ethereum – For deploying smart contracts.
*Solidity – Smart contract programming language.
*Remix IDE – For writing and compiling smart contracts.
*MetaMask – For interacting with the Ethereum blockchain.
*Web3.js – For connecting the frontend with blockchain transactions.

# Working Mechanism
1.Land registration: The landowner calls the registerLand function by providing land details. The smart contract records the information and assigns ownership to the sender’s Ethereum address.
2.Ownership transfer: The registered owner calls the transferOwnership function and specifies the new owner's Ethereum address. The ownership is updated, and a transaction is recorded.
3.Land verification: Anyone can call the getLand function by providing a land ID to retrieve land details.

# Results

![RegCanada](https://github.com/user-attachments/assets/9bde6e23-ca5f-4d2a-8269-982f891bf3e2)
Register Land with input id=1,location=canada and area=200





