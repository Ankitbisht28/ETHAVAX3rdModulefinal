# ETHAVAX3rdModulefinal
Token Creation on Local Hardhat Network:-

This project demonstrates the creation of a custom token on a local Hardhat network using a Solidity smart contract. The contract allows the contract owner to mint tokens to a provided address, and any user to burn and transfer tokens.

Getting Started:-

These instructions will help you set up and deploy the token contract on a local Hardhat network, and interact with it using Remix.

Prerequisites:-

Node.js (>=12.0.0)
npm or yarn

Installation:-

1.Clone this repository or download the project files.
2.Open a terminal and navigate to the project directory.
3.Install the project dependencies:
npm install

Deployment:-
1.Compile the contract using :npx hardhat compile
2.Deploy the contract to a local Hardhat network:npx hardhat node
3.In a separate terminal window, run the deployment script:npx hardhat run deploy.js --network hardhat

Interacting with the Contract:-
Open Remix in your browser.

In the "File Explorers" section, click the "+" button to create a new Solidity file.

Copy and paste the contract code into the new file.

In the Remix "Compile" tab, compile the contract.

Switch to the "Deploy & Run Transactions" tab.

Select "Injected Web3" as the environment.

Click the "Deploy" button.

Enter the contract's address (obtained from the deployment step) and provide the contract ABI in the contract field.

Click the "At Address" button. Remix will load the deployed contract.

Expand the contract in the "Deployed Contracts" section to access its functions.

As the contract owner, use the mint function to mint tokens to a provided address.

Any user can use the burn and transfer functions to burn and transfer tokens, respectively.

Example Usage:-

Here's an example of how you can interact with the contract using Remix:

Deploy the contract as described in the "Interacting with the Contract" section.

Locate the mint function in the contract interface and provide an address and an amount of tokens to mint.

Click the "transact" button. MetaMask will prompt you to confirm the transaction.

After the transaction is confirmed, the specified address will receive the minted tokens.

Use the burn function to burn a specific amount of tokens.

Use the transfer function to transfer tokens to another address.

Troubleshooting:-

If you encounter any issues during deployment or interaction, make sure you have a local Hardhat network running and are connected to it using MetaMask.

Double-check the contract address and ABI when interacting with the contract in Remix.

License:-
This project is licensed under the MIT License.
