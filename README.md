# Project-Solidity (for my metaceafters assignment of Ethereum begineer cource)
Let’s Create a Token, Together!

# MyToken Solidity Contract

`MyToken` is a basic ERC20-like token with mint and burn functionalities.

## Features

- **Public Variables**: 
  - `tokenName`: "My Unique Token"
  - `tokenAbbr`: "MUT"
  - `totalSupply`: 0

- **Mapping**: `balances` tracks address balances.

- **Functions**:
  - `mint(address recipient, uint amount)`: Increases total supply and recipient's balance by `amount`.
  - `burn(address holder, uint amount)`: Decreases total supply and holder's balance by `amount`, requiring sufficient balance.

## Usage

### Deploy

1. Compile and deploy the contract using a Solidity compiler (e.g., Remix, Truffle).

### Interact

1. **Mint Tokens**: `mint(0xAddress, 100)`
2. **Burn Tokens**: `burn(0xAddress, 50)`

## License

MIT License.

## Contact

Email: akashlakhwan2329@gmail.com

