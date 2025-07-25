## 📦 Hardware Requirements
 RAM: 4-6 GB
 CPU: 2vCPU
Storage: 100 GB SSD
Network: 10 Mbps Internet Connection

# Join waitlist:
[HERE](https://netrumlabs.com/Waitlist?ref=0x05A7Eb929209F5C1F2f08dd087b64bB1beBa99fE)
## 🔐 Node Requirements
You need 0.0004 Base ETH for node registration fee
Wallet address must have a registered Base domain name:
 Base domain name
 
 (Mint [here](https://www.base.org/names) if you don't have one)*

## 1. Clone the repo
```bashgit clone https://github.com/NetrumLabs/netrum-lite-node.git
cd netrum-lite-node
```
## 2. Install dependencies
```bash
sudo apt update && sudo apt install -y curl bc jq speedtest-cli
```
## 3. Install Node.js (v20)
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs npm
node -v
```
## 4. Install Netrum CLI
```bash
npm install
sudo npm link
netrum
```
## Sample CLI Output (for reference):
<pre>
# Netrum CLI  Version v1.0.0
# Light-weight node & wallet toolkit for the Netrum network.
# Commands:
# netrum-system          System status & logs
# netrum-new-wallet      Create / new a wallet
# netrum-import-wallet   Create / import a wallet
# netrum-wallet          Create / inspect a wallet
# netrum-wallet-key      Export private key
# netrum-wallet-remove   Delete wallet files
# netrum-check-basename  Check basename conflicts
# netrum-node-id         Show current Node ID
# netrum-node-id-remove  Clear Node ID
# netrum-node-sign       Sign a message with node key
# netrum-node-register   Register node on-chain
# netrum-sync            Sync blockchain data
# netrum-sync-log        Node sync logs
# netrum-mining          Start mining
# netrum-mining-log      Node mining logs
# netrum-claim           Claim rewards
</pre>
## 5. Wallet setup
```bash
netrum-new-wallet
```
## OR if you already have a wallet:
```bash
netrum-import-wallet
```
## 6. Check Base domain
```bash
netrum-check-basename
```
## 7. Node registration
```bash
netrum-node-id
netrum-node-sign
netrum-node-register
```
#If you see errors check it with : `netrum-system`
## 8. Start syncing
```bash
netrum-sync
netrum-sync-log
```
## 9. Enable as systemd service
```bash
sudo systemctl daemon-reload
sudo systemctl enable netrum-node.service
sudo systemctl start netrum-node.service
sudo systemctl status netrum-node.service
```
## 10. Start mining
```bash
netrum-mining
netrum-mining-log
```
## 11. After 24 hours, claim rewards
```bash
netrum-claim
```
## 12. Check wallet
```bash
netrum-wallet
```
## 13. Join Discord and register your Node ID:
## https://discord.gg/TvztxbBq
## Use the /register command with your Node ID inside the server
<img width="855" height="376" alt="image" src="https://github.com/user-attachments/assets/9689ceaf-1e18-447e-9a5b-fdc986799d92" />
