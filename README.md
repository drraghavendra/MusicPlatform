# MusicPlatform

Problem Statement Identified and Stated as - In today’s world, Music artists are struggling for monetary benefits for their work. The royalty distribution in its present form makes it difficult to keep the fair share of revenue they generate on existing art selling platforms. Moreover, there’s no transparent and decentralised platform for the same.

What is Musicplatform? Musicplatform is a decentralised application(dApp) for musicians to create NFTs of their music. These NFTs can then be traded and each time an NFT gets traded, the musician will get 5% of the trade as royalty! It is a platform to trade individual NFTs of songs. NFTs from artists can be looked at as stocks in the market. Just as buying stocks of companies that people believe to perform good in the future can result in massive profits, similarly, the value of these NFTs can skyrocket if that artist grows to be successful over time. We aim to uplift musicians by enabling them to creating NFTs of their music and providing them with royalties and recognition that they deserve but are not able to get enough from other sources.

The problem MXV solves- Musicplatform is powered by cryptocurrency, using future-proof blockchain & smart contract technology to connect artists, fans, and investors like never before. Musicians are unable to receive the deserved revenue/share/royalty from their art form via currently available platforms (Source: Forbes). We aim to create a platform which leverages the artist from his/her dependency on the platform for providing their desired share. Artists can raise money by selling their music as NFTs, while fans can support and form closer connections to their idols by purchasing a real stake in their career. Even if the art has been sold, the artist will still be getting a percentage of trade! Thus providing the artist with benefits and the recognition they actually deserve. By basing the MXV platform on the Polkadot blockchain and storing all the tracks on IPFS, there is no central server and so the storage costs are drastically reduced. This allows for more of the revenue to go directly to the artist, in a more secure, transparent, and decentralised way than ever before.


## How to setup

-   Fork the repo to your account

-   Clone the forked repo to your local system using `git clone https://github.com/<your-username>/Musicplatform

-   Connect your local repo to the upstream using `git remote add upstream https://github.com/drraghavendra/Musicplatform

-   Run `npm install` to install npm dependencies

-   Start the local development blockchain on Ganache

-   Connect Metamask to local Ganache blockcahin

-   Run `truffle migrate --reset` in the terminal

-   Run `npm start` to start the React application

## How to contribute?

-   **DO NOT** make and push changes to the main branch!

-   **Always** keep your main/working branch in sync with the main repository `git pull upstream main` on the branch you are working on locally.

-   **Always create a new branch** before making any changes `git checkout -b <new-branch-name>`, never ever make any changes directly on the master/main branch.

## Running the Test Script

Just run: `truffle test`

## Migrate the Contract after making any changes inside the contracts folder

`truffle migrate --reset`

## Testing in Truffle console

-   Run: `truffle console`

-   `Musomatic.deployed().then(function(instance) {contract = instance})`

-   Test the deployed contract:

    `contract.address`

    `contract.name()`

    `contract.symbol()`

-   To check the created song:
    `contract.songs(0)`

## Migrating to Polygon Testnet

-   `truffle migrate --network polygonTestnet`
