# my-nft
First experience creating a smart contract and minting a NFT on Etherium

This was done following: [HOW TO MINT AN NFT](https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/) & [HOW TO MINT AN NFT](https://ethereum.org/en/developers/tutorials/how-to-mint-an-nft/)

Setup

* Install dependencies
* Add your keys on a .env file
* Run `npx hardhat compile` to compile the contact
* Run `npx hardhat --network ropsten run scripts/deploy.js` to deploy the contract
* Replace the contract address with yours contract address on the file `scripts/mint-nft.js` 
* Create your NFT medatada
* Run `node scripts/mint-nft.js` to deploy your NFT
