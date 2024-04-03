# graph_nft_market Demo

  - [TheGraph Address](https://thegraph.com/studio/subgraph/lu-nft-marketplace/)


## Blockchain Ends associated to this project
- [frontend](https://github.com/Luyunee/frontend_nft_market/blob/main/README.md)
- [smart contracts deployment](https://github.com/Luyunee/hardhat_nft_market/tree/master)


## Built With

#### **Frontend** <sub><sup>React + JavaScript</sup></sub>
  - [React](https://pt-br.reactjs.org/)
  - [Next.js](https://nextjs.org/)
  - [Wagmi](https://wagmi.sh/)
  - [Web3UiKit](https://github.com/web3ui/web3uikit)

#### **Blockchain and Smart Contracts** <sub><sup>Solidity</sup></sub>
  - [Solidity](https://docs.soliditylang.org/)
  - [Hardhat](https://hardhat.org/)
    
#### **Data indexing** <sub><sup>GraphQL</sup></sub>
  - [TheGraph](https://thegraph.com/docs/zh/)




## How to Use
Now go to project folder and run:


```bash
$ cd graph_nft_market/lu-nft-marketplace

# run the client-side
$ yarn start

# initialize subgraph
graph init --studio lu-nft-marketplace

# authenticate in cli
graph auth --studio 1618f4cde268a307bea96f467fb50d00

# build subgraph
graph codegen && graph build

# deploy subgraph
graph deploy --studio lu-nft-marketplace
```
