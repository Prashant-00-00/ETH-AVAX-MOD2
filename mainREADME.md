# Next.js/Hardhat Project

This project combines a Next.js front-end with a Hardhat development environment for Ethereum smart contracts.

## Prerequisites

- Node.js and npm installed on your computer
- MetaMask extension installed in your browser

## Steps to Start the Project
1. Clone the project repository:

```
git clone <repository-url>
```
2. Navigate into the project directory:

```
cd <folder>
```
3. Install the dependencies:
```
npm install
```
4. Open three terminals:

#### Terminal 1: 
Run the Next.js development server:
```
npm run dev
```
This will start the frontend on http://localhost:3000/.

#### Terminal 2: 
Start the Hardhat node to simulate a blockchain:
```
npx hardhat node
```
Note the RPC URL which is http://127.0.0.1:8545/.

#### Terminal 3: 
Compile and deploy the smart contracts:
```
npx hardhat compile
npx hardhat ignition deploy ./ignition/modules/TicketSales.js --network localhost
```

This will launch the front-end application, typically accessible at `http://localhost:3000/`.

## Connecting MetaMask

To interact with the deployed contracts, you need to connect MetaMask to the local Hardhat network:

1. Open MetaMask and click on the network dropdown at the top.
2. Select "Custom RPC".
3. Enter the following details:
    - **Network Name**: Localhost 8545
    - **New RPC URL**: http://localhost:8545
    - **Chain ID**: 1337 (default Hardhat network ID)
4. Save the network.

Then, import one of the generated accounts from the Hardhat node into MetaMask using the private keys displayed in the Hardhat terminal.

## Common Issues

- **Error: "Internal JSON-RPC error"**: Ensure that your MetaMask is connected to the correct network and the contract address is correct.
- **Dependencies Not Installed**: Make sure you run `npm install` inside the project directory.

## License

This project is licensed under the MIT License.
