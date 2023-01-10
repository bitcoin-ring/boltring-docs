# BoltRing Quickstart

There are many options for setting up and using your **BoltRing** with varying tradeoffs. In this
quickstart guide we show you a simple setup using [LNBits](https://lnbits.com/) with the Bolt Card
extension as a service for your BoltRing. LNBits as a free open-source lightning account system. It
operates on top of a lightning funding source such as LND.

!!! danger "Security Warning"
    In this guide we use a public demo installation of LNbits. This means you are trusting the
    operators of the service with guarding the satoshis you send to the LNBits wallet. **Don´t be
    reckless** and use it with caution and only for testing with small amounts.

## Step 0 - Prerequisites

- An existing Lightning Wallet that you can use to fund your LNBits account
- An Android Mobile Phone with NFC support to provision your BoltRing
- The NFC UID of your BoltRing (printed on the leaflet that came with your BoltRing)

!!! tip "I don´t have an Android Phone!"
    You will only need the Android Phone for the initial setup of your BoltRing. So you could borrow
    an Android Phone from a friend to do the setup. Another option for iPhone users is the
    [CoinCorner Wallel](https://www.coincorner.com/). The CoinCorner App supports BoltCard setup on
    both Android and iPhone devices.

!!! tip "I don´t know the NFC UID of my BoltRing!"
    If you don´t know the UID of your BoltRing you can read it from the device at any time using an
    NFC enabled device and an app like NFC Tools. See
    [NFC Tools for Android](https://play.google.com/store/apps/details?id=com.wakdev.wdnfc) or
    [NFC Tools for iPhone](https://apps.apple.com/de/app/nfc-tools/id1252962749). The

## Step 1 - Create an LNBits Wallet

- Browse to https://legend.lnbits.com/
- Type a memorable name for your wallet
- Click "ADD A NEW WALLET"
- Take note of you Wallet-URL

!!! danger "Secure your Wallet-URL"
    The LNBits wallet you created does not have a password protected login. The **Wallet-URL** shown
    in the browser after creating the wallet IS YOUR PASSWORD/LOGIN. **So make a backup of the full
    Wallet-URL and keep it a secret**.

![LNBits Wallet-URL](images/lnbits-wallet-url.png)

## Step 2 - Fund your wallet

Click the `CREATE INVOICE` button and send some satoshis to your LNbits wallet.

## Step 3 - Install Extension

Activate the LNBits Bolt Card Extension for your wallet as follows:

- Click on `Manage Extensions` in the left menue
- Click `ENABLE` on the Bolt Cards tile
- Click `OPEN` or the new `Bolt Cards` item in the left menue

![LNBits Enable Bolt Cards Extension](images/lnbits-enable-bolt-card-extension.png)

## Step 4 - Create Bolt Card Service

- Click the orange plus-button on the Bolt Cards Extension screen

![LNBits Create Bolt Card](images/lnbits-create-bolt-card.png)

On the card creation form:

1. Select the wallet you created in [Step 1](#step-1-create-an-lnbits-wallet)
1. Set a limit of satoshis per transaction (for example 50000)
1. Set a limit of satoshis per day (for example 300000)
1. Type a memorable name for your BoltRing
1. Enter the NFC UID of your BoltRing
1. Click `Create Card`

![LNBits Bolt Card Form](images/lnbits-bolt-card-form.png)

## Step 5 - Provision your BoltRing

tbd
