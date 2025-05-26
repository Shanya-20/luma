# SimpleWill Smart Contract

A simple Ethereum smart contract that acts as a digital will. It allows an owner to set a recipient who can claim the funds after a set period of inactivity by the owner.

---

## 📜 Features

- ✅ Owner can signal they are alive using `ping()`
- ⏰ If owner is inactive for a period (default: 60 seconds for testing), the recipient can claim all contract funds
- 🔐 Access control: only the owner can ping, and only the recipient can claim
- 💰 Accepts and transfers ETH securely

---

## 🧱 Contract Details

- **Language**: Solidity `^0.8.0`
- **License**: MIT
- **Inactivity Period**: 60 s

```
contact details:0xf8e81D47203A594245E36C48e151709F0C19fBe8

![Screenshot (1)](https://github.com/user-attachments/assets/959a4474-18ad-4a93-9d5a-4728530fdb68)
