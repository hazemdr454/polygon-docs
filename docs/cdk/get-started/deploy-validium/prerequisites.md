## Hardware

- A Linux-based OS (e.g., Ubuntu Server 22.04 LTS).
- At least 16GB RAM with a 4-core CPU.
- An AMD64 architecture system.

## Software

Make sure you have the following software:

| Download link | Version | Check version |
| --- | --- | --- |
| [Node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) | ^20 | `node --version` |
| npm | ^10 | `npm --version` |
| [Foundry](https://book.getfoundry.sh/getting-started/installation) | ^0.2 | `forge --version` |
| [jq](https://jqlang.github.io/jq/download/) | ^1.6 | `jq -V` |

## Sepolia access

You will need the following:

- A Sepolia node RPC URL: e.g. https://goerli.infura.io/v3/YOUR-INFURA-API-KEY
- An account address holding minimum 2 Sepolia ETH.

### Faucets

Use a public faucet to get Sepolia test ETH. 

- [Infura faucet](https://www.infura.io/faucet/sepolia).
- [Chainstack faucet](https://chainstack.com/sepolia-faucet/).
- [Quicknode faucet](https://faucet.quicknode.com/ethereum/sepoli).

## Configuration files

Create a folder inside `/tmp/` named `/cdk/` that will store all the configuration files.

```bash
mkdir /tmp/cdk/
```

## Environment variables

Create a `.env` file to store environment variables.

```bash
nano /tmp/cdk/.env
```