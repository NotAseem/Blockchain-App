# Decentralized Voting DApp

This is a decentralized voting application built on the Ethereum blockchain. The DApp allows users to vote on various proposals securely and transparently using smart contracts, ensuring that all votes are stored immutably on the blockchain. The application is developed with Solidity, Hardhat, JavaScript, and CSS, and integrates Metamask for blockchain interaction.

## Technologies Used

- Ethereum Blockchain: The decentralized platform where smart contracts are deployed.
- EnergyWeb: Blockchain framework for energy-related use cases.
- Metamask: Ethereum wallet to interact with the DApp from the browser.
- Volta Testnet: Energy Web's test network for testing and development.
- Hardhat: Development environment to compile, deploy, test, and debug Solidity smart contracts.
- Solidity: Programming language used to write smart contracts.
- JavaScript: Used to handle the front-end logic.
- CSS: For styling the application.

## Prerequisites

Make sure you have the following installed before getting started:

- [Node.js](https://nodejs.org/en/)
- [Metamask](https://metamask.io/) browser extension
- [Hardhat](https://hardhat.org/)

## Project Setup

1. Clone the repository:

    git clone https://github.com/NotAseem/Blockchain-App.git

2. Navigate to the project directory:

    cd Blockchain-App
    
3. Install the dependencies:

    npm install

4. Compile the Solidity smart contracts using Hardhat:

    npx hardhat compile

5. Deploy the smart contracts to your local blockchain or a test network:

    npx hardhat run volta --network scripts/deploy.js

6. Run the local development server:

    npm start

## Note 1: 
  To initialize the Node.js project, use 'npm init' which creates a 'package.json' file where you can define the dependencies.
  Now, install the dependencies using 'npm install'.

## Note 2:
  It is better to maintain two separate folders for handling the backend i.e., hardhat-contracts side and a different one for frontend which has required     
  App.js file where several functions are defined to handle the frontend. 
