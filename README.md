# Martian Token Crowdsale

Create a fungible token that is ERC-20 compliant and that will be minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The crowdsale contract that we create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. The contract will mint the tokens automatically and distribute them to buyers in one transaction.

---
### Language

| Component | Version |
|-----------|---------|
| Solidity  | 0.5.0   |
| Remix     | 0.23.3  |
| Ganache   | 2.5.4   |
| Metamask  | 10.14.0 |

---
### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Remix web browser with Solidity 0.5.0

### Running the Crowdsale App

1. Compile `KaseiCoin.sol` and `KaseiCoinCrowdsale.sol` from Remix IDE.
![Kasei_Coin_Compiled](./media/images/01_KaseiCoin_Compiled.png)

2. Deploy the `KaseiCoinCrowdsale` from RemixIDE.
![Kasei_Coin_Crowdsale_Compiled](./media/images/02_KaseiCoin_Crowdsale_Compiled.png)

3. Create a new Ganache workspace for the project.
![Ganache_Workspace](./media/images/03_Ganache_Workspace.png)

4. Add a new network to Metamask.
![Add_Metamask_Network](./media/images/04_Metamask_Add_Network.png)

5. Connect Remix with Metamask and Ganache.
![Remix_Metamask_Ganache](./media/images/05_Connect_Remix_Metamask.png)

6. Deploy the contract.
![Deploy_Contract](./media/images/06_Deploy_Contract.png)

7. View the deployed Contract.
![Kasei_Coin_Crowdsale_Compiled](./media/images/07_Deployed_Contract.png)

8. View the transaction in Ganache.
![Blocks_Transactions](./media/images/08_Blocks_Transactions.png)

9. Verify accounts to view the transferred Kasei coins.
![Account_Balance](./media/images/09_Account_Showing_Deployed_KC.png)

10. Detailed demo is available in the following video:
![Kasei_Coin_Demo](./media/videos/01_Crowdsale_Demo_480p.gif)

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.