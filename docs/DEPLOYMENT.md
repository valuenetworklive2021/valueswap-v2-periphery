# Deployment

ropsten
  - ValueswapV2Router02 0xa8d200eaB94c77a98077c8e2631B2F2D00F2c1E7
    - old ?


## Install Dependencies
```bash
yarn
```


## Compile Contracts
```bash
yarn compile
```


## Run Tests
```bash
yarn test
```


## Deployment
```bash
yarn deploy <network>
yarn verify <network> ValueswapV2Router02
```


### Deployment for Ropsten
```bash
yarn deploy ropsten
yarn verify ropsten ValueswapV2Router02
```


### Deployment for Mainnetwork
```bash
yarn deploy mainnet
yarn verify mainnet ValueswapV2Router02
```


### ROUTER_ADDRESS
Replace in `ROUTER_ADDRESS`
 - for `valueswap-interface/src/constants/index.ts`.
