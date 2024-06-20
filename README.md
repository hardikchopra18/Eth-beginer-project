# ETH Beginner Project

Welcome to the ETH Beginner Project! This project involves minting our own tokens and managing their supply through smart contract functions. Below is a detailed explanation of the project's structure and functionality.

## Project Overview

This project demonstrates how to create and manage a simple token on the Ethereum blockchain. We have implemented basic functionalities including minting new tokens and burning existing ones. The following sections describe the key components and functions within our smart contract.

## Public Variables

The smart contract contains several public variables to store important information about our token:

- `name`: The name of the token.
- `symbol`: The symbol representing the token.
- `initialSupply`: The initial supply of tokens, which is set to zero at the beginning.

## Functions

### Mint Function

The `mint` function allows the creation of new tokens. When this function is called, it generates a specified number of tokens and assigns them to a given address. This also increases the total supply of the tokens.

### Burn Function

In contrast to the `mint` function, the `burn` function destroys a specified number of tokens from the total supply. This function decreases the total supply, effectively removing tokens from circulation.

## Usage

To use the smart contract, you need to deploy it on the Ethereum blockchain. Once deployed, we can interact with the contract through its public functions to mint or burn tokens.

## Conclusion

This ETH Beginner Project serves as an introduction to creating and managing tokens on the Ethereum blockchain. By understanding the mint and burn functions, we can control the supply of your custom tokens effectively.
