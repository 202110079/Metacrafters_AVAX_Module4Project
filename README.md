# Metacrafters Avalanche Module 4 Project
This is a submission for the Metacrafters Avalanche Module 4 Project involving creating a custom token that can burn, mint, and transfer tokens between addresses.

## Minting
Only the owner address can mint tokens. If another address attempts to mint, they will not be allowed to. 
The mint function provides an address with a certain amount of tokens, and adds those tokens to the total supply.

## Burning
Any address can burn their own tokens.
The burn function takes in the number of tokens and removes it from both the address's balance, and from the totalSupply of the entire token.

## Transfer
Any address can transfer their tokens to whoever.
The transfer function allows any address to give their tokens to another address. This reduces that number of tokens from their balance, and gives it to the other address without reducing the total supply of the entire token.
