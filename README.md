# mint-aptos-nft

## Project Description

**mint-aptos-nft** is a Move smart contract project designed for minting NFTs on the Aptos blockchain. It provides the foundation for creating and managing non-fungible tokens (NFTs) with customizable metadata and ownership logic.

## Features

- 🎨 Mint unique NFTs on Aptos
- 🔒 Secure asset ownership and transfer mechanisms
- 🛠️ Easy customization of NFT metadata
- ⚡ Optimized Move smart contracts for performance

## Installation

```bash
# Clone the repository
git clone https://github.com/sherrigonzalez1963122/mint-aptos-nft.git
cd mint-aptos-nft
```

## Usage

### Compile Move Contracts

```bash
# Compile the Move package
aptos move compile --package-dir .
```

### Deploy Contracts

```bash
# Publish the NFT minting contract to the Aptos network
aptos move publish --package-dir . --profile default
```

### Mint an NFT

Example command (after deployment):

```bash
# Run an entry function to mint an NFT (example parameters needed)
aptos move run-entry-function \
  --function-id "mint_aptos_nft::module::mint_nft" \
  --args "TokenName" "TokenURI"
```

> Be sure to replace `TokenName` and `TokenURI` with your actual NFT metadata.

## Project Structure

- `sources/`: Contains the Move smart contracts
- `Move.toml`: Move package configuration

## Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Implement your changes
4. Commit your work (`git commit -m 'Describe your changes'`)
5. Push to your branch (`git push origin feature/your-feature-name`)
6. Create a pull request

## License

This project currently does not specify a license. Please contact the repository owner for usage terms.

## Links

- [Aptos Documentation](https://aptos.dev/)
- [Move Language Documentation](https://move-language.github.io/move/)
- [Aptos GitHub](https://github.com/aptos-labs)
