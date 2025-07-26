# Nfts
chapter 1
# Behind the scenes in minting NFTs

This is just a small project I worked on to understand how NFTs actually work behind the scenes. Nothing official mostly me playing with testnets, smart contracts, and connecting the frontend to MetaMask.

## What this does

The idea was to create a basic setup where someone could mint an NFT from a webpage. It’s all on testnet, with placeholder images and metadata stored on IPFS.

## What I used

- Solidity for the contract
- Hardhat for compiling and deploying
- Ethers.js to connect the wallet
- A basic HTML/CSS frontend
- IPFS for metadata

## How to run it

Clone the repo, install dependencies,compile the contract:

```bash
git clone https://github.com/yourusername/nft-minting-practice
cd nft-minting-practice
npm install
npx hardhat compile
