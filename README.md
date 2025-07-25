# netrum-lite-node
**Hardware Requirements:
 RAM: 4-6 GB
 CPU: 2vCPU
 Storage: 100GB SSD
 Network: 10Mbps Internet Connection
and 
Node Requirements:
 You need 0.0004 Base ETH for Node registration Fee
 Wallet address has a registered Base domain name (Mint [here](https://www.base.org/names) if you don't have one)*

```bash
git clone https://github.com/NetrumLabs/netrum-lite-node.git
cd netrum-lite-node
```
```bash
sudo apt update && sudo apt install -y curl bc jq speedtest-cli nodejs npm
```
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
node -v
```
```bash
npm install
sudo npm link
netrum
```
```sql Netrum CLI  Version v1.0.0
Light-weight node & wallet toolkit for the Netrum network.

Available Commands:
netrum-system          System status & logs
netrum-new-wallet      Create / new a wallet
netrum-import-wallet   Create / import a wallet
...
```

```bash
netrum-new-wallet
```
#or
```bash
netrum-import-wallet
```
check the domain
```bash
netrum-check-basename
```
```bash
netrum-node-id
```
```bash
netrum-node-sign
```
```bash
netrum-node-register
```
```bash
netrum-sync
```
```bash
netrum-sync-log
```
```bash
sudo cp /root/netrum-lite-node/netrum-node.service /etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable netrum-node.service
sudo systemctl start netrum-node.service
sudo systemctl status netrum-node.service
```

```bash
netrum-mining
```
```bash
netrum-mining-log
```
after 24 H
```bash
netrum-claim
```
chek wallet
```bash
netrum-wallet
```
join here https://discord.gg/TvztxbBq
and register your node id <img width="855" height="376" alt="image" src="https://github.com/user-attachments/assets/9689ceaf-1e18-447e-9a5b-fdc986799d92" />
