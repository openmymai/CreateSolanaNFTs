#### Create Solana NFTs with Metaplex
- Non-Fungible Tokens (NFTs) are SPL Tokens with an associated metadata account, 0 decimals, and a maximum supply of 1
- Metadata attaches additional properties to token mints (both NFTs and regular tokens). For NFTs, metadata includes the token name and a link to an offchain JSON file. This JSON file contains links to artwork and other media files, any special traits the NFT has, and more.
- The Metaplex Token Metadata program is an onchain program that attaches metadata to a token mint. We can interact with the Token Metadata program using the Token Metadata package via Umi, a tool made by Metaplex for working with onchain programs.
