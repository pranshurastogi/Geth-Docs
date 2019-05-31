# Geth-Parity-Docs

## What is Geth?

Geth is an implementation of an Ethereum node in the Go programming language.

In simpler terms, Geth is a program which serves as a node for the Ethereum blockchain, and via which a user can mine Ether and create software which runs on the EVM – the Ethereum Virtual Machine. This software can be things like crypto tokens, decentralized apps, and more.

### Download Link 

https://geth.ethereum.org/downloads/

## What happen after download ??
After startup, Geth will connect to the existing live blockchain or create its own, depending on provided settings. Left at the default values, Geth will connect to the live Ethereum blockchain (the Mainnet) which we use daily. Simply by running Geth, you're already participating in making the Ethereum network better and stronger. Geth also serves as a console for inputting certain commands and executing specific functions. 

## How to install in Ubuntu .

### Installing from PPA
```
sudo apt-get install software-properties-common
sudo add-apt-repository -y ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install ethereum
```
If you want to stay on the bleeding edge, install the `ethereum-unstable` package instead.
After installing, run `geth account new` to create an account on your node.
You should now be able to run `geth` and connect to the network.
Make sure to check the different options and commands with `geth --help`
You can alternatively install only the geth CLI with apt-get install geth if you don't want to install the other `utilities (bootnode, evm, disasm, rlpdump, ethtest).`

