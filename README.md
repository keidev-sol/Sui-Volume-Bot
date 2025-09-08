# ⚡ SUI Volume Bot (CETUS DEX)

[![Made with TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)](https://www.typescriptlang.org/)
[![Sui Network](https://img.shields.io/badge/Blockchain-SUI-blue)](https://sui.io/)
[![Cetus DEX](https://img.shields.io/badge/DEX-CETUS-purple)](https://www.cetus.zone/)

Automated trading bot for the **Cetus DEX** on the Sui blockchain.  
The bot performs **endless buy and sell swaps** to generate trading **volume** and **maker activity** while keeping **gas costs minimal**.

> ⚠️ This repo contains a **compiled demo version**.  
> The original project is written in TypeScript. For full access, contact the author on [Twitter](https://twitter.com/kei_4650) or [Telegram](https://t.me/Kei4650).

---

## ✨ Features

- ⚙️ **Automated SUI Distribution** → funds new wallets automatically.
- 🔄 **Endless Buy & Sell Swaps** → creates constant market activity.
- 🛠️ **Configurable Parameters** → swap size, timing, distribution, pool ID, etc.
- ⛽ **Optimized Gas Usage** → efficient transaction handling.

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/keidev-sol/SUI-Volume-Bot-CETUS.git
cd SUI-Volume-Bot-CETUS

```

---

## ⚙️ Configuration

cp .env.copy .env


PRIVATE_KEY=your_sui_wallet_private_key

NETWORK=mainnet

RPC_ENDPOINT=https://rpc.ankr.com/sui/<RPC_API_KEY>
RPC_WEBSOCKET_ENDPOINT=wss://rpc.ankr.com/sui/ws/<RPC_API_KEY>

DISTRIBUTE_INTERVAL_MAX=30  # seconds
DISTRIBUTE_INTERVAL_MIN=20  # seconds

BUY_INTERVAL_MAX=10         # seconds
BUY_INTERVAL_MIN=5          # seconds

SWAP_AMOUNT_MAX=0.5         # SUI
SWAP_AMOUNT_MIN=0.1         # SUI

POOL_ID=


---

## 👤 Author

### Twitter: [@Kei Novak](https://twitter.com/kei_4650)   

### Telegram: [@Kei Novak](https://t.me/Kei4650)   

---
