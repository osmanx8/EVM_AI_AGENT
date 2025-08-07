# 🤖 EVM AI Agent
EVM AI Agent is a conversational AI interface designed for seamless interaction with EVM-compatible blockchains. Through natural language input, users can perform complex blockchain operations like transactions, contract deployments, token management, and more—all within a friendly, chat-driven environment..

---

## 🔥 🚀 Key Capabilities

### 🔧 Blockchain Operations
Conduct token transfers, swaps, and bridge operations

Automatically generate, deploy, and verify smart contracts

Launch custom tokens with metadata and advanced parameters

### 🧠 AI-Powered Understanding
Interprets natural commands (e.g., “swap 1 ETH to USDC on Ethereum”)

Breaks down multi-step tasks with confirmation flows

Simplifies blockchain interactions with clear explanations

### 🪙 Wallet & Token Utilities
Retrieve wallet balances across ETH and ERC tokens

Resolve token names and addresses accurately

Fetch live market data using integrated price feeds (via CoinGecko)

Detect the correct chain context (Ethereum, Polygon, Onyx, etc.)

### 🔐 Embedded Wallet Support (via Privy)
Instantly generates embedded wallets for new users

Supports linking external wallets

Allows in-chat transfers, top-ups, and transaction approvals

### 📚 Onyx Chain Integration
- Automatically fetches context from Onyx Chain whitepaper PDF
- Answers Onyx-specific queries more accurately than LLM alone

### 💬 Prompt & Session Management
- 10 free prompts per user per day
- Session-based memory like ChatGPT
- Persistent history and session restarts

---

## 🧠 Tech Stack

| Layer             | Tech Used                          |
|------------------|------------------------------------|
| Language Model    | OpenAI (GPT-4o)              |
| Backend           | Nest.js, TypeScript, Express        |
| Wallets           | Privy Embedded Wallets              |
| Web3              | Ethers.js, Alchemy, RPCs            |
| APIs              | CoinGecko, CoinMarketCap, Etherscan |
| Verification      | Etherscan Contract Verification     |
| Data Extraction   | PDF to Text AI Parsing              |
| Memory            | mongodb     |

---

## 📦 Example Prompts

| Use Case         | Prompt Example                                                    |
|------------------|-------------------------------------------------------------------|
| **Token Swap**   | `swap 1 ETH to USDC on Ethereum mainnet`                          |
| **Balance Check**| `check 0xabc...abc ETH balance`                                   |
| **Token Deploy** | `deploy token (name TEST, symbol TST, supply 1000, decimals 18)`  |
| **Generate Code**| `generate USDC staking contract that rewards 2x per week`         |
| **Deploy & Verify**| `deploy and verify it on Base`                                 |
| **Price Info**   | `what’s the price of PEPE on Polygon?`                            |
| **Onyx Support** | `what is Onyx Chain?` (used PDF whitepaper for accurate answers)  |

---

## ⚠️ Notice
This repository contains only the frontend component for security and IP protection.
If you're interested in the full system (including backend services), please reach out directly:

📧 Email: hyperbuildx@adamglab.dev

💬 Telegram: @web3_maxim
