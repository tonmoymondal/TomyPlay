# TomyPlay

# Introduction 
This repository contains the solidity smart contract for the Degen Token, an ERC20 Token designed for gaming purposes on the Avalanche Fuji Test network. 
This contract provides teh functionality for minting new tokens, transferring tokens, approve, and redeeming the tokens for in-game items, checking the token balances, and burining the tokens.

# Contract Details
- Token Name: Degen Token
- Symbol: DGN
- Decimals: 18
- Totalsupply
- Owner's address

  # Events performed
  1. Minting new Tokens: It allows the owner to create new tokens.
  2. Burning Tokens: This function allows to burn the specific amount of their own tokens.
  3. Approval: It enables the token holder to grant permission to another address to spend a specific amount of their tokens.
  4. Transferring Tokens: It allows the token holder to send the tokens to another address.
  5. TransferFrom: Allows an approved address to transfer tokens from the sender's address to the recipient address.
  6. Redeemption: It allows the token holder to redeem items using their own tokens.
 
  # Implementation
  The contract can be deployed on the Avalanche Fuji Test network for the Degen Gaming
  - Steps to follow:
    1. First write the contract on the remix.
    2. Add the Avalanche Fuji Network on your Metamask.
    3. Request for the AVAX on https://core.app/en/tools/testnet-faucet/
    4. Make sure that the required avax is present in your account.
    5. When the metamask has enough avax then select the environment as "Injected Provider" in remix.
    6. And last deploy the contract in the selected environment.
    7. Perform the Transactions.
    8. To verify copy the address of deployment and paste it into "Snowtrace Fauji Testnet".
   
    ![image](https://github.com/user-attachments/assets/ffb1e58f-d44f-477f-9843-ec716b26cb07)
