# NFT Pixels

NFT Pixels is a social dApp built for creators, makers, artists, and anyone who loves painting, design, or drawing.

With our NFT Pixels platform, anyone can create an NFT, customize it, or design one within minutes. Our simple and practical online art editor allows anyone with or without experience to create NFTs in a fun way. As well as to sell them in our marketplace.

Whenever a viewer goes to the app he or she will be able to browse NFTs from different creators, see details from specific NFT and play for a chance to win an NFT.

If the user successfully guessed the secret number, the user will be celebrated by confetti, and he/she will be able to mint the NFT. Try it, it is really fun!

Then the app will notify you about your transaction, it should redirect the user to the polygon network to see the details of the transaction.

Why Did I use IPFS?
I wanted to use IPFS to design a simple and fun app where everyone can collaborate, learn about NFTs and experience them directly.

How it's made?
NFT Pixels application makes use of the following software:

NFTStorage: the data is stored on NFTStorage IPFS, the generated hash (CID) will be used to view the details and to retrieve the NFT.

We use everywhere IPFS, code line:

- https://github.com/electrone901/NFTStorag-pixel/blob/40ec4184a7b16e389692e8fbbc4d42fa57cd14f1/src/components/create-post/CreatePet.js#L40
- https://github.com/electrone901/NFTStorag-pixel/blob/40ec4184a7b16e389692e8fbbc4d42fa57cd14f1/src/components/home/PetGallery.js#L21

Solidity: Solidity was used for the smart contract together with OpenZeppelin ERC721 for faster development of the smart contract

Ganache: for local blockchain development

Polygon, Matic Network: the network I deployed the app.

Frontend: React Js for the frontend, Material-UI, and Web3 to connect to the blockchain.

Deployed website Demo: https://00012ucolb73g08pag0mikd4ffjusi5a5rlmiasrar4kut09jmtp8hg.siasky.net/pet-details/bafyreiccqxygmb4ozq3eycuwuf7czsodj527xtbg26cbt3xakv7ft3ar2m)

# How it's made

NFT Pixels application makes use of the following softwares:

### `NFTStorage` for data storage on IPFS that generates a transation hash used to retrive the NFT .

### `Solidity` for the smart contract

### `OpenZeppelin ERC721` we use the ERC721 template for a faster development of the smart contract

### `Ganache` for local blockchain development

### `Polygon, Matic Network` the network I deployed the app

### `React Js, Material-ui, Web3` React Js for the frontend, Material-ui and Web3 to connect to blockchain.

### `Unlock Protocol` to allow users to pay for exclusive content this protocol was a big part of our use case.

## Demo

Website Demo:

- [Demo](https://00012ucolb73g08pag0mikd4ffjusi5a5rlmiasrar4kut09jmtp8hg.siasky.net/pet-details/bafyreiccqxygmb4ozq3eycuwuf7czsodj527xtbg26cbt3xakv7ft3ar2m)

  ![Main Page]() <br> <br>

# Getting Started

### `yarn start`

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
