# academia-nft.github.io

## Academe

An NFT Marketplace application for people in Academia

# How to 

1. Update

   Either update the ganache account's private key in hardhat.config.js \
   Or register network in hardhat.config.js \
   If you are using your own network, then update rpcEndpoint in pages\index.js line 19 \
   E.g., \
   ```
   let rpcEndpoint = "http://127.0.0.1:7545";
   ```
2. Run
   ```
   npm install
   npx hardhat run --network your_network_name .\scripts\deploy.js
   npm run build
   npm start
   ```
   
   ![Video_21-11-25_12-14-12](https://user-images.githubusercontent.com/37606416/143383889-71c62b8c-a6c7-4662-9fa2-45498dac0b9a.gif)
   
   We would like to thank @x0protivol for proof-reading and updating the hard code with us.
