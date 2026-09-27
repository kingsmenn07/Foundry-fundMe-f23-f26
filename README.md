## Foundry
1. proper README
2. Integration tests
PIT STOP! How to make running these scripts easier???
3. Programatic verification
4. push to GitHub


## ABOUT
This is a sourcing app for Learning solidity and smart contract for security research purpose

## Getting Started

Requirements
* git
     ```shell
     git --version
     and you will see a response like>> git version x.x.x.
     that is when you know you got it right                                          
* foundry
    ```shell
    forge --version 
    and you will see a response like>> forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z),
    that is when you know you got it right   

* Quickstart
    ```shell
   git clone git@github.com:kingsmenn07/Foundry-fundMe-f23-f26.git

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage
## Deploy
```shell
 forge script script/DeployFundMe.s.sol

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge test --fork-url $SEPOLIA_RPC_URL
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
