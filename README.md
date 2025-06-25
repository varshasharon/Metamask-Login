# Metamask-Login

A simple decentralized authentication system using MetaMask and Ethereum. This project allows users to sign in using their MetaMask wallet, verifying identity via cryptographic signature, without needing passwords.

## Features
🦊 MetaMask wallet integration (Ethereum-based authentication)
🔐 Nonce-based signature verification for secure login
🧑‍💻 Frontend: HTML, CSS, JavaScript
🌐 Backend: Node.js + Express.js
🔁 Stateless login (no session/password storage)
📦 Uses crypto for nonce generation and ethers.js for signature verification

##  Tech Stack
### Frontend

HTML5, CSS3, JavaScript
MetaMask Ethereum provider (window.ethereum)
Wallet signature interaction

### Backend

Node.js
Express.js
crypto module for secure nonce generation
ethers.js for Ethereum signature verification

## How It Works

1. User connects MetaMask wallet.
2. Client requests a unique nonce from the backend.
3. User signs the nonce using their Ethereum wallet.
4. The signed message is sent to the backend.
5. Backend verifies:
   -  Wallet address
   -  Signature matches the nonce
6. If verified, the user is authenticated.
   
