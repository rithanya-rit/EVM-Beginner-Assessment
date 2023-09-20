# MyToken Solidity Smart Contract

This README provides an overview of the "MyToken" Solidity smart contract. The contract implements a basic token system with functionalities for minting and burning tokens.

## Token Details

- **Token Name:** Solana
- **Token Abbreviation:** SOL
- **Total Supply:** 0

## Contract Functions

### Mint Function

The `mint` function allows users to create new tokens by specifying an address and a value. It increases the total supply by the specified value and adds the same value to the balance of the sender's address.

### Burn Function

The `burn` function enables users to destroy tokens by specifying an address and a value. It decreases the total supply by the specified value and deducts the same value from the balance of the sender's address. Additionally, the function includes conditionals to ensure that the sender's balance is greater than or equal to the amount to be burned.

## Usage

1. Deploy this smart contract on a compatible blockchain network (e.g., Ethereum, Binance Smart Chain) using a Solidity-compatible development environment like Remix or Truffle.

2. Interact with the contract by calling the `mint` and `burn` functions, providing the necessary parameters as described above.

## License

This smart contract is provided under the MIT License.

## Author

Rithanya.R.K
