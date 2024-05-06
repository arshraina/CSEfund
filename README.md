### Quickstart
```
cd SPITfund
yarn
yarn start
```

```
cd SPITfund
cd contracts
yarn
yarn hardhat deploy
yarn hardhat node
```

### Add hardhat network to your metamask/wallet

- Get the RPC_URL of your hardhat node (usually `http://127.0.0.1:8545/`)
- Go to your wallet and add a new network. [See instructions here.](https://metamask.zendesk.com/hc/en-us/articles/360043227612-How-to-add-a-custom-network-RPC)
  - Network Name: Hardhat-Localhost
  - New RPC URL: http://127.0.0.1:8545/
  - Chain ID: 31337
  - Currency Symbol: ETH (or GO)
  - Block Explorer URL: None