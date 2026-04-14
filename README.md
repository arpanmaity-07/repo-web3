# 🚀 Simple DEX on Stellar (Soroban)

## 📌 Project Description

This project is a basic **Decentralized Exchange (DEX)** smart contract built using **Soroban** on the **Stellar blockchain**.
It demonstrates how users can deposit tokens, manage balances, and perform token swaps in a decentralized environment.

---

## ⚙️ What it does

* Allows users to deposit tokens into the contract
* Stores user balances on-chain
* Enables token swapping between assets
* Uses a **fixed 1:1 swap rate** for simplicity

---

## ✨ Features

* 🔐 Secure authentication using `require_auth()`
* 💰 Token deposit system
* 📊 Balance tracking (user + token)
* 🔄 Token swap functionality
* ⚡ Lightweight and beginner-friendly smart contract

---

## 🧠 How it Works

1. Users deposit tokens into the contract
2. Contract stores balances in on-chain storage
3. Users call the swap function
4. Tokens are exchanged at a fixed rate
5. Balances are updated automatically

---

## 🛠 Tech Stack

* **Rust**
* **Soroban SDK**
* **Stellar Blockchain (Testnet)**

---

## 📂 Project Structure

```
├── src/
│   └── lib.rs        # Smart contract logic
├── Cargo.toml        # Rust dependencies
├── target/           # Compiled WASM
└── README.md         # Documentation
```

---

## 🔗 Deployed Smart Contract

### 🌐 Contract ID

```
CCJNYKCFV6GRJWS3OUEXMUYYTF6YVH35FG4O7VB5WCJT4GMPXBJ37YNZ
```

### 🔍 View on Explorer

👉 https://stellar.expert/explorer/testnet/contract/CCJNYKCFV6GRJWS3OUEXMUYYTF6YVH35FG4O7VB5WCJT4GMPXBJ37YNZ

### 🧪 Open in Stellar Lab

👉 https://lab.stellar.org/r/testnet/contract/CCJNYKCFV6GRJWS3OUEXMUYYTF6YVH35FG4O7VB5WCJT4GMPXBJ37YNZ

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/soroban-dex.git
cd soroban-dex
```

### 2️⃣ Build contract

```
cargo build --target wasm32v1-none --release
```

### 3️⃣ Deploy contract

```
stellar contract deploy \
  --wasm target/wasm32v1-none/release/your_contract.wasm \
  --source-account alice \
  --network testnet \
  --alias your_contract
```

<img width="1920" height="1140" alt="Screenshot 2026-03-19 140846" src="https://github.com/user-attachments/assets/6fc9d786-7fbd-4b2f-9665-d239eaca1e33" />


## 📚 Future Improvements

* 💧 Add liquidity pools
* 📈 Implement AMM pricing (Uniswap-style)
* 💸 Add trading fees
* 🔗 Support multiple token pairs
* 🌐 Build frontend (React + Stellar wallet)

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and is **not production-ready**.
Security audits are required before real-world use.

---

## 🙌 Author

Built by **Arpan Maity**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
