# Getting started with your BoltRing

To use your **BoltRing** you must pair it with a compatible Wallet and Bolt Card service. The
service is then responsible for verifying and processing the unique payment URLs generated by your 
BoltRing according to the configured payment rules.

As always, with Bitcoin, there are different options for setting up, operating, or using a Bolt Card
service for your BoltRing, with varying features and tradeoffs.

!!! danger "Backup your Keys"

    You need keys to re-configure your BoltRing. **Without keys you cannot reset or re-configure
    your device!**

    Keys are initialy set to ZERO at factory settings unless you bought a pre-configured BoltRing.
    For pre-configured BoltRings the keys are printed as QR code on the enclosed leaflet.
 
    After you re-configured your BoltRing **you will need the newly set keys** for any further 
    re-configuration (the original keys will not work anymore).

## BoltRing Pairing Options

| Wallet/Service                        | Custodial | Open Source | Exchange | Difficulty |
|---------------------------------------| --------- | ----------- | -------- |------------|
| [CoinCorner](#coincorner)             | Yes       | No          | Yes      | Easy       |
| [Bolt Card Wallet](#bolt-card-wallet) | Yes/No    | Yes         | No       | Easy       |
| [LNbits](#lnbits)                     | Yes/No    | Yes         | No       | Advanced   |

### CoinCorner

[![CoinCorner Icon](images/coincorner-icon.png){ align=right width=30% }](https://www.coincorner.com/)

For non-technical folks and iPhone users, CoinCorner is probably the easiest way to get started.
CoinCorner launched the Bolt Card in May 2022. They offer many Bitcoin-related services for users
and merchants, including a custodial lightning wallet and fiat exchange services.

!!! tip
    Before creating an account with CoinCorner, make sure their service is available in your [country](https://www.coincorner.com/Countries)

If you sign up with CoinCorner, you can easily pair your BoltRing with their mobile lightning wallet
using any NFC-capable iPhone or Android device. The pairing procedure is the same as with the Bolt
Card. Use our referral link to sign up:

[Go with CoinCorner](https://www.coincorner.com){.md-button .md-button--primary}

### Bolt Card Wallet

[![Bolt Card Icon](images/bolt-card-icon.png){ align=right width=20% }](https://boltcardwallet.com/)

Another option is the Bolt Card Wallet for Android or iOS which is a modified version of 
[Bluewallet](https://bluewallet.io/). The app is 
[open source](https://github.com/boltcard/boltcard-wallet) and allows you to connect your BoltRing
with a Bolt Card Hub Service that you can run yourself. You may also use a public instance
(custodial) of the Bolt Card Hub.

[Install Bolt Card Wallet](https://boltcardwallet.com/){.md-button .md-button--primary}

### LNbits

[![LNbits Icon](images/lnbits-icon.png){ align=right width=20% }](/lnbits)

LNbits is a free, open-source lightning account system with many features, including a Bolt Card
extension. You can use a hosted LNbits service or, provided that you have the necessary technical
skills, install and operate your own LNbits service.

[LNbits Setup Guide](/lnbits){.md-button .md-button--primary}
