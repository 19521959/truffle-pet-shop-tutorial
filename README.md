# Truffle pet shop tutorial

[Truffle Tutorial](https://trufflesuite.com/tutorial/)

## Install Truffle

```bash
npm install -g truffle
```
## Compilation

```bash
truffle compile
```

You will see `build/contracts`.

## Migrate

migrate the contract to the blockchain. For tutorial, we are going to use [Ganache](https://trufflesuite.com/ganache/).

```bash
truffle migrate
```

## Test

```bash
truffle test
```


## Running Dapp

```bash
npm run dev
```

In the box marked Wallet Seed, enter the mnemonic that is displayed in Ganache.

**Warning**: Do not use this mnemonic on the main Ethereum network (mainnet). If you send ETH to any account generated from this mnemonic, you will lose it all!


![](https://raw.githubusercontent.com/regchiu/resources/master/truffle-pets-shop-turtorial/ganche-mnemonic.png)
