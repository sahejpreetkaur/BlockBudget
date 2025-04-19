# 💸 BlockBudget – Blockchain-Based Expense Tracker

> A secure, tamper-proof expense tracking application built with **React**, **TypeScript**, and a custom **JavaScript blockchain**. BlockBudget uses blockchain principles to ensure financial records are immutable and verifiable.

---

## 📌 Table of Contents
- [🔍 Overview](#-overview)
- [🚀 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📦 Installation](#-installation)
- [🧪 Usage](#-usage)
- [🧱 Blockchain Structure](#-blockchain-structure)
- [🧠 Learnings](#-learnings)
- [📸 Screenshots](#-screenshots)
- [📈 Future Scope](#-future-scope)
- [📄 License](#-license)

---

## 🔍 Overview

**BlockBudget** is a decentralized expense tracker where each transaction is logged onto a blockchain. Unlike traditional apps, it ensures:

- 🔒 Immutability — Transactions cannot be altered once added.
- 🧾 Transparency — Users can view the full history in a chain format.
- 🚫 No Central Database — Trust is distributed and maintained via cryptographic hashing.

Perfect for both **personal budgeting** and **educational demos** of blockchain applications.

---

## 🚀 Features

- ✅ Custom blockchain built from scratch using TypeScript
- ✅ Add new expenses with mining simulation (Proof-of-Work)
- ✅ View full chain of expenses in a clean UI
- ✅ Real-time blockchain validation and tamper detection
- ✅ Responsive design with Tailwind CSS
- 🔧 Easily extendable for multi-user or backend support

---

## 🛠️ Tech Stack

| Layer       | Technology                        |
|-------------|------------------------------------|
| Frontend    | React, TypeScript, Tailwind CSS    |
| Blockchain  | Custom logic using SHA256 (crypto-js) |
| Dev Tools   | Vite, ESLint, Prettier             |
| State Mgmt  | React Hooks (`useState`, `useEffect`) |
| Deployment  | [Docker - *not yet added*]         |

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/blockbudget.git
cd blockbudget

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## 🧪 Usage

- Navigate to `http://localhost:5173`
- Add new expense entries via the form
- View all added blocks in the Blockchain Visualizer
- Try tampering with the chain in dev tools and click "Validate Blockchain" to test immutability

---

## 🧱 Blockchain Structure

Each expense is stored in a block with the following structure:

```json
{
  "index": 2,
  "timestamp": "2025-04-15T16:40:30",
  "data": {
    "description": "Grocery Shopping",
    "amount": 2100,
    "category": "Food"
  },
  "previousHash": "00adf12b3c...",
  "hash": "005d8fe21b...",
  "nonce": 2984
}
```

---

## 🧠 Learnings

- Understanding of blockchain internals (hashing, nonce, PoW)
- TypeScript and component-based architecture in React
- Tailwind CSS for fast, responsive UI development
- Vite for modern web bundling and dev experience

---

## 📸 Screenshots

> *(Include images here after capturing from your project)*  
- ✅ Expense form UI  
- ✅ Blockchain visualizer  
- ✅ Console log showing mining process  
- ✅ Validation result for tampered/valid chains  

---

## 📈 Future Scope

- 👥 Add user authentication and profiles
- 💾 Store blockchain in persistent backend (MongoDB/Firebase)
- 📊 Visual analytics (monthly spending charts)
- 📱 Convert into a PWA or mobile app
- 🔗 Generate QR codes or shareable links for each block
- 🌍 P2P version with decentralized node syncing

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
