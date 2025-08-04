# Safucard

This is a dApp project that showcases how to integrate Alchemy’s APIs, Pinata, and Solidity to retrieve a wallet’s BEP-20 token data which includes the whale status, the first and most recent tokens held, and address age based on its first transaction. The user is then given the option of minting this information as an NFT at a predetermined price, using Chainlink’s Price Oracle for accurate conversion, which will then be uploaded to your Pinata File service and minted by the NFT Smart Contract.

## DEMO

- Live Link: [SafuCard](https://scorecard-frontend-teal.vercel.app)
- Network: BNB Smart Chain Testnet
- Verified Contract Code: 
- RPC URL: https://data-seed-prebsc-1-s1.binance.org:8545/

### TECH STACK/ PREREQUISITES

- Node.js v18+
- Express
- Hardhat
- React v19+
- A wallet (e.g metamask)
- Wagmi
- AlchemySDK
- PinataSDK

## Usage

1. # Clone The Repo
```bash
   git clone https://github.com/Domistro16/safucard.git
   cd safucard
   ```

2. Enter your BNB wallet address in the input field.
3. Click **Search** to fetch scorecard data and generate your SafuCard.
4. Click **Download** or **Fullscreen** to preview or save the image.
5. Optionally, click **Mint NFT** to upload to IPFS and mint the card as an NFT.

## Self-Hosting

To run the server locally:

1. ```bash
   cd SafuServer
   npm install
   npm run build
   ```
2. Configure .env variables by renaming .env.example to .env and inputing your
   ALCHEMY_KEY=
   GATEWAY_URL=
   JWT=

## License

This project is licensed under the MIT License.

## Contact

Email: desmondesih@gmail.com
