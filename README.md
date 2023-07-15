# Basic blockchain app
https://sandhu-sahil.github.io/Blockchain-Solidity-1st/

## working explanation

`mood.sol` is the smart contract that is deployed on the blockchain. It has a function `setMood` that sets the mood of the user and another function `getMood` that returns the mood of the user.

Deploy the smart contract on the blockchain using `Remix Compiler` by setting the environment to `Injected Provider - MetaMask`. This will deploy the smart contract on the blockchain and return the address of the smart contract.

Now, we need to connect the smart contract to the frontend. For this, we need to use the `web3.js` library. We need to install the `web3.js` library using `npm install web3` command.

And `index.js` inculde all the code to connect the smart contract to the frontend.