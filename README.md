# NFTs with Metadata, dNFTs

Completed as part of Alchemy's ["Road to Web3"](https://www.youtube.com/playlist?list=PLMj8NvODurfEYLsuiClgikZBGDfhwdcXF)

This was week 3, and the tutorial has users create a dynamic NFTs with on-chain metadata. A primitive that can be used to build an on chain NFT gaming dApp.

Tutorial found here [How to make NFTs with On-Chain Metadata - Hardhat and JavaScript](https://www.youtube.com/watch?v=8FJvY4zXvPE&list=PLMj8NvODurfEYLsuiClgikZBGDfhwdcXF&index=3)

## Overview Info
Chain: Polygon

Network: Mumbai

Languages: Solidity, JavaScript

Deployed to Mumbai at: 0xdE844613ecD39b611c785b5019C41DA4aF9D05e6

Mumbai Contract Link on Mumbai Polygonscan: https://mumbai.polygonscan.com/address/0xdE844613ecD39b611c785b5019C41DA4aF9D05e6

## This tutorial covers:
- Coding an on chain, dynamic NFT
- Getting Matic Tokens, connecting to Mumbai Test Net
- Using Hardhat

## Technology/Websites used:
- [Alchemy](https://www.alchemy.com/)
- [Polygon](https://polygon.technology/)
- [Mumbai Test Net](https://docs.polygon.technology/docs/develop/network-details/network/)
- [Hardhat](https://hardhat.org/)

## To Get Started
1. Clone Repo
   ```sh
   git clone https://github.com/MSBivens/road-to-web3-week3-nfts-with-onchain-metadata
   ```
2. Create package.json
   ```sh
   npm init -y
   ```
3. Install HardHat
   ```sh
   npm add hardhat
   ```
4. Initialize simple project
   ```sh
   npx hardhat
   ```
5. Install additional dependencies if needed using:
   ```sh
   npm install --save-dev hardhat@^2.9.3 @nomiclabs/hardhat-waffle@^2.0.0 ethereum-waffle@^3.0.0 chai@^4.2.0 @nomiclabs/hardhat-ethers@^2.0.0 ethers@^5.0.0
   ```
6. Add Open Zepplin contracts, JardHat Etherscan Package, dotenv packge
   ```sh
   npm add @openzeppelin/contracts @nomiclabs/hardhat-etherscan dotenv
   ```