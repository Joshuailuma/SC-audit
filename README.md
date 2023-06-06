# SC-audit

This project demonstrates auditing of smart contracts using tools like Slither.
the smart contract basically store a user's address and an amount in form of an unsigned integer/uint

## Requirement
- Follow this guide to install Slither https://github.com/crytic/slither#how-to-install

- run slither storage.sol
## Result
After running slither on this project it was found that
- the function 'store' is not in mixed case
- the state vairable 'owner' should be made immutable

## Fixes
- fixed the function name to 'storeNumber'. 
- made the state variable 'owner' immutable. `address immutable owner`

## Author 
*Joshua Iluma
