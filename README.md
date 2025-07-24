# 🐶 ShibaToken — Meme Token Smart Contract (Alephium)

This repository contains a custom fungible token smart contract written in [Ralph](https://docs.alephium.org/ralph/overview/), the official smart contract language for the [Alephium Blockchain](https://alephium.org/).

## 💡 What It Does

ShibaToken is a meme-inspired fungible token with the following features:

- 🟢 **Total Supply:** 1,000,000,000 SHIBA
- 🔒 **Locked Forever:** 30% (300 million) permanently locked at deployment
- 💰 **Circulating Supply:** 70% (700 million) assigned to the deployer
- 🔐 **No Minting, No Burning, No Backdoor**

This structure promotes trust and transparency for investors by ensuring that a significant portion of the supply is provably inaccessible.

---

## 🔧 How It Works

- Implements Alephium's `IFungibleToken` standard.
- `transfer` function allows the deployer to send from the unlocked balance.
- Locked supply is hardcoded and unreachable, ensuring integrity.
- Fully open to audit and testnet deployment.

---

## 📁 File Structure
