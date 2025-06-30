#STEP BY STEP WALLET GENERATION GUIDE OF OCTRA { CODESPACE }
🔹 Step 1: Install Bun
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
🔹 Step 2: Install Dependencies
bun install
🔹 Step 3: Build the Project
bun run build
🔹 Step 4: Start the Server
bun start
✅ After this, click the “PORTS” tab in Codespace and open localhost:8888 in browser.

Done! Wallet Generator is live. 🔐

🪙 TASK 1 : TOKEN TRANSFER
🔹 STEP 1: Open in Codespace
Go to 👉 https://github.com/octra-labs/octra_pre_client
Click the green Code button
Select → Open with Codespaces → + New codespace
Wait for the environment to fully load
🔹 STEP 2: Install dependencies
In the Codespace terminal, run:

pip install -r requirements.txt
🔹 STEP 3: Create and edit wallet.json
Create the wallet file:

cp wallet.json.example wallet.json
Then open the file: wallet.json

Paste your test wallet details (⚠️ never use your real wallet): Wallet Generation

{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
🔹 STEP 4: Send a test transaction
python cli.py send --to oct5ziFzQJkiJFPfcQeuAmp4vhfQgjwb8gyx2W2TZdGhzJm --amount 0.01
🟢 That’s it! You can now access the wallet UI and make transactions to addresses found on the explorer: https://octrascan.io/

📢 JOIN TG FOR UPDATES: t.me/cryptodropscout octra-testnet
