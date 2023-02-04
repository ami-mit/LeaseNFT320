# LeaseNFT320
Allowing easy renting and borrowing  of NFT/Digital Assets. 
LeaseNFT320 is a protcol implementation of collateral based lending of NFT/Digital Assets. 
Using our protocol, anyone can rent NFT/Digital Assetsfor a specified collateral and rental price for a set duration. 
We hope to make renting NFT/Digital Assets feature available on all NFT/Digital Assets marketplaces.
LeaseNFT320 uses a front-end interface built in NextJS to allow any NFT borrower to lease NFT. 
Also, borrower can see the collateral price and rental price before renting the NFT. 
Backend is built using solidity and for blockchain simulation we are using Hardhat. 
Our aim is to develop a library to make leasing NFT feature available on all NFT marketplaces and games. 
We are using Infura fro IPFS integration for NFT data integration.
LeaseNFT320 is an application which acts as marketplace for leasing NFTs. A lender can list his NFTs for listing on our application. Lender can set the collateral which he wants for renting his NFT. Lender can also set rental price and duration for which he will lease the NFT. Once a lender has made his NFT available for leasing, NFT is transferred to LeaseNFT320 platform and we are the custodian of the NFT. All NFTs which are available for leasing are listed on our application. A borrower can lease NFT from our application. Borrower can choose NFT depending on collateral and rental price which is listed out. Post rental period expiry, borrower can return NFT can reclaim collateral. In case of default, LeaseNFT320 will liquidate the collateral and return it to lender of NFT. We also aim to provide LEASING api to NFT marketplaces and games. Future roadmap is to provide collateral-less lending to certain environments such as games in metaverse.
