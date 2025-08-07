# NFT Project

My learning NFT project that I built with the help of one of the best web3 mentors - Patrick Collins

Through this course I made:

1. An IPFS Hosted NFT
2. An SVG NFT(fully hosted on-chain)


## Quickstart

```
git clone https://github.com/fbabovic23/foundry-first-NFT-project
cd foundry-first-NFT-project
forge install
forge build
```

## Deployment to a testnet or mainnet

1. Setup environment variables

You'll need to set up `SEPOLIA_RPC_URL` and `PRIVATE_KEY` as environment variables in `.env` file.

- `SEPOLIA_RPC_URL`: This is url of the sepolia testnet node you're working with. You can get setup with one for free from [Alchemy](https://alchemy.com/?a=673c802981)

Optionally, add your `ETHERSCAN_API_KEY` if you want to verify your contract on [Etherscan](https://etherscan.io/).


### Deploy (IPFS NFT)

```
make deploy ARGS="--network sepolia"
```

### Deploy (SVG NFT)

```
make deploySvg ARGS="--network sepolia"