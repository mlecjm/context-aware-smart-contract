## Context-aware smart contracts for blockchain IoT systems

It contains 2 directories:

1. `contracts`: contains the `ContextAwareSmartContract.sol` contract with the artifacts.
2. `app`: contains JavaScript application scripts for the DApp (decentralized application).


### Directories

The `app` folder contains app.js script for connecting with the `ContextAwareSmartContract.sol` contract.
For the deployment of the contract, `address` and `totalDevicesPowerValue` should be updated (according to the devices you are testing).


To run a script, type in terminal `sudo node app.js`. Remember, Solidity file must be compiled.

### Deployment of the system

1. Download all necessary dependencies and libraries required of your system to run and the Quorum blockchain
Blockchain:
- [Vagrant](https://www.vagrantup.com/docs/installation)
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)/[Docker](https://docs.docker.com/engine/install/)

dApp libraries:
- [nodejs](https://nodejs.org/en/download/) 
- pigpio
- OnOff
- [web3.js](https://web3js.readthedocs.io/en/v1.7.3/)

Sensors libraries:
- node-dht-sensor
- mcp-spi-adc

2. Set up your Quorum client or create the quorum blockchain
3. Set up your Quorum nodes number and node urls
4. Deploy a decentralized application at the IoT gateway node(s) connected to the blockchain node (s)
5. Connect web3 to your Quorum nodes on the DApp
6. Deploy the smart contract on Quorum (sandbox) or remix
7. Connect DApp with smart contract ( bytecode, json, abi)
8. Send a private transactions and interact with contract privately by running the app.js on the terminal.

Output from script will appear in terminal.

### iBELab - Intelligent Blockchain Engineering Lab.
https://ibel.korea.ac.kr/ - Korea University
