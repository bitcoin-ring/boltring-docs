# BoltRing LNBits Setup

This guide shows you how to set up the BoltRing with [LNBits](https://lnbits.com/) and the Bolt Card
extension. LNBits is a free, open-source lightning account system.

!!! danger "Safety notice"
    In this guide, we use a public demo installation of LNbits, which means you must trust the
    service operators to guard your satoshis. **Don´t be reckless**; use it with caution and only
    for testing with small amounts.

## Step 0 - Requirements

- An existing Lightning Wallet that you can use to fund your LNBits account
- An Android Mobile Phone with NFC support to provision your BoltRing
- A BoltRing that has not been set up yet (or has been wiped)

!!! tip "I don´t have an Android Phone!"
    You will only need the Android Phone for the initial setup of your BoltRing. So you could borrow
    an Android Phone from a friend to do the setup. Another option for iPhone users is the
    [CoinCorner Wallet](https://www.coincorner.com/). The CoinCorner App supports BoltCard setup on
    both Android and iPhone devices.

## Step 1 - Install Bolt Card Creator

Install the
[Bolt Card creator app](https://play.google.com/store/apps/details?id=com.lightningnfcapp)

You will need this app later to write the bolt service configuration to the BoltRing. You will also
need the NFC UID of your BoltRing for this set-up. You can find it on the leaflet that came with
your BoltRing.

If you have your UID and are in a hurry, you can skip the next section and continue with step 2.

**Read BoltRing NFC UID**

1. Select the `Advanced` tab at the bottom of the start screen of the Bolt Card Creator App
1. Select the `Read NFC` tab on the stacked menu
1. Scan your BoltRing by holding it to the back of your phone
1. Take note of the UID of your BoltRing

!!! tip "Memorize the NFC antenna location"
    Smartphones have their NFC antenna in different places. Usually, it is in the upper third of the
    back of the phone. While scanning the BoltRing, pay attention to the position the app detects
    the BoltRing. Knowing the antenna position will give you more confidence when writing the
    configuration to the BoltRing later.

![Bold Card App read NFC](images/bolt-card-app-read-nfc.png)

## Step 2 - Create an LNBits Wallet

!!! tip "Do these steps from a PC"
    The guide assumes you create your LMBits wallet from a desktop PC.

- Browse to https://legend.lnbits.com/
- Type a memorable name for your wallet
- Click `ADD A NEW WALLET`
- Take note of your Wallet-URL

!!! danger "Secure your Wallet-URL"
    The LNBits wallet you created does not have a password-protected login. The **Wallet-URL** shown
    in the browser after completing the setup IS YOUR PASSWORD/LOGIN. **So please make a backup of
    the full Wallet-URL and keep it a secret**.

![LNBits Wallet-URL](images/lnbits-wallet-url.png)

## Step 3 - Fund your wallet

Click the `CREATE INVOICE` button and send some satoshis to your LNbits wallet.

## Step 4 - Install Extension

Activate the LNBits Bolt Card Extension for your wallet as follows:

- Click on `Manage Extensions` in the left menu
- Click `ENABLE` on the Bolt Cards tile
- Click `OPEN` or the new `Bolt Cards` item in the left menu

![LNBits Enable Bolt Cards Extension](images/lnbits-enable-bolt-card-extension.png)

## Step 5 - Create Bolt Card Service

- Click the orange `plus` button on the Bolt Cards Extension screen

![LNBits Create Bolt Card](images/lnbits-create-bolt-card.png)

On the card creation form:

1. Select the LNBits wallet you created before
1. Set a limit of satoshis per transaction (for example, 50000)
1. Set a limit of satoshis per day (for example, 300000)
1. Type a memorable name for your BoltRing
1. Enter the NFC UID of your BoltRing
1. Click `CREATE CARD`

![LNBits Bolt Card Form](images/lnbits-bolt-card-form.png)

After clicking `CREATE CARD`, you should see the card service created. Click the QR Code in the
first column of the listview to show the QR code you need in the next step.

![LNBits Bolt Card List](images/lnbits-bolt-card-list.png)

!!! noborder ""
    ![LNBits Bolt Card Create QR Code](images/lnbits-create-card-qr.png){ align=right width="40%"}
    After clicking the QR code symbol, you should see this card creation modal.

    **Make sure you back up the keys shown below the QR code.** You will need them to reset/wipe
    your BoltRing later. Should LNBits become unavailable, these keys will be the only way to
    recover/reset your BoltRing.

    Keep the modal window open; you will need to scan the shown QR code in the next step.

## Step 6 - BoltRing Setup

Go to your mobile phone and start the Bolt Card Creator APP you installed earlier. Place your
BoltRing on a table, so it is ready to be scanned.

!!! warning
    Please make sure you go through these last steps in one go, because the QR code from the
    previous step will be invalidated when you scan it. If you close the App before writing the data
    to the BoltRing, you must start over from [step 5](#step-5-create-bolt-card-service) and create
    a new card service entry.

1. Go to the start screen of the Bolt Card Creator app
1. On the start screen, tap `SCAN QR CODE` and scan the LNbits card creation QR code
1. Tap "WRITE CARD NOW" and position your phone´s NFC antenna close above the BoltRing
1. Verify that the app `Output` section shows all the green checkmarks

**Congratulations, your BoltRing is now ready for use.**

![Bolt Card App Write Card](images/bolt-card-app-write-card.png)
