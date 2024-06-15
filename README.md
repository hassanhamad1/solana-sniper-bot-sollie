<div align="center">
    <h1>📟 Sollis Sniper Bot</h1>



</div>

---

<p align="center">
    <img src="https://img.shields.io/github/stars/0xtaodev/jupiter-python-cli">
    <img src="https://img.shields.io/github/forks/0xtaodev/jupiter-python-cli">
    <br>
</p>

# 📖 Introduction
**Sollis Sniper Bot** is a Command Line Interface (CLI) where you can use it's features** including a **Sniper Bot**.<br>

# ⚠️ Disclaimer
**Please note that I'm not responsible for any loss of funds, damages, or other libailities resulting from the use of this software or any associated services.<br>
This tool is provided for educational purposes only and should not be used as financial advice, it is still in expiremental phase so use it at your own risk.**

# ✨ Quickstart

This project has been made for Python 3.11

## 🛠️ Installation

💾 **Dwonload this repository**
```sh
    Download this repo
```
💻 **Open the cmd**
```sh
    open a cmd in the downloaded folder
```
🌐 **Install all the libraries**
```sh
 run the command (pip install -r requirements.txt)
```
▶️ **Start**
```sh
py main.py
```


![](https://github.com/timuruva/realtime-processing/blob/127d46a2edc57ec1449d8976e04f301e3c1997b7/Files/line.gif)

# 🗺️ Overview
```
📟 Sniper
│
├── 🪐 Jupiter Exchange
│   ├── Swap
│   ├── Limit Order
│   │   ├── Open Limit Order
│   │   ├── Display Canceled Orders History
│   │   └── Display Filled Orders History
│   ├── DCA
│   │   ├── Open DCA Account
│   │   └── Manage DCA Accounts
│   ├── Token Sniper
│   │   ├── Add a token to snipe
│   │   ├── Watch token
│   │   └── Edit tokens
│   └── Change wallet
├── 💳 Manage Wallets
│   ├── Add wallet
│   ├── Edit wallet name
│   └── Delete wallet(s)
├── 🔧  settings
│   ├── Solana RPC URL Endpoint
├── ❓ About
└── 🔚 Exit 
```


![](https://github.com/timuruva/realtime-processing/blob/127d46a2edc57ec1449d8976e04f301e3c1997b7/Files/line.gif)

# 🤖 Sniper Bot
**In top of most of the  features that you can use, you are also able to snipe token.**<br>
❗**Please note that Sniper Bot is experimental and subject to change as there might be issues that I didn't see.**

### ⚙️ How it works
Every second, the bot will send a GET request to [Jupiter API Quote](https://quote-api.jup.ag/v6/quote).<br>
If there is a route available for this token, it will then execute it.<br>
Please note that only tokens with sufficient liquidity and on-chain metadata are listed in Jupiter API: min. 250$ liquidty and buy/sell price impact are below 30%.<br>
When these criteria are met, it will take a few minutes to automatically add the token.<br>

### 🆕 Add a token to snipe
- Token/Project name
- Token Address
- Amount ($) to buy
- Take Profit ($)
- Stop Loss ($)
- Slippage (%)

If token has a launch date:
- Month
- Day
- Hours
- Minutes

### ✍🏻 Edit tokens
You can modify token info as follow:
- Name
- Address
- Selected Wallet
- Buy Amount
- Take Profit
- Stop Loss
- Slippage
- Launch date
- Delete

# 🗨️ Q&A
### Where are my private keys?
*Your private keys are stored in `wallets.json`.*
### Is there any fees when swapping using CLI?
*There are no additional fees when performing swaps via the CLI; the costs should be the same as using the Jupiter UI.*
### Does sniper bot remains running if I close the CLI?
*If you close the CLI, the sniper bot will stop running.*
### Is it possible to swap any tokens?
*You can only swap tokens that are listed on Jupiter based on their criterias.*

