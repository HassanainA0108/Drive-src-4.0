# Decentralized Image Upload and Sharing DApp

A decentralized application (DApp) that enables users to securely upload and share images using blockchain and decentralized storage technologies.

## 🚀 Features

- 📦 **Decentralized Storage**: Images are stored on IPFS ensuring immutability and distributed access.
- 🔐 **Smart Contract Access Control**: Solidity-based contract on Ethereum handles image ownership and permissioning.
- 👥 **User Access Management**: Grant and revoke access to uploaded images for specific Ethereum addresses.
- 🖼️ **Frontend Interface**: Built with React to interact with the smart contract and IPFS seamlessly.

---

## 🛠 Technologies Used

| Layer        | Tech Stack                          |
|--------------|-------------------------------------|
| Smart Contract | Solidity, Hardhat                  |
| Frontend     | React.js, CSS, Ant Design (optional)|
| Storage      | IPFS (via Infura or Web3.Storage)   |
| Web3         | Ethers.js                           |
| Testing      | Jest (for React), Hardhat Tests     |

---

## 📁 Project Structure

Drive-src-4.0/
│
├── client/ # Frontend (React)
│ ├── public/ # Static files
│ └── src/
│ ├── components/ # Reusable components
│ │ ├── FileUpload.js # Image upload logic
│ │ ├── Display.js # Display images
│ │ ├── Modal.js # Access control modal
│ ├── App.js # Main React component
│ ├── index.js # Entry point
│ └── ...
│
├── contracts/
│ └── Upload.sol # Smart contract
│
├── scripts/
│ └── deploy.js # Deployment script
│
├── hardhat.config.js # Hardhat configuration
└── README.md # Project overview
