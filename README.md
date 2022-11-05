# staking-contracts

Smart contracts for Archie Chain

## How to start

```shell
$ git clone https://github.com/archieneko/staking-contracts.git
$ cd staking-contracts
$ npm i
```

## Staking and Unstaking
Please make sure required values are set in .env to use this command
```
cp .env.example .env
```
Add your private key to the .env file and save

### Stake balance to contract
```shell
$ npm run stake-test
```

### Unstake from contract

```shell
$ npm run unstake-test
```

### Check current total staked amount and validators in contract

```shell
$ npm run info
```

## Building Contract from Source
### Build contracts

```shell
$ npm run build
```

### Run unit tests

```shell
$ npm run test
```

### Deploy contract to ArchieChain

```shell
$ npm run deploy
```