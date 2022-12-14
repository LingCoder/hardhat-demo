# Hardhat-template

<div align=center style="background:lightgrey">
<img src="./logo.svg" width=250" height="100" />
</div>
<div align=center>
<img src="https://img.shields.io/badge/solidity-^0.8.17-blue"/>
<img src="https://img.shields.io/badge/hardhat-^2.10.2-red"/>
<img src="https://img.shields.io/badge/etherjs-v5-green"/>
<img src="https://img.shields.io/badge/@openzeppelin-^4.8.0-green"/>
</div>

English | [简体中文](./README_zh.md)

## Quick Start

```bash

npm install -g yarn

yarn install

```

## Quick Commands

```bash
    yarn compile
    yarn deploy
    yarn test
    yarn test:coverage
    yarn test:size-contracts
    yarn lint:sol
    yarn lint:sol:fix

```

## Hardhat Commands

```bash
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
REPORT_GAS=true npx hardhat test
npx hardhat coverage
npx hardhat run scripts/deploy.ts
TS_NODE_FILES=true npx ts-node scripts/deploy.ts
npx eslint '**/*.{js,ts}'
npx eslint '**/*.{js,ts}' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix

```

## Other Commands

Deploy the contract to a specific network

```shell
  npx hardhat run --network rinkeby deploy/deploy.ts
```

Validate deployed contracts

```shell
npx hardhat verify --network rinkeby "DEPLOYED_CONTRACT_ADDRESS" "constructor-args1" "constructor-args2"
```
