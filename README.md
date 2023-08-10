# Token Contract with Minting and Burning Functionality

## Introduction

This repository contains a basic Solidity smart contract that demonstrates how to implement token minting and burning functionalities. The contract is designed to help users understand the process of creating and destroying tokens, managing the total supply, and tracking individual balances.

## Description

The Token Contract with Minting and Burning is a simple Solidity smart contract showcasing minting and burning capabilities. It includes public variables for storing token information like name, abbreviation, and total supply. The contract also employs a mapping structure to keep track of token balances associated with different addresses.

The contract features a function named `mint` for token creation. By invoking this function with the recipient's address and the number of tokens to mint, the total supply increases, and the recipient's balance is updated accordingly.

Similarly, the contract provides a `burn` function for token destruction. Calling this function with the address to burn tokens from and the quantity to burn results in a reduction of the total supply and the sender's balance. The function incorporates a conditional check to ensure the sender's balance is sufficient, preventing excessive burning.

## Getting Started

### Prerequisites

To interact with the token contract, you will need:

- A development environment with Solidity support (e.g., Remix).
- An Ethereum address to deploy and interact with the contract.

### Installation

Open the `MyToken.sol` contract file in your chosen Solidity development environment.

### Performing Transactions

1. Utilize your preferred Ethereum wallet or development tool to interact with the deployed contract.

2. To mint tokens, call the `mint` function. Provide the recipient's address (`_address`) and the number of tokens to mint (`_value`).

3. For burning tokens, execute the `burn` function. Specify the address from which to burn tokens (`_address`) and the quantity of tokens to burn (`_value`).

## Assistance

If you run into any issues or have inquiries regarding the token contract, please feel free to create an issue on this repository's GitHub page.

## Authors

- Harsh Saini

## License

This project is licensed under the MIT License.
