# WidePiper: Organization Overview

Welcome to the WidePiper organization repository! This repository hosts the various components of the WidePiper project, a blockchain-powered platform designed to facilitate the management of derivative assets and interaction with blockchain wallets and decentralized exchanges (DEX). Below you'll find an overview of the project's architecture, guidelines for contribution, and links to the specific repositories for each component.

## Project Structure

WidePiper consists of several interconnected systems, which can be broken down into the following core components:

### 1. Frontend

The frontend provides users with an intuitive interface for interacting with their wallets, viewing derivative assets, and managing transactions.

- **Key Features**: Portfolio management, user wallet interaction, transaction history display, and derivative management.

You can find more information and the codebase for the frontend here: [Frontend Repository](#).

### 2. Server (Backend)

The server is responsible for managing user data, connecting to the blockchain, handling requests from the frontend, and ensuring a smooth flow of operations for the derivative management mechanism.

- **Key Modules**: Wallet Management, Transaction Handling, Exchange Mechanism, Game Wallet Integration

For more information, please visit the backend repository: [Backend Repository](#).

### 3. Blockchain 

The blockchain layer is the core of the WidePiper ecosystem. It includes smart contracts for managing tokens, executing derivative transactions, managing liquidity, and interacting with decentralized exchanges.

- **Core Components**:
  - **Smart Contracts for Tokens**: Smart contracts for the Idea and Matter tokens, which are used for staking within the ecosystem.
  - **Smart Contract for Wallet Management**: A smart contract to manage user wallets within the application, enabling secure fund transfers and interaction with tokens.
  - **Derivative Management Contract**: A smart contract to facilitate the placing and execution of derivative transactions.

Access the blockchain code and resources here: [Blockchain Repository](https://github.com/RickCastle2018/wallets-manager).

## Math Analysis Documentation

Access the detailed mathematical analysis of the system here: [Math Analysis Document](../math.pdf). This document outlines key calculations, risk assessment metrics, and the mathematical models used in the WidePiper ecosystem.





## Technical Specification

WidePiper is a platform for managing derivatives with blockchain wallet integration and a decentralized exchange (DEX). 
The main goal of the project is to create an interface for managing derivatives, while also providing users with an 
easy and efficient way to interact with tokens through a blockchain wallet.

### Phase 1: Interface Development and Wallet Integration

#### 1. Derivatives Management Interface
- Develop an interface for managing derivatives that allows users to create, edit, and track their derivative positions.
- Ensure a user-friendly UX/UI design to enhance interaction with the system.
- Support basic functionality, such as placing bets, tracking results, and accessing historical data.

#### 2. Blockchain Wallet Integration
- Connect a blockchain wallet to allow users to store and manage their assets.
- Implement functionality for token deposits and withdrawals through the integrated wallet.

#### 3. Blockchain Interaction
- Enable sending and receiving transactions via the blockchain wallet.
- Support integration with popular blockchain networks (e.g., TON, Ethereum).

### Phase 2: Integration with Decentralized Exchange (DEX)

#### 1. DEX Integration
- Develop a smart contract for interacting with the decentralized exchange.
- Enable token exchange via the DEX with minimal latency and maximum security.

#### 2. Betting Mechanism
- Implement a betting mechanism on token price changes with flexible parameter configurations.
- Define winnings and support bets on token price fluctuations with both current and historical price data.

##### Reward Calculation Model
The user's reward depends on the accuracy of their prediction and the amount of invested funds.

Formula for reward calculation:

![Formula](https://quicklatex.com/cache3/d7/ql_80683f28b7ce1d14a3baa7ecf36d0ad7_l3.png)

Where:
- ![Formula](https://quicklatex.com/cache3/dd/ql_c263f2c31f052e3832bf8ad77dc50cdd_l3.png): Reward for user ![Formula](https://quicklatex.com/cache3/0b/ql_ebc3da03e5724ce1a1cf155b4d43c70b_l3.png)
- ![Formula](https://quicklatex.com/cache3/3d/ql_e2d3a0ae6679d70dfd24ebd46868693d_l3.png): Funds invested by user ![Formula](https://quicklatex.com/cache3/0b/ql_ebc3da03e5724ce1a1cf155b4d43c70b_l3.png)
- ![Formula](https://quicklatex.com/cache3/26/ql_e135345347e9b6a760577a7f28876f26_l3.png): Predicted change in liquidity by user ![Formula](https://quicklatex.com/cache3/0b/ql_ebc3da03e5724ce1a1cf155b4d43c70b_l3.png)
- ![Formula](https://quicklatex.com/cache3/21/ql_44cd056d41f8c32318fb9ac245de5921_l3.png): Actual change in liquidity
- ![Formula](https://quicklatex.com/cache3/85/ql_2ffced18fbd986db6c61139ec61b3085_l3.png): Number of participants

The more accurate the user's prediction ![Formula](https://quicklatex.com/cache3/26/ql_e135345347e9b6a760577a7f28876f26_l3.png) is compared to the actual change ![Formula](https://quicklatex.com/cache3/21/ql_44cd056d41f8c32318fb9ac245de5921_l3.png), the higher the reward.

### Phase 3: System Testing and Launch

#### 1. Integration and Load Testing
- Perform integration tests to ensure all components work seamlessly.
- Conduct load tests to validate system stability under high demand.

#### 2. System Launch
- Prepare the system for deployment and ensure robust support for users after the launch.




## Music Inspiration

Here are some songs that inspired the creation of WidePiper. We recommend giving them a listen for some insight into the vibe and spirit behind the project:

- [track 1](../music/audio(2).mp3)  
- [track 2](../music/audio(3).mp3)  
- [track 3](../music/audio(5).mp3)  
- [track 4](../music/audio(8).mp3)  
- [track 5](../music/audio(9).mp3)  

## License

This project is licensed under the GNU General Public License v3.0.

You are free to use, modify, and distribute this software, provided that any modifications you make are also shared under the same license terms.

For more details, please refer to the full license file: [LICENSE](../LICENSE)