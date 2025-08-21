# 📌 Crypto Wallet Simulator

A simple Crypto Wallet Simulator built in Python.  
This project demonstrates how digital wallets and transactions work using a JSON-based ledger.

Each wallet has a unique address, balance, and can transfer coins to other wallets.  
All transactions are permanently recorded in `transactions.json`, while wallet details are saved in `wallets.json`.

---

## 🚀 Features
- Create new wallets with unique addresses  
- Store wallet balances in `wallets.json`  
- Transfer coins between wallets  
- Record every transaction with sender, receiver, amount, and timestamp in `transactions.json`  
- Beginner-friendly simulation of how a blockchain wallet works  

---

## 🛠️ Requirements
- Python 3.x  
- No external libraries needed (only built-in `json` and `hashlib`)  

---

## ▶️ How to Run
```bash
git clone https://github.com/your-username/crypto-wallet-simulator.git
cd crypto-wallet-simulator
python crypto_wallet.py
