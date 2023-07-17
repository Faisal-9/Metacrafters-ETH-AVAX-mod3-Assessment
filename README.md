# Mwtacrafters-ETH-AVAX-mod3-Assessment

# MyToken

MyToken is a basic ERC20 token contract written in Solidity. It allows the owner to mint new tokens and users to burn their own tokens.

## Contract Details

- Name: Ahmad
- Symbol: ETH
- Total Supply: 0

## Functions

### mint(address _to, uint _amount)

This function allows the owner of the contract to mint new tokens and assign them to a specific address. Only the owner can call this function. The total supply and the balance of the recipient address will be increased by the specified amount.

### burn(uint _amount)

This function allows users to burn their own tokens. The user must have a sufficient balance to burn the specified amount. The total supply and the balance of the user will be decreased by the burned amount. This function also emits a Burn event with the address of the user and the burned amount.

## License

This contract is licensed under the MIT License.
