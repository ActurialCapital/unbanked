<!-- PROJECT LOGO -->
# `Unbanked` from `Ternio`

<p align="center"><img src="docs/artist_sketch.jpg" alt="logo" width="90%" height="90%"></p>

<!-- ABOUT THE PROJECT -->
# Bankers Smart Contract

Welcome to the Bankers smart contract repository. 
This README provides a comprehensive overview of the Bankers collection, its utilities, and how to get started with the contract.

## Overview

### Bankers Collection

The Bankers collection comprises unique digital collectibles on the Ethereum blockchain that offer real utility and ownership benefits:

- **Increased Earnings**: Earn 20% more on Unbanked Yield.
- **Lending and Borrowing**: Enjoy free lending and borrowing services.
- **Creator Background**: Created by Antoine Mingo, the creator of Pudgy Penguins.
- **IP Rights**: Full ownership of your Banker IP rights.
- **Limited Edition**: Out of the 10,000 originally created, only 1,932 remain as the unsold Bankers were burned.

### Dutch Auction Contract

The Bankers contract operates as a Dutch auction. In a Dutch auction, the price of the token starts high and decreases over time until a buyer is willing to purchase at the current price. This mechanism ensures that tokens are sold at a fair market value based on demand.

## Unbanked Yield

### What is Yield Farming?

Yield farming involves utilizing digital assets to maximize returns. It typically entails locking up digital assets in various DeFi protocols to earn rewards. Yield farming, also known as liquidity mining, can involve moving assets across different pools to achieve the best annual percentage yield (APY).

### Unbanked Yield on Uniswap

Given the surge in Ethereum-based DeFi protocols, Unbanked Yield leverages Uniswap for yield farming. Uniswap offers a decentralized platform for automated liquidity provision for Ethereum token trading pairs.

### Tokenization with TERN

Ternio has introduced TERN tokens to Uniswap for liquidity pooling. As an ERC-20 token, TERN can be deposited into a smart contract to receive pool tokens, which represent the provider’s share of the liquidity pool. Uniswap charges a 0.30% fee on all trades, which is added to the reserve pool and distributed to liquidity providers when they reclaim their stakes by burning pool tokens.

## Getting Started

To interact with the Bankers NFT smart contract, follow these steps:

1. **View Accounts**:
    ```sh
    $ npx hardhat accounts
    ```

2. **Compile the Contract**:
    ```sh
    $ npx hardhat compile
    ```

3. **Clean the Cache**:
    ```sh
    $ npx hardhat clean
    ```

4. **Run Tests**:
    ```sh
    $ npx hardhat test
    ```

5. **Start a Local Node**:
    ```sh
    $ npx hardhat node
    ```

6. **Execute Sample Script**:
    ```sh
    $ node scripts/sample-script.js
    ```

7. **Get Help**:
    ```sh
    $ npx hardhat help
    ```

## License

This project is distributed under the BSD-3 License. See [LICENSE](LICENSE.txt) for more information.

## Etherscan

You can view the deployed contract on Etherscan: [Contract Address 0x95F36F45D93e5271612e4FD365fA9C2ac165a3fc](https://etherscan.io/address/0x95F36F45D93e5271612e4FD365fA9C2ac165a3fc).

For any additional questions or issues, feel free to open an issue on GitHub.

<p align="left">
    <a href="https://etherscan.io/address/0x95f36f45d93e5271612e4fd365fa9c2ac165a3fc">
        <img src="docs/qr-code.png" alt="qr" width="20%" height="20%">
    </a>
</p>

