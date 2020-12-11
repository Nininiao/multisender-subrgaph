# multisender-subrgaph
# Project description

Multisender is simply a project that lets its users send Ethereum, and Ethereum tokens to different Ethereum addresses in a single transaction.

This is the subgraph, a collection of GraphQL schemas and mappings that parse the events broadcast by this subgraph on the Ethereum blockchain.

The smart contracts can be found here https://etherscan.io/address/0xa5025faba6e70b84f74e9b1113e5f7f4e7f4859f#code.

# Development
Before you can build, create and deploy this subgraph, you have to execute the following commands in the terminal:

$ yarn install

$ yarn prepare:mainnet

The first command installs all external dependencies, while the latter generates the subgraph.yaml file, which is required by The Graph.

The manual how to Build a Subgraph via Contract on Windows for a Non-Tech Curators you can find here https://ninadrokina.medium.com/how-to-build-a-subgraph-via-contract-on-windows-for-a-non-tech-curator-74d5d9e47e96
