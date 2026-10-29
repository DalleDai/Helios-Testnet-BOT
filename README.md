# ☀️ Helios Testnet BOT - CDY

Automate your journey through Helios ecosystem projects - Testnet operations and SolariSwap DEX automation in full drip-mode 😎  

---

## 🔗 Quick Start

### Helios Testnet Bot
- Register: [Helios Testnet](https://testnet.helioschain.network/?code=GENESIS-OLYMPIC-636)
- Use Invite Code: `GENESIS-OLYMPIC-636`
- Connect Discord to register

### SolariSwap Bot
- Register: [SolariSwap](https://solariswap.finance/)
- Use same wallet as Helios Testnet

---

## 🚀 Features

### Helios Testnet Bot (`bot1.py`)
✅ Auto Fetch Account Info  
✅ Auto Faucet Claim (Requires 2captcha key)  
✅ Auto Bridge HLS → Sepolia  
✅ Auto Delegate HLS to Validators  
✅ Auto Claim Delegation Rewards  
✅ Auto Deploy Token Contract  
✅ Auto Vote Governance Proposal 
✅ Auto Create Governance Proposal 
✅ Proxy Support (Public/Private/None)  
✅ Smart Proxy Rotation  
✅ Multi-Account Support  

### SolariSwap Bot (`bot2.py`)
✅ Auto Get Account Information  
✅ Auto Execute Random Swaps  
✅ Proxy Support (Public/Private/None)  
✅ Smart Proxy Rotation  
✅ Multi-Account Support  

> ⚠️ More features coming soon. Stay tuned.

---

## 🛠️ Requirements

- Python 3.9+ 
- Pip package manager
- 2captcha key (For Helios faucet claims only)

---

## ⚙️ Installation

1. **Clone Repository**
```bash
git clone https://github.com/DalleDai/Helios-Testnet-BOT.git
cd Helios-Testnet-BOT
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```
or
```bash
pip3 install -r requirements.txt
```

3. **Verify Library Versions**  
If encountering issues, check and match these versions:
```bash
pip show web3 eth-account eth-utils cryptography
pip uninstall <mismatched_lib>
pip install <lib_name>==<required_version>
```

---

## 🧾 Configuration Files

### Shared Files:
1. **accounts.txt** (Both bots)
```bash
private_key_1
private_key_2
```

2. **proxy.txt** (Both bots)
```bash
ip:port
http://ip:port
http://user:pass@ip:port
```

### Helios Exclusive:
3. **2captcha_key.txt** (Helios bot only)
```bash
your_2captcha_api_key
```

---

## ▶️ Run Bots

**Helios Testnet Bot:**
```bash
python bot1.py
# or
python3 bot1.py
```

**SolariSwap Bot:**
```bash
python bot2.py
# or
python3 bot2.py
```

---

## ☕ Support Development

Consider supporting our work:

- **EVM:** `0x3b94Ff1611773171E06047C0041099CccCFC609F`

---

## 🔒 Security & Disclaimer

### ⚠️ Important
- **TESTNET USE ONLY** - Never use mainnet wallets
- **ZERO LIABILITY** - Use at your own risk
- **DYOR** - Always audit code before execution

### 🔐 Best Practices
1. Use dedicated testnet wallets
2. Never expose private keys
3. Verify all contract interactions
4. Monitor bot activities regularly

---

## 🙌 Community Support

Help us improve:
- ⭐ Star the repository
- 🐛 Report issues
- 💡 Suggest features
- 📢 Share with your community

**Happy Farming! 🚀🌾**  
*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes (where applicable)
* 💡 Contribute ideas and code

---

## 📝 License

This project is licensed under the MIT License.

---
