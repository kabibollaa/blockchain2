# My Web3 Project

## Usage

This project demonstrates the interaction with a smart contract on the Ethereum blockchain using web3.js. It includes functions to retrieve and display transaction information from an ERC-20 token contract.

## Demo Screenshots

Add any relevant screenshots or gifs that showcase the functionality of your project. This section is optional but can greatly enhance the README.

- **Screenshot 1:** Connecting to Ethereum Node
![2024-01-21_23-23-30](https://github.com/kabibollaa/blockchain2/assets/147371746/6381e0df-27e0-4f31-b071-bb63b8511f1e)


- **Screenshot 2:** Deploying to MetaMask using Remix IDE
  ![Снимок экрана 2024-01-17 182925](https://github.com/kabibollaa/blockchain2/assets/147371746/f8de7c47-5cd5-48a0-a702-dcef24f57f5c)




## Examples

Provide usage examples or code snippets to help users understand how to interact with your project.

```javascript
const web3 = new Web3('http://localhost:8545');
const contractAddress = '0xYourContractAddress';

// Example: Retrieve token balance
const balance = await contract.methods.balanceOf('0xRecipientAddress').call();
console.log('Token Balance:', balance);
