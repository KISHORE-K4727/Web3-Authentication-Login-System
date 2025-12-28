# Web3 Authentication Login System

A simple Web3-based authentication system that enables **passwordless login using MetaMask**.  
Users authenticate by signing a message with their wallet instead of using usernames or passwords.

## 🚀 Features
- MetaMask wallet integration
- Nonce-based message signing
- Secure signature verification
- Simple and clean frontend
- Login / Logout functionality

## 🛠️ Tech Stack
- HTML, CSS, JavaScript
- Ethers.js
- MetaMask

## ⚙️ How It Works
1. User clicks **Login with MetaMask**
2. MetaMask requests wallet access
3. User signs a nonce message
4. Wallet address is verified
5. User is logged in securely

## ▶️ Run Locally
1. Clone the repository
2. Open `index.html`
3. Use **Live Server** in VS Code
4. Make sure MetaMask is installed

## 🔐 Security Note
- No passwords are stored
- Private keys never leave MetaMask
- Authentication is done using cryptographic signatures

## 📄 License
MIT License
