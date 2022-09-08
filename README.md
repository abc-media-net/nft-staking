# Instructions & Description

Simple instructions and clear explanation on every file included in this repository.

## Collection.sol

Basic NFT smart contract with all functions and fetures needed for most of the collections.

### Note for the beginners

You need to change "ABC Media NFT Collection" to your collection name and also come up with your own token ID and replace "ABC" with it. After you have done that, the only important thing to do is to edit "int256 public maxSupply = 10000" to your preferred max supply. To clarify even more you just need to change the number "10000" to match the max supply of your collection. All other edits can be done after you deploy the contract like "function _baseURI" link to match the one where you uploaded your .img and .json files. It can also be ipfs link but we prefer the regular https mainly because we can easily edit or replace the NFT image or description if needed and we like to store our collection files on our own servers. You can change that later but keep in mind that you need to pay gas fee for every single change on your contract after you have deployed it.
