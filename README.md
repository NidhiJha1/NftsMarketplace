# NftsMarketplace

Technology Stack & Tools

Solidity (Writing Smart Contract) Javascript (React & Testing) Ethers (Blockchain Interaction) Hardhat (Development Framework) Ipfs (Metadata storage) React routers (Navigational components)

Requirements For Initial Setup Install NodeJS, should work with any node version below 16.5.0 Install Hardhat

Setting Up

Clone/Download the Repository

Install Dependencies: $ npm install

Boot up local development blockchain $ npx hardhat node

Connect development blockchain accounts to Metamask Copy private key of the addresses and import to Metamask Connect your metamask to hardhat blockchain, network 127.0.0.1:8545. If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.

Migrate Smart Contracts npx hardhat run src/backend/scripts/deploy.js --network localhost

Run Tests $ npx hardhat test

Launch Frontend $ npm run start
