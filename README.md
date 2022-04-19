## StreamPay Mobile Wallet

A StreamPay Mobile Wallet in flutter. It's work in progress, expect bugs, use carefully.

Non-custodial cross-platform wallet for Solana. Create a payment streams for stablecoins, and crypto currencies.

Features:
- Add New Wallet
- Support Stream Payment Gateway & Web Plugin (WordPress/WooCommerce)
- Support USDC
- QR code payment
- Import wallets with it's seedphrase (devnet only for now)
- Create new wallets (devnet only for now)

🎉 Support this project
You can support this project by donating any amount you want to these addresses;

SOL: 8k1JM5Cd6Hz7G6Jsq1FSzgRYPyS4RFj9k11Uvt5bgWRP


### Building android

```
flutter build android
```

### Building iOS

```
flutter build ios
```

### ToDo / Ideas

- [ ] Handle `solana:` links, this way the wallet will be prompted to the user (experimental)
- [ ] Add password encryption
- [ ] [Solana Pay](https://solana-pay-docs.vercel.app/core/wallet-integration) integration, implemented, but highly experimental
    - [ ] QR Reader (Support Solana Pay)
    - [ ] Ability NFC Readers and payment support
    - [ ] Point of Sale support (local store payment support)
    - [ ] SOL, USDC and Stream Token Transactions (Experimental)
    - [ ] Cross-Chain Transactions (Experimental). Ex. Bitcoin Lightning Network
    - [ ] SPL Tokens Transactions (Experimental)
    - [ ] Support for Label, Message, Memo and Metadata
    - [ ] QR Generator (WIP, like https://github.com/solana-labs/solana-pay/tree/master/point-of-sale does )
        - [ ] SOL transactions (Experimental)
        - [ ] SPL Tokens transaction (Experimental)
        - [ ] Compare the new received transaction by finding it with the reference, just to make sure the amount is correct
- [ ] Mainnet/betanet/custom net support
- [ ] Ability to name and rename imported and created wallets, and watched addresses
- [ ] Ability to make SOL, USDC, ETH, XRP, AVX, BTC, FYFY, Stream token "STRM" transactions (Multi-Currency support)
- [ ] Ability to refresh the current SOL, USDC value by pulling down
- [ ] Option to use another currency besides USD as equivalent currency
- [ ] Display latest transactions 
- [ ] Better project organization
- [ ] Ability to easily share an address (User wallet and QR Code)
- [ ] Have some UI tweaking options, like themes.
- [ ] Unit tests (WIP)
- [ ] StreamPay brand UI/UX tweaks (Add Teko fonts etc..)
- [ ] Display owned tokens
- [ ] Ability to display NFTs owned by an address 
- [ ] Create and Upload to https://itsallwidgets.com/
- [ ] Ability to add a small note when making transactions
- [ ] Ability to make transactions name service and domains
- [ ] Ability to make transactions with SPL Tokens
- [ ] Better UX (specially when creating accounts)
- [ ] Transactions Timestamps
- [ ] Better Windows UX (e.g, using split views)
- [ ] Send notifications when the app is closed and new transactions are received
- [ ] Add a contacts list (wallet address, naming, phone book?)
- [ ] Ability to update the encryption password once it's set

MIT License
