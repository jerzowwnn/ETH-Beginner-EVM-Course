# ETH-Beginner-EVM-Course

# Introduction

This repository contains my files for the ETH PROOF: Beginner EVM Course. The file is named createToken.sol. The code is primarily purposed to create a contract and is developed using the Remix IDE.

# Pre-requisites
To ensure sound understanding and proper execution of the code, it is recommended to run the code with the following:
- Remix IDE
- Solidity Compiler

# Program Details
The file, createToken.sol, is a program thatg creates a contract which have public variables tokenName, tokenAbbrv, andf totalSupply. All variables arefor storing information about the created coin. It also has a mapping of addresses to balances. The program also has two functions: mint() and burn(). Both functions take two parameters, the address and value, and performs the following:

- mint(address, value) = Adds the value parameter to the totalSupply and balance of the address.
- burn(address, value) = Deducts the value to the totalSuply and balance of the address. Balance should always be greater than or equal to the value burned.  
