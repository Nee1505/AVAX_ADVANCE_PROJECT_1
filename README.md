#  Creating a DeFi Kingdom Clone on Avalanche
In this Solidity program,  we create our own cutom subnet on avalancheand deploy foundational smart contracts to build a DeFi Kingdom clone. 

## Description

In this project, we first create our own custom subnet on avalanche and deploy it. In the custom subnet, we create our native currency which we can later use fore the transactions. Then we connect the subnet to the metamask.
After that we have two smart contracts- ERC20.sol and Vault.sol. These two contracts are the basic building blocks of our game. The ERC20 contract is used to add the functionalities of the ERC20 token. The Vault is used to define the game rules and functions like deposit tokens, withdraw tokens, redeemrewards, and functions for checking our account balance.

## Getting Started

## Executing program

To execute this project, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

1. Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with as ERC20.sol. Copy and paste the code given in this repository under the ERC20.sol file.
2. Then similarly, create another file in the same folder as Vault.sol. Then copy and paste  code given in the Vaault.sol file given in this repository.
3. set the environment in the remix ide to the injected provider(metamask), connect it to the custom EVM subnet we created before.
4. Deploy the ERC20 contract, then copy its contract address.
5. Then deploy the vault contract, while deploying it enter the address of ERC20 contract in the vault constructor.
6. Then mint some token in the ERC20 using the mint function.
7. After that approve the vault to spend tokens using the approve function in the ERC20 contract.

## Interact with the smart contract:

1. Deposit: Enter the amount you wish to deposit and click "Deposit".
2. Withdraw: Enter the amount of ETH you wish to withdraw and click "Withdraw ETH".
3. BalanceOf: Enter your account address and click on "BalanceOf" to check the balance of your account.
4. Rewards: Enter your account address and click on "Rewards" to check the rewards you have.
5. RedeemRewards: Click on "RedeemRewards" to redeem the rewards that you have.


## Authors

Neelam Rani
