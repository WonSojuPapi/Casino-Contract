# Casino-Contract

This repository contains a Solidity smart contract named MyCasino. It implements basic deposit and withdrawal functionalities while showcasing the usage of `require()`, `assert()`, and `revert()` functions for input validation, internal consistency checks, and error handling.

## Features

- **Deposit Functionality**: Users can deposit funds into the smart contract by calling the `deposit` function. The function checks if the deposit value is greater than 100 using the `require()` function. If the condition is not met, it reverts with an error message.

- **Withdrawal Functionality**: Users can withdraw funds from the smart contract by calling the `withdraw` function. The function verifies if the user has sufficient balance using the `require()` function. If the balance is insufficient, it reverts with an error message. Additionally, the function ensures that the user's balance doesn't go below zero after withdrawal using the `assert()` function.

- **Error Handling**: The contract utilizes the `revert()` function to handle exceptional conditions. If the `assert()` statements fail, indicating internal errors, the contract reverts the transaction and provides an error message.

## Requirements

To interact with the MyCasino smart contract, you need:

- A development environment for Ethereum smart contracts, such as Remix or Truffle.
- An Ethereum account with some test Ether to perform transactions.
- Basic understanding of Solidity and Ethereum development.

## Usage

1. **Deploy Contract**: Deploy the `MyCasino.sol` contract to an Ethereum testnet or a local development environment.

2. **Interact with Functions**: Use a web3 provider or Ethereum development environment to interact with the contract's functions:
   - Deposit funds using the `deposit` function and Withdraw funds using the `withdraw` function.

3. **Handle Errors**: Ensure proper error handling in your application when interacting with the contract. Handle cases where transactions may revert due to input validation or internal errors.

## Author

Jakkin Elero
3.2 BSIT

## License
