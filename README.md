# Land-Registry-App
A decentralized land registry DApp using Ethereum blockchain and Solidity smart contracts for secure land registration and ownership transfer.<br>

# Problem Statement
Traditional land registry systems suffer from fraud, corruption, lack of transparency, and inefficiencies due to manual record-keeping. There is a need for a secure, decentralized, and tamper-proof system that ensures land ownership authenticity and enables seamless ownership transfers.<br>
This project aims to build a decentralized application (DApp) for land registry using Ethereum smart contracts to provide:<br>         
  1.Tamper-proof land records stored on the blockchain.<br>
  2.Secure and verifiable land ownership transfer without intermediaries.<br>
  3.Transparency and trust in property transactions.<br>
  4.Elimination of fraudulent land ownership claims.<br>
The system will allow users to register land parcels, transfer ownership, and verify land details in a secure and efficient manner.<br>

# Objectives
1.Land Registration – Allow users to register land parcels with unique IDs, location details, and ownership information.<br>
2.Ownership Transfer – Enable secure transfer of land ownership without intermediaries, ensuring authenticity.<br>
3.Verification & Transparency – Provide a publicly verifiable and tamper-proof record of land ownership.<br>
4.Security & Fraud Prevention – Reduce the risk of fraudulent land sales and illegal modifications to records.<br>

# Features
*Blockchain-based Storage – All land records are stored on Ethereum’s blockchain, ensuring transparency and security.<br>
*Smart Contract Execution – Automated transactions remove the need for third-party verification.<br>
*Decentralization – Eliminates single points of failure and enhances trust among users.<br>
*Ownership Verification – Any user can verify ownership details by querying the smart contract.<br>
*Immutable Transactions – Once a land parcel is registered or ownership is transferred, it cannot be altered fraudulently.<br>

# Technologies Used
*Ethereum – For deploying smart contracts.<br>
*Solidity – Smart contract programming language.<br>
*Remix IDE – For writing and compiling smart contracts.<br>
*MetaMask – For interacting with the Ethereum blockchain.<br>
*Web3.js – For connecting the frontend with blockchain transactions.<br>

# Working Mechanism
1.Land registration: The landowner calls the registerLand function by providing land details. The smart contract records the information and assigns ownership to the sender’s Ethereum address.<br>
2.Ownership transfer: The registered owner calls the transferOwnership function and specifies the new owner's Ethereum address. The ownership is updated, and a transaction is recorded.<br>
3.Land verification: Anyone can call the getLand function by providing a land ID to retrieve land details.<br>

# Results

![RegCanada](https://github.com/user-attachments/assets/9bde6e23-ca5f-4d2a-8269-982f891bf3e2)
Register Land with input id=1,location=canada and area=200





