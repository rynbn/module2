# Local Bank

> A Simple Web3 application for transferring Ether and personalizing your account. 

## Description 

This is a simple web3 application built with HTML, CSS, and Solidity. It uses the power of Ethereum networks to deliver a decentralized banking experience. This allows users to effortlessly deploy contracts, transfer Ether, and personalize their account names. The application is created with Solidity smart contracts, the sophisticated Ethers.js framework, and the easy-to-use MetaMask wallet extension.

## INSTALLATION

### Configure MetaMask to use the Hardhat node 

1. Open the MetaMask extension in your browser.
2. Click on the account icon in the top right corner and select "Settings".
3. In the "Networks" tab, click on "Add Network".
4. Fill in the following details:
   - Network Name: hardhat-test-network
   - RPC URL: http://127.0.0.1:8545/
   - Chain ID: 31337
   - Currency Symbol: GO or ETH
5. Click on "Save" to add the Hardhat network to MetaMask.

### Steps to run the project

1. Download or clone the project.
2. Install the dependencies by running `npm install`.
3. Start the local blockchain using Hardhat by running `npx hardhat node`.
4. Open new terminal and deploy the Bank contract `npx hardhat run --network localhost scripts/deploy.js`.
5. Start the development server by running `npm run dev`.


### Add accounts using private keys by Hardhat for testing 

1. In the MetaMask extension, click on the account icon in the top.
2. Select "Add Account", next is click "Import Account".
3. In the "Private Key" field, enter one of the private keys provided by Hardhat.
   - To access the list of private keys, open the terminal where you started the Hardhat local network.
   - The private keys are displayed as part of the accounts generated by Hardhat.
4. Click on "Import" to import the account into MetaMask.
5. Repeat the above steps to add more accounts for testing purposes.

## Step-by-step on how to use the web-page 

**To use the application, follow these instructions:**

1. After connecting MetaMask to the Hardhat local network, connect your wallet with the application
2. Click on Transfer Funds and fill in the recipient's address and the amount you want to transfer.
3. Click the "Transfer" button to initiate the transaction.
4. Confirm the transaction in MetaMask.
5. The transaction details will be logged to the console, and the account balance will be updated.

**Edit your account name:**

1. Click the "Change Account Name" button to set the new account name.
2. Enter a new name in the input field.
3. Confirm the transaction in MetaMask.
4. The account name will be updated, and the change will be reflected in the account details.


