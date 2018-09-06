# Scopuly Stellar Wallet & SDEX

### Safe cold storage (local secret key encryption)
### P2P Trade in crypto Assets (DEX)
### Asset Tokenization
### ICO & Token Marketplace

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
  * Managing Trust
  * Managing multi-signatures
  * Management of trade offers
  * Merge Accounts
  * Recovery Account
* Multiple assets
    * Issue/Redeem
    * Send/Receive/Trade

* Creation / reception of payment requests by QR-code

* Multisignature

* Add contacts
    * using QR code
    * from a transaction

* Add memo to transactions

* Import/export accounts
    * QR code
    * Manual input


## Security

All private keys are stored in localStorage, encrypted or not. Within the app, key decryption and transaction signing all take place inside the `Keychain` service in `app/core/services/keychain.js`. The only time an unencrypted private key leaves that service is when an account is being exported and you're not using password protection.

All transactions go through the same steps of being displayed for review before being signed and submitted.

## License

**Scopuly** is released under the AGPL

* app/core/controllers/scanner.js
* app/core/directives/qr-scanner.js
* app/core/services/platform-info.js

which originate from **Copay**, and are made available under the terms of the **MIT License**.

Copyright &copy; 2016-2018 MBK, LLC
