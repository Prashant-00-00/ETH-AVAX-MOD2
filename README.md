<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">Smart Contract Management - ETH + AVAX
</h1>
</p>


## Quick Links

- [Quick Links](#quick-links)
- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running ETH-AVAX-MOD2](#running-eth-avax-mod2)
  - [Start the Hardhat Local Node](#start-the-hardhat-local-node)
  - [Deploy the Smart Contracts](#deploy-the-smart-contracts)
  - [Launch the Front-End](#launch-the-front-end)
- [License](#license)
- [Creator](#creator)

---

## Overview

ETH-AVAX-MOD2 is an integrated project combining a Next.js front-end with a Hardhat Ethereum development environment. It demonstrates the deployment and interaction with Ethereum smart contracts, leveraging modern web technologies.

---

## Features

- **Smart Contract Deployment**: Seamlessly deploy and interact with Ethereum smart contracts.
- **Next.js Front-end**: A dynamic and responsive user interface built with Next.js.
- **Local Blockchain Simulation**: Utilize Hardhat to simulate a local blockchain environment for testing.
- **Comprehensive Testing**: Ensure code quality and functionality with integrated testing.

---

## Repository Structure

```sh
└── ETH-AVAX-MOD2/
    ├── LICENSE
    ├── README.md
    ├── contracts
    │   └── Gill.sol
    ├── hardhat.config.js
    ├── package-lock.json
    ├── package.json
    ├── pages
    │   └── index.js
    └── scripts
        └── deploy.js
```

##  Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **JavaScript**

###  Installation

1. Clone the ETH-AVAX-MOD2 repository:

```sh
git clone https://github.com/Prashant-00-00/ETH-AVAX-MOD2.git
```

2. Change to the project directory:

```sh
cd ETH-AVAX-MOD2
```

3. Install the dependencies:

```sh
npm install
```

###  Running ETH-AVAX-MOD2

### Start the Hardhat Local Node

Open a new terminal and start the Hardhat local blockchain node:

```bash
npx hardhat node
```

This will start a local Ethereum network for development.

### Deploy the Smart Contracts

In another terminal, deploy the smart contracts to the local network:

```bash
npx hardhat run --network localhost scripts/deploy.js
```

This will compile and deploy your smart contracts to the local Hardhat network.

### Launch the Front-End

Back in the first terminal, start the Next.js development server:

```bash
npm run dev
```

This will launch the front-end application, typically accessible at `http://localhost:3000/`.

##  License

- This project is licensed under the MIT License.


---
##  Creator

- Prashant Kumar