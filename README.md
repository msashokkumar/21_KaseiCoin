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

3. Remix, MetaMax and Ganache contract interactions are shown in the following demo:
![Kasei_Coin_Demo](./media/videos/01_Crowdsale_Demo.mov)

4. Transactions showing up in Ganche.
![Transactions](./media/images/03_Ganache_Transactions.png)

5. Account_3 Balance.
![Account_3_Balance](./media/images/04_Account3_Account_Balance.png)

6. Account_4 Balance.
![Account_4_Balance](./media/images/05_Account4_Account_Balance.png)

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