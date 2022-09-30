
# Subgraph for AW Magical Keys NFT collection

### Pre-requirements
`yarn global add @graphprotocol/graph-cli`

## Install
```
git clone https://github.com/atlantis-world-core/magical-keys-subgraph.get
cd magical-keys-subgraph
yarn install
```

## Generate types
`yarn codegen`

## Build graph sources
`yarn build`

## Deploy
```
graph auth
graph deploy --node https://api.thegraph.com/deploy/ <GRAPH_USERNAME>/atlantis-world-magical-keys
```