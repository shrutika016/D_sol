# D_sol
## Creating Tokens by Using Solidity language
This is Solidity smart contract . 

## DESCIRPTION
This Solidity smart contract contains  features to manage a custom token. It includes two public variables: one for the token's name and another for its abbreviation. The contract also has a variable that keeps track of the total token supply. To manage user balances, there is a mapping variable named "balances" that connects addresses with their corresponding token balances.
The contract provides two essential functions: "mint" and "burn." The "mint" function allows the contract owner to increase the balance of a specific address by a given amount of tokens. On the other hand, the "burn" function allows the contract owner to decrease the balance of a specified address by a certain number of tokens, but only if the address has a sufficient balance to accommodate the requested reduction. In essence, these functions enable the contract owner to create new tokens (mint) and destroy existing tokens (burn) for specific addresses in the system.

## Implementation Compiler 
Use remixIDE 

## EXECUTING THE PROGRAM
* Create a new folder from upper menu.
* If Remix is set to auto compile and run, the code will be automatically compiled and executed. 
* After compiling, deploy the contract to get the account address for next steps.
* To mint tokens, click on the "Mint" button, paste the account address, enter the desired token quantity (e.g., 1000), and click "Transact" to add tokens to the account.
* To check the balance, click on "Balances," paste the account address, and click "Call" to view the account balance.
* to check the totalsupply click on it.
* To burn tokens, click on "Burn", paste the account address, set the value to be burnt (e.g., 791), and click "Transact" to reduce tokens from the account.
* To check the balance again, press "Call" to obtain the latest balance (e.g., 1000-791 = 209 tokens).
* These are all the steps followed in the contract.

## AUTHORS
Shrutika Bhoyar

## License
This project is licensed under the [MIT] License - see the LICENSE.md file for details
