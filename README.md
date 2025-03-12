# MeganetAutoRefBot

join https://meganet.app/login?refcode=DV130H

An automated solution for **Meganet wallet registration** and **point farming**, featuring advanced proxy and user-agent rotation support.

---

## 🌟 Features

- ✅ Automated wallet registration with **referral code integration**.
- ✅ Scheduled **point farming** through periodic ping operations.
- ✅ Comprehensive **proxy support** for managing multiple wallets.
- ✅ **User-agent rotation** to ensure secure and diverse operations.
- ✅ Interactive **Solana wallet generator** for seamless wallet creation.
- ✅ **Batch processing**—handle up to 100 wallets in one go.
- ✅ Automated task execution for each wallet.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- **Node.js** (version 14 or higher)
- **NPM** (version 6 or higher)

---

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zcsaqueeb/Meganet.git
   cd Meganet
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Configure your setup:
   - Add wallet addresses in `wallets.json`
   - Include proxies in `proxy.txt` (one proxy per line)
   - Adjust settings in `config.json`

---

### Solana Wallet Generator

Use the built-in tool to easily create Solana wallets:

1. Run the wallet generator script:
   ```bash
   node generateWallets.js
   ```

2. Enter the number of wallets to generate when prompted.

3. The script will:
   - Create wallets with **unique IDs**.
   - Append new wallets to the existing `wallets.json` file.
   - Display the **public addresses** of the generated wallets.

---

## 🛠 Configuration

### `wallets.json`

Store wallet data in the following format:
```json
[
  {
    "id": 1,
    "address": "YOUR_WALLET_ADDRESS_1",
    "privateKey": "YOUR_PRIVATE_KEY_1"
  },
  {
    "id": 2,
    "address": "YOUR_WALLET_ADDRESS_2",
    "privateKey": "YOUR_PRIVATE_KEY_2"
  }
]
```

### `proxy.txt`

Define your proxy list (one per line):
```
http://username:password@host:port
socks5://username:password@host:port
```

### `config.json`

Customize bot settings:
```json
{
  "refCode": "YOUR_REFERRAL_CODE",
  "pingInterval": 15000,
  "useProxy": true,
  "processTasks": true
}
```
- **refCode**: Add your Meganet referral code.
- **pingInterval**: Set interval between pings (milliseconds).
- **useProxy**: Enable (`true`) or disable (`false`) proxy usage.
- **processTasks**: Automate task completion (`true`) or manage tasks manually (`false`).

---

## 💻 Usage

### Start Referral Automation:
```bash
node ref.js
```

### Begin Point Farming:
```bash
node index.js
```

---

## ⚠ Disclaimer

This bot is designed for **educational purposes only**. Usage is at your own risk. The developers bear no responsibility for any outcomes resulting from its use.

---

## 📜 License

This project is licensed under the **MIT License**.

---
