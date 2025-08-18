📂 File Upload Blockchain Project

Hi! 👋 I’m Abhay, and this is my File Upload DApp.
I built it to learn how blockchain can be used for secure file storage and access control.

📌 What it Does

Upload Files – Users can upload files (images, docs, etc.) that get stored on IPFS.

Share Access – File owners can grant or revoke access to other users.

Secure Storage – Metadata and permissions are stored on the blockchain for transparency.

View Files – Users with access can retrieve and view the file anytime.

Basically, it’s like Google Drive but decentralized — no central authority, only blockchain-based access control.

🛠 Tech Stack

Solidity – Smart contracts for access control

React.js – Frontend UI

Ethers.js – Blockchain integration

IPFS – File storage (instead of a centralized server)

Hardhat – Smart contract development & testing

💡 How it Works

Connect your wallet (MetaMask).

Upload a file → File goes to IPFS, hash is stored on blockchain.

Owner can share/revoke access with other wallet addresses.

Users with access can view/download the file directly.

🚀 How to Run Locally
# Clone the repo
git clone https://github.com/abhaysingh200/File-Upload-Blockchain.git

# Go into the project folder
cd File-Upload-Blockchain

# Install dependencies
npm install

# Start the frontend
npm start
