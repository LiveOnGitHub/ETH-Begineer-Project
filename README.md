# MyToken Solidity Contract (Mint and Burn)

This Solidity contract implements a basic  token named "HARSH" (abbrv. "HRH") with minting and burning functionalities. The contract serves as a foundation for understanding token creation and management on the Ethereum blockchain.

## Description

This contract defines a simple token named "HARSH" with the token abbreviation "HRH". The contract features functions to mint and burn tokens, effectively managing the total supply and individual token balances.

The `mint` function allows the contract owner to increase the total supply and allocate tokens to a specified address. On the other hand, the `burn` function enables the contract owner to decrease the total supply and deduct tokens from a given address. Proper checks are in place to ensure that token balances are sufficient for burning.

## Usage

### Prerequisites

- You need an Ethereum development environment or an online Solidity IDE such as Remix.
- Basic knowledge of Solidity and Ethereum smart contracts is recommended.

### Deployment and Interaction

1. Deploy the Contract:
   - Deploy the contract by copying and pasting the provided code into a Solidity file (e.g., `MyToken.sol`).
   - Compile the contract using the desired version of the Solidity compiler (e.g., `0.8.18`).

2. Minting:
   - Call the `mint` function, providing an address and an amount as parameters.
   - This will increase the total supply and allocate tokens to the specified address.

3. Burning:
   - Call the `burn` function, providing an address and an amount as parameters.
   - The function checks if the address has a sufficient balance before decreasing the total supply and deducting tokens from the address.

### Example Usage (Remix)

1. Deploy the contract on Remix using the appropriate Solidity version.

2. Interact with the contract:
   - Mint tokens using the `mint` function, specifying an address and an amount.
   - Burn tokens using the `burn` function, providing an address and an amount to burn.

3. Ensure proper token management and balance checks are performed.

## Authors

Harsh Saini
22BCT10007@cuchd.in

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
