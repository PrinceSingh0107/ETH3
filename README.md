# ETH3
# MyTokenProject

## Overview
This project demonstrates the creation, deployment, and interaction with an ERC20 token using the Solidity programming language and OpenZeppelin libraries. The smart contract is deployed using Remix IDE.

## Features
- **Minting Tokens**: The contract owner can mint new tokens to a specified address.
- **Burning Tokens**: Any user can burn their own tokens.
- **Transferring Tokens**: Users can transfer tokens to other addresses.

## Files
- `contracts/MyToken.sol`: The Solidity smart contract for the ERC20 token.

## Requirements
- Solidity version ^0.8.0
- OpenZeppelin Contracts

## Getting Started
1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new workspace or use the default workspace.
3. Create a new file named `MyToken.sol` in the `contracts` directory.
4. Copy and paste the code from `MyToken.sol` into the newly created file.
5. Compile the contract.
6. Deploy the contract using your preferred environment (Injected Web3 or Remix VM).

## Interacting with the Contract
1. **Mint Tokens**:
   - Call the `mint` function with the recipient address and amount of tokens.
   
2. **Burn Tokens**:
   - Call the `burn` function with the amount of tokens to burn.

3. **Transfer Tokens**:
   - Call the `transfer` function with the recipient address and amount of tokens.

## Example
### Minting Tokens
```solidity
mint("0xRecipientAddress", 1000);
