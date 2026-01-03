# Decentralized Exchange (AMM)

A simplified **Automated Market Maker (AMM) Decentralized Exchange** built using **Solidity** and **Hardhat**.  
This project implements the **Constant Product Formula (`x * y = k`)**, enabling permissionless token swaps and liquidity provision without relying on order books.

---

##  Features

- **Liquidity Provision**
  - Users can supply Token A and Token B to the pool
  - Liquidity providers receive LP tokens representing their share

- **Token Swapping**
  - Seamless swapping between Token A and Token B
  - Prices are determined algorithmically using reserve ratios

- **Trading Fees**
  - A **0.3% swap fee** is applied to every trade
  - Fees are distributed proportionally to liquidity providers

- **Slippage Protection**
  - Prices automatically adjust based on pool liquidity
  - Protects against large price manipulation

---

##  Technology Stack

- **Solidity** – Smart contract development  
- **Hardhat** – Development, testing, and deployment framework  
- **Ethers.js** – Contract interaction and testing  
- **Docker** – Containerized testing environment  

---

##  Prerequisites

Make sure you have the following installed:

- **Node.js** v18 or higher  
- **Docker** (optional, for containerized execution)

---

##  Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd dex-amm
