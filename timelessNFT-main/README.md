# 🛒 Web3 NFT Marketplace

A decentralized NFT marketplace where users can mint, buy, sell, and trade NFTs using blockchain technology. Built with cutting-edge tools and technologies to provide a seamless and secure user experience.

## 🚀 Features

- **Mint NFTs:** Create unique digital assets stored on the blockchain.
- **Buy & Sell NFTs:** Securely trade NFTs using cryptocurrency.
- **Wallet Integration:** Easily connect your MetaMask wallet.
- **Responsive Design:** Tailored for all devices with Tailwind CSS.
- **Local Blockchain Testing:** Powered by Ganache-CLI.

---

## 🛠️ Tech Stack

- **Frontend:** [ReactJS](https://reactjs.org/) + [Tailwind CSS](https://tailwindcss.com/)
- **Blockchain Framework:** [Truffle](https://trufflesuite.com/)
- **Local Blockchain:** [Ganache-CLI](https://trufflesuite.com/ganache/)
- **Smart Contracts:** [Solidity](https://soliditylang.org/)
- **Wallet Integration:** [MetaMask](https://metamask.io/)
- **Blockchain Communication:** [Web3.js](https://web3js.readthedocs.io/)
- **API Service:** [Infura](https://infura.io/)
- **Test Cryptocurrency Faucet:** Simulate transactions during development.

---

## 📦 Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Truffle](https://trufflesuite.com/) (`npm install -g truffle`)
- [Ganache-CLI](https://github.com/trufflesuite/ganache-cli) (`npm install -g ganache-cli`)
- [MetaMask Extension](https://metamask.io/)

### Clone the Repository

```bash
git clone https://github.com/yourusername/nft-marketplace.git
cd nft-marketplace
```

### Install Dependencies

```bash
npm install
```

---

## 🔨 Usage

### Start Local Blockchain

In a terminal, run Ganache-CLI:

```bash
ganache-cli
```

### Compile & Deploy Smart Contracts

In the project directory:

```bash
truffle compile
truffle migrate
```

### Start the Frontend

```bash
npm start
```

---

## 💡 How to Use

1. **Connect Wallet:** Open the app in your browser and connect MetaMask.
2. **Mint NFTs:** Use the "Mint NFT" feature to create your own NFTs.
3. **Trade NFTs:** List NFTs for sale or purchase existing ones using cryptocurrency.
4. **Test Transactions:** Use the provided Faucet for testing with test Ethereum.

---

## 🔐 Environment Variables

Create a `.env` file in the root directory with the following:

```plaintext
REACT_APP_INFURA_PROJECT_ID=your-infura-project-id
REACT_APP_PRIVATE_KEY=your-wallet-private-key
REACT_APP_CONTRACT_ADDRESS=your-smart-contract-address
```

---

## 📃 Smart Contract

The core functionality is handled by a Solidity smart contract:

- **File:** `contracts/NFTMarketplace.sol`
- **Features:** NFT minting, buying, and selling.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🛡️ Acknowledgements

- [Ethereum](https://ethereum.org/)
- [OpenZeppelin](https://openzeppelin.com/)
- [Truffle Suite](https://trufflesuite.com/)
- [Infura](https://infura.io/)
- [MetaMask](https://metamask.io/)

--- 
