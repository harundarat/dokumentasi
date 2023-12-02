# EcoSaver

This website allows users to create crowdfunding campaign and collect funds from donors. The collected funds will be stored in an Ethereum smart contract and will be distributed to the project after get approved by admin.

## 🚀 Demo

[https://ecosaver.netlify.app/](https://ecosaver.netlify.app/)

## 🧐 Features

Here're some of the project's best features: 
* Create crowdfunding campaign and collect funds from donors. 
* Campaign approval and funds release by admin. 
* Platform fee: 5%. 
* Rewards for donors.

## 🛠️Development Steps

> [!NOTE]
> _EcoSaver development requires currently maintained [Node.js](https://nodejs.org/en) LTS version._

### Setup/Installation:

1. Run each of the following commands in the project's root directory:  
``` bash
cd app && npm install
```  
``` bash
cd contract && npm install
```  

### Testing:
1. From project's root directory, go to contract directory:  
``` bash
cd contract
```  
2. Run Hardhat test command. This will run `test/test.js`:  
``` bash
npx hardhat test
```  
3. Make sure all tests are checked:  
![Alt text](https://bafkreic2ckiiyrbcuw7h7djs4wry3wmxeyaq5ofp26jvyr5vuo6tja7uza.ipfs.nftstorage.link/)

### Deployment
1. From project's root directory, go to contract directory:  
``` bash
cd contract
```
2. Run this command in terminal:
``` bash
npx thirdweb@latest deploy
```
3. Select all contract using `Space`, then `Enter`:  
![Alt text](https://coral-mad-vole-745.mypinata.cloud/ipfs/QmW2ppJWJWurNpiMjP88UMtt8PkbriChkhcE5JG1E3MGej)  
4. You'll redirected to thirdweb deploy contracts page. Choose one of them. Later, you'll need to repeat this step for other contracts:  
![Alt text](https://coral-mad-vole-745.mypinata.cloud/ipfs/QmUyEdFNjEK8PUntkjDttQe2cHHNCNAcB3Xu1ZgSAZTLzz)  
5. Choose network, then deploy:  
![Alt text](https://coral-mad-vole-745.mypinata.cloud/ipfs/QmNvMDRcmF6xKrwFpiDfkQRKiuSNdLZ9j1GGJjhgSG89TR)  
6. Repeat from step 4 until all contracts are deployed.

### Contract Address  
Here are the addresses of our deployed contracts:  
1. **Crowdfunding** :
2. **Admin** :
3. **Reward** :
4. **EcoSaverNFT** :  

## 💻 Built with

Technologies used in the project: 
* [Solidity](https://soliditylang.org/) - Object-oriented programming language for implementing smart contracts.
* [Hardhat](https://hardhat.org/) - Ethereum development environment for professionals.
* [OpenZeppelin Contracts](https://www.openzeppelin.com/contracts) - Open-source library for building secure smart contracts.
* [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling.
* [Node.js](https://nodejs.org/en) - open-source, cross-platform JavaScript runtime environment.
* [thirdweb](https://thirdweb.com/) - The complete web3 development toolkit.


## 🛡️ License:

This project is licensed under the MIT.
