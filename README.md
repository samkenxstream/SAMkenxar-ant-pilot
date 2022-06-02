# Gateway Name Token Proof of Concept

## Project setup
```
yarn add arweave@1.10.23 arlocal@1.1.30 redstone-smartweave@0.5.6
```

### Compiles and minifies for production
```
yarn build
```

### Tests contracts with arlocal
```
yarn test
```

### Tools
In order to deploy contracts and use the Gateway Name Service Registry (along with creating Gateway Name Tokens) the following tools are available to be used. 

Make sure to update the variables at the top of each tool's `.ts` file, as well as the local wallet file in `constants.ts`  

- `create-gnt` creates a new GNT with arweave data pointer
- `create-test-gnt` creates a new GNT with arweave data pointer on RedStone Testnet
- `deploy-contract` deploys a new GNT Contract to mainnet  
- `deploy-test-contract` deploys a new GNT Contract to Redstone Testnet  
- `remove-record` removes an existing record from the GNT
- `remove-test-record` removes an existing record from a GNT on Redstone Testnet
- `transfer-gnt` transfers a GNT to another wallet  
- `transfer-test-gnt` transfers a GNT to another wallet on Redstone Testnet
- `update-record` creates a new record in a GNT or updates existing one
- `update-test-record` creates a new record in a GNT or updates existing one on Redstone Testnet


