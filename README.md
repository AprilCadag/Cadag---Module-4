# Cadag--Module-3
The gimoGameToken contract is a Solidity smart contract designed to implement an ERC20 token for use within a gaming platform. It inherits functionality from the ERC20 contract provided by the OpenZeppelin library. The contract includes several key components to facilitate token management.

## Description
This Solidity contract, named gimoGameToken, is a simple example of an ERC20 token smart contract. It enables users to create a new token with a specified name, symbol, and total supply. The contract's admin, determined during deployment, possesses special privileges to generate (mint) additional tokens and allocate them to specific addresses using the generateTokens function. Users also have the ability to burn (destroy) their own tokens through the burnTokens function. Moreover, the contract facilitates token transfers between addresses via the transfer function, ensuring that the recipient address is valid. Additionally, it supports delegated transfers through the transferFrom function, allowing a spender to transfer tokens from the sender's account to another recipient. This contract serves as a foundational framework for managing ERC20 tokens on the Ethereum blockchain, demonstrating fundamental Solidity syntax and common patterns in a clear and concise manner.

## Getting Started
### Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

1. Open Remix IDE: Go to Remix IDE.
2. Create a New File: Create a new Solidity file (e.g., gimoGameToken.sol).
3. Copy and Paste the Contract Code: Paste the modified contract code into the file.
4. Compile the Contract: Click on the "Solidity Compiler" tab and compile the contract.
5. Deploy the Contract:
6. Go to the "Deploy & Run Transactions" tab.
7. Select the appropriate environment (e.g., JavaScript VM for local testing or Injected Web3 for MetaMask).
8. Enter the constructor parameters (tokenName, tokenSymbol, initialSupply).
9. Click "Deploy".

## Author
April Cadag

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
