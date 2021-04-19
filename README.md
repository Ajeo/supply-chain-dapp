# Supplay Chain DAPP

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## Deploy smart contract on a public test network

- Transaction ID: 0xae7a2d26ea20e8fa8c961e23916d71fe6bc298f7c42a8f48b235033e352e63d7
- Contract address ([Contract deployed in Rinkeby](https://rinkeby.etherscan.io/address/0xedab3d01c214b3925ac3df11ba76c8dea253ca3b))

## Ganache Setup

1. Install `npm install -g ganache-cli`

## Truffle Setup

1. Install `npm install truffle@4.1.17 -g`
1. Clone the repo
1. Go to the folder project-6
1. Run `truffle develop`
1. Migrate contracts `migrate --reset`
1. Run `test` inside the truffle console

## Frontend Setup

1. Go to the folder project-6
1. Install dependencies with `npm install`
1. Run local server `npm run dev`
1. Open `localhost:3000` in your browser

## Deploy in Rinkeby

1. Run `truffle migrate --reset --network rinkeby`
