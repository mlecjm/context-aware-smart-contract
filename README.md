# Context-aware smart contracts for blockchain IoT systems

It contains 2 directories:

1. 'contracts': contains the ContextAwareSmartContract.sol contract with the artifacts.
2. 'app': contains javascript application scripts for the dApp (decentralized application).


## DIRECTORIES

The 'app' folder contains app.js script for connecting with the 'ContextAwareSmartContract.sol' contract.
For the deployment of the contract, 'address' and 'totalDevicesPowerValue' should be updated (according to the devices you are testing). 


To run a script, type in terminal 'sudo node app.js'. Remember, Solidity file must be compiled.

## Deployment of the system

1. Download all necessary dependencies and libraries required of your system to run and the Quorum blockchain
Blockchain:
- Vagrant
- Virtual box/Docker

dApp libraries:
- Node js
- pigpio
- OnOff
- web3.js

Sensors libraries:
- node-dht-sensor
- mcp-spi-adc

2. Set up your Quorum client or create the quorum blockchain
3. Set up your Quorum nodes number and node urls
4. Deploy a decentralized application at the IoT gateway node(s) connected to the blockchain node (s)
5. Connect web3 to your Quorum nodes on the dApp
6. Deploy the smart contract on Quorum (sandbox) or remix
7. Connect dApp with smart contract ( bytecode, json, abi)
8. Send a private transactions and interact with contract privately by running the app.js on the terminal.

Output from script will appear in terminal.
