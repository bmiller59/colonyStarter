---
title: colony-cli
section: CLI
order: 1
---

The `colony-cli` package is a command line tool for building [colonyStarter](https://github.com/JoinColony/colonyStarter) packages and running services such as Ganache, Truffle, and Trufflepig to assist with local development alongside the [colonyNetwork](https://github.com/JoinColony/colonyNetwork) smart contracts.

## Prerequisites

- Node `>=10.12.0`
- Yarn `>=1.12.0`
- Docker `>=18.09.0`

_You may find it helpful to use Node Version Manager (`nvm`) to manage Node versions._

_If you are using Linux, check out [Linux Setup](/docs-linux-setup/) to ensure Yarn and Docker are set up accordingly._

## Install

Install the `colony-cli` package globally:

```
yarn global add @colony/colony-cli
```

## Commands

### `build`

Build [colonyStarter](https://github.com/JoinColony/colonyStarter) packages:

```
colony build [package-name]
```

### `service`

Start a local test network with [Ganache](https://github.com/trufflesuite/ganache-cli):

```
colony service start-ganache
```

Deploy the [colonyNetwork](https://github.com/JoinColony/colonyNetwork) smart contracts:

```
colony service deploy-contracts
```

Serve truffle contract data with [TrufflePig](https://github.com/JoinColony/trufflepig):

```
colony service start-trufflepig
```

Seed the network with global skills:

```
colony service seed-network
```
