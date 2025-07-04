# Octra-wallet-generation-guide

## 💼 Wallet generation Guide

---

### 🔹 Step 1:
```bash
curl -fsSL https://bun.sh/install | bash  
source ~/.bashrc  
bun --version

🔹 Step 2:
bun install

🔹 Step 3:
bun run build

🔹 Step 4:
bun start

click the “PORTS” tab open link under forwarded address in browser

Wallet Generated, Back up private key

Go to https://faucet.octra.network/

Paste Wallet address & claim faucet

Join Discord - https://discord.gg/gfAazqK9Xb

Quest1 - Send Tokens
Step 1
pip install -r requirements.txt
Step 2
cp wallet.json.example wallet.json
Step 3
Then open the file: wallet.json

Paste your test wallet details

{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
🔹 Step 4 : Send a test transaction
Replace address with any address from explorer - https://octrascan.io/

python cli.py send --to octECeUEKyTeFMYBumubqnskCYo292L
