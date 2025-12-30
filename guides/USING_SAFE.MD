# 🔐 Safe (Multisig Wallet) Guide

[Safe](https://safe.global) (formerly Gnosis Safe) is the industry standard for securing digital assets on EVM chains. It is a **Smart Contract Wallet** that requires multiple signatures to execute transactions.

## 🛡️ Why use Safe?

1.  **Multi-Signature Security**: Require 2-of-3, 3-of-5, or any combination of owners to sign before any funds can move.
2.  **No Single Point of Failure**: If one owner loses their private key, the remaining owners can still access the funds and replace the lost key.
3.  **Global Coordination**: Work with people anywhere in the world. Safe allows teams to co-manage assets without needing a traditional bank or a shared legal jurisdiction.
4.  **Advanced Features**: Gasless signatures (off-chain), transaction batching, and integration with many DeFi apps.
5.  **Team Management**: Perfect for DAOs, teams, or even individuals wanting extra security for their long-term holdings.

---

## 🌍 Global Coordination & DAOs

In the context of space missions and lunar base development, coordination is often global. Safe acts as the **trustless infrastructure** for these collaborations:

- **Borderless Treasury**: A team in Japan, a developer in Brazil, and an engineer in Norway can co-manage project funds instantly.
- **Programmatic Trust**: You don't need to trust a single "treasurer." The code (the Smart Contract) ensures that funds only move when the agreed-upon number of partners sign.
- **Transparency**: Every signature and transaction is recorded on the blockchain, allowing anyone to verify how funds are being managed.
- **DAO Ready**: Safe is the foundation for most Decentralized Autonomous Organizations (DAOs). It allows for complex governance where token holders or a committee can control the "keys" to the mission's resources.

---

## 🚀 Getting Started

### 1. Create a Safe
1.  Go to [app.safe.global](https://app.safe.global).
2.  Connect your individual wallet (e.g., Rabby or MetaMask).
3.  Click **"Create New Safe"**.
4.  **Name your Safe**: This is just for your local display.
5.  **Select Network**: Choose the chain you want to use (Base, Polygon, Ethereum, etc.).
6.  **Add Owners**: Add the wallet addresses of the people who should co-own the Safe.
7.  **Set Threshold**: Choose how many signatures are required (e.g., 2 out of 3).

### 2. Funding the Safe
Your Safe has its own Ethereum-style address (`0x...`). You can send tokens or NFTs directly to this address.

### 3. Executing Transactions
1.  **Initiate**: One owner starts a transaction (e.g., a transfer or interaction with an app).
2.  **Sign**: Other owners see the "Pending" transaction in their Safe dashboard and must sign it.
3.  **Execute**: Once the threshold is met, any owner (or sometimes even a third party) can "Execute" the transaction, which submits it to the blockchain and pays the gas fee.

---

## 📲 Safe Apps & WalletConnect

You can use your Safe with almost any web3 application:
- **Safe Apps**: Built-in integrations like Uniswap, Aave, or CoW Swap that run directly inside the Safe interface.
- **WalletConnect**: Use the "WalletConnect" Safe App to connect your Safe to any external website. You'll sign in your individual wallet, but the transaction proposal will go to the Safe.

---

## ⚠️ Critical Security Reminders

- **Threshold is Key**: Never set a threshold of 1-of-1 for long-term storage; it defeats the purpose of a multisig.
- **Gas Fees**: While signing is often free (off-chain), the final execution requires gas on the network where the Safe lives.
- **Native Tokens**: Ensure the Safe always has a small amount of the native token (ETH, POL, etc.) to pay for transaction execution if you don't use a relay.

---

## 📚 Related Guides
- [🔷 EVM Wallets & Networks](WALLETS_EVM.MD)
- [💳 Crypto Wallets Quick Start](USING_WALLETS.MD)
