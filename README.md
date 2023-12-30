# calculate income tax

This Solidity smart contract, named **IncomeTaxContract**, is designed to calculate income tax based on the income provided. It has been developed on the Ethereum blockchain using the Solidity programming language. Below is a brief explanation of the key features and usage of the contract.

## Smart Contract Details

### SPDX-License-Identifier

The contract is licensed under the MIT License, which allows for free use, modification, and distribution of the code. Please refer to the SPDX-License-Identifier for more details.

### Solidity Version

The contract is implemented using Solidity version 0.8.0. It is important to use the specified version or later to ensure compatibility.

## Contract Overview

The smart contract includes the following:

- **Owner:** The contract has an 'owner' variable, initialized with the address of the deployer of the contract.

- **Constructor:** The constructor sets the deployer's address as the owner.

- **calculateTaxupto12lakh:** This function calculates income tax based on the provided income. It includes different tax slabs and rates as follows:
  - 5% tax for income up to 6 lakh
  - 10% tax for income between 6 lakh and 9 lakh
  - 15% tax for income between 9 lakh and 12 lakh
  - Reverts if the income exceeds 12 lakh
  - Only the owner can invoke this function

## Usage

1. Deploy the contract to the Ethereum blockchain.

2. Set the income tax calculation by calling the `calculateTaxupto12lakh` function with the desired income value.

3. Only the owner can invoke the tax calculation function.

##  Author 
Mourya 
mourya7795@gmail.com




