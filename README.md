# CLI Node Run Full Guide (PC and VPS for Both)
Nexus-Labs-Node-Run-Full-Guide
Introduction
Nexus Labs appears to be a multifaceted organization involved in various technological domains, particularly in blockchain, gaming, and smart buildings.

Overview
Blockchain and zkVM: Nexus Labs is developing the Nexus zkVM (Zero-Knowledge Virtual Machine) and aims to build a supercomputer network powered by blockchain technology. This includes creating an EVM-compatible blockchain that becomes more powerful as more nodes connect, focusing on verifiable computation.

Gaming Industry: They have a significant presence in the gaming sector, specifically with a project named "Resurgence." This is described as a free-to-play, massively multiplayer online role-playing game (MMORPG) set in a post-apocalyptic Earth scenario where players can have ownership and control over the game's universe through blockchain technology.

Smart Buildings: Nexus Labs also operates in the smart buildings technology space, providing education and community platforms. They focus on simplifying the marketplace for smart building technologies, offering insights, newsletters, and workshops aimed at building owners and tech vendors.

Education and Community: They offer educational content through newsletters and courses, like "Nexus Foundations," which introduce people to the smart buildings industry. They also organize events like NexusCon, aimed at educational advancement without the commercial fluff. Technological Partnerships: Nexus Labs has partnerships with various entities to enhance their capabilities, such as with Hyperbolic Labs for decentralized compute and verifiable AI infrastructure, GAIB for AI Finance, and others for exploring solutions in blockchain technology and smart buildings.

### Offical Docs - https://docs.nexus.xyz/layer-1/testnet-ii/cli-node

1️⃣ Dependencies for WINDOWS & LINUX
```
sudo apt update
sudo apt upgrade
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files

```
sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
rustup target add riscv32i-unknown-none-elf
```
```
source $HOME/.cargo/env
```
```
sudo apt install -y protobuf-compiler
```

3️⃣ Start Node
```
curl https://cli.nexus.xyz/ | sh
```

Then put Ur Node ID & Run it Continuesly

## How to get Node ID

- Click "Nodes" button
- Click "Add node" button
- Click "Add CLI node" button
- Then copy your Node ID & Paste in WSL


## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
curl https://cli.nexus.xyz/ | sh
```
I Node Run Full Guide (PC and VPS for Both)
