## How to Create a subgraph

1. Got to graph website and create new subgraph
2. Install graph cli using `npm install -g @graphprotocol/graph-cli`
3. Initialize subgraph using `graph init --studio nft-marketplace`
4. Write your Schema and mapping(instructions on what to do on event)
5. Most of the code is automatically created thanks to Graph.
6. Authenticate graph in cli using `graph auth --studio 805f1108cdf3ea996eaf46d63`
7. Generate type and build folder using `graph codegen && graph build`
8. Finally deploy your subgraph `graph deploy --studio nft-marketplace`
# nft-marketplace-subgraph
