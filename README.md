# 💰 TokenWallet: A Blockchain-Based Token Wallet Application

## Overview

**TokenWallet** is a blockchain-powered decentralized application (dApp) for managing digital tokens. It allows users to securely create wallets, send and receive tokens, and visualize their transaction history. The app integrates blockchain technology, ensuring immutability and transparency of all transactions. Additionally, it offers an interactive visualization of the blockchain and the underlying Merkle Tree structure of transactions for enhanced transparency.

This application was built using **Streamlit**, **NetworkX**, **Matplotlib**, and **Python**, focusing on simplicity and usability while demonstrating the power of blockchain and Merkle Trees for secure transaction management.

### [🌐 Live Demo](https://blockchainwallet.streamlit.app/) — Explore the deployed app

## Key Features

- **Wallet Management**: Create, manage, and switch between multiple wallets.
- **Token Transactions**: Send and receive tokens between wallets with easy-to-use forms.
- **Transaction History**: View and download the complete transaction history of your wallet.
- **Blockchain Visualization**: See how each block is created and linked, representing the tamper-proof chain of transactions.
- **Merkle Tree Visualization**: Visualize the Merkle Tree structure for each block, ensuring transaction integrity.
- **Blockchain Security**: Each block is secured with a cryptographic hash and includes a Merkle root for transaction verification.


## 🛠️ Installation and Setup

To run this project locally, follow the steps below:

### Prerequisites

Make sure you have the following installed:

- Python 3.7+
- Pip (Python package manager)

### Steps to Set Up

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/TokenWallet.git
   cd TokenWallet
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**:

   ```bash
   streamlit run app.py
   ```

5. **Access the app**:
   
   Open your web browser and go to [http://localhost:8501](http://localhost:8501).

---

## 📜 How It Works

1. **Wallet Creation**: 
   Users can create multiple wallets that store their token balances.
   
2. **Send and Receive Tokens**: 
   Easily transfer tokens between wallets by selecting the recipient wallet and entering the desired token amount.

3. **Blockchain Visualization**: 
   Each transaction is recorded into blocks, which are cryptographically linked together to form a blockchain. This chain is displayed in the app for transparency.

4. **Merkle Tree**:
   Each block's transactions are represented as a Merkle Tree, where transaction integrity is verified by comparing the tree's root hash. The tree structure is visualized for the most recent block.

---

## 🧩 Technologies Used

- **Python**: The core programming language for blockchain logic and wallet management.
- **Streamlit**: An open-source app framework for creating data apps.
- **NetworkX**: A powerful library for the creation, manipulation, and visualization of complex networks like the blockchain and Merkle Trees.
- **Matplotlib**: For rendering visual graphs of the blockchain and Merkle Trees.

---

## 🚀 Future Enhancements

In the future, the following features could be added:

- **Advanced Wallet Features**: Add support for multiple cryptocurrencies or token standards like ERC-20.
- **Multi-Signature Wallets**: Implement multi-signature wallets for enhanced security.
- **Smart Contract Integration**: Use smart contracts to automate transactions or provide additional functionality like staking.
- **User Authentication**: Add secure user authentication for multi-device access to wallets.
  
---

## 🧑‍💻 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.


