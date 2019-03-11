Scopuly provides a safe and secure way to use your Stellar accounts without trusting your private key to anyone. All sensitive data is encrypted with your password and securely stored in the browser.

# Scopuly Stellar Wallet & SDEX

- Safe cold storage (local secret key encryption)
- Decentralized trade in crypto Assets (DEX)
- Asset Tokenization
- ICO & Token Marketplace

Scopuly allows you to safely store and instantly transfer your crypto-currency assets, issue your own crypto tokens and launch ICO campaigns, invest in ICO projects, and also trade in crypto tokens on the decentralized Exchange of Scopuly DEX (Stellar Exchange) in real time, with zero commissions.

## Main features:

* Multiple accounts

* Accounts
  * Create Account
  * NameCard
  * Export Account
  * Import Acccount
  * Funding Account
  * Inflation
  * Managing Trustlines
  * Managing multi-signatures
  * Management of trade offers
  * Merge Accounts
  * Recovery Account
  
* Multiple assets
  * Issue/Redeem
  * Send/Receive/Trade
  * Trading tokens released
  * Establishment of the issuer's metainformation
  * Management of emission limitation

* Creation / reception of payment requests by QR-code

* Multisignature

* Contacts
  * Import By QRCode
  * Export QRCode
  * Autocomplete recipient when sent
  * from a transaction

* Add memo to transactions
    
* Choosing an interface design
  * Interface: iOS, MD
  * Theme: Light, Dark
  * Color: Red, Green, Blue, Pink, Ellow, Orange, White, Black


## Security

All private keys are stored in localStorage, encrypted or not. Within the app, key decryption and transaction signing all take place inside the `Keychain` service in `app/core/services/keychain.js`. The only time an unencrypted private key leaves that service is when an account is being exported and you're not using password protection.

All transactions go through the same steps of being displayed for review before being signed and submitted.

## Web 
https://scopuly.com/

## Apps
  * Android: https://play.google.com/store/apps/details?id=com.scopuly.app
  * iOS: https://itunes.apple.com/us/app/id1383402218
  * MacOS: https://github.com/Scopuly/scopuly/releases
  * Windows: https://github.com/Scopuly/scopuly/releases
  
## License

**Scopuly** is released under the AGPL

Copyright &copy; 2016-2018 MBK, LLC
