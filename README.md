# Web3.js-Ethereum-Interaction-Example-
Web3.js Ethereum Interaction Example:
const Web3 = require('web3');
const web3 = new Web3('https://mainnet.infura.io/v3/YOUR_INFURA_API_KEY');

// Example: Getting the balance of an Ethereum address
const address = '0x742d35Cc6634C0532925a3b844Bc454e4438f44e';
web3.eth.getBalance(address).then(console.log);
