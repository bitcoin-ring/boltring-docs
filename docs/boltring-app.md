# BoltRing App - Concept

!!! danger "Work in Progress"
    This document is work in progress and may change without notice. At the current time this
    concept of a BoltRing companion app is just that - **A Concept**. This document will be updated
    if/when we implement the concept.

## Introduction

The **BoltRing App** is a mobile application for Android and iOS. It is a companion app for the
BoltRing payment device. The goal of the app is to enable non-technical people to configure and use
the BoltRing. To drive adoption of contactless bitcoin lightning payments the user experience of
this app shall be as convenient, simple and polished as possible.

## BoltRing App Features

### Basic Features

- Connect the BoltRing with a BoltService
- Configure payment rules and other settings
- Track balance and send/receive payments
- Reset a BoltRing to factory defaults

### Special Features

- Import a pre-configured BoltRing
- Require PIN for certain payments
- Separate activation of Send/Receive/BalanceCheck
- Extended Payment Authorizaton Rules
- Push notifications for payments

## Hardware Requirements

Connecting a BoltRing with a BoltService requires an accessible NFC Chip on the mobile device. If
the device has no NFC-Chip it is possible to activate the Ring using another device and then import
the pre-configured BoltRing to the device without NFC support.

## BoltRing Activation

To activate the payment functionality of a BoltRing the following high level steps are required:

- Creation of an account on a BoltService
- Writing the Service URL and account keys to the NFC chip of the BoltRing

## User Experience

### Application Start

Starting the application shows a loader screen with the BoltRing Logo. Optionally a high quality
polished product photo of the BoltRing itself. Application start should be optimized to be as fast
as possible.

### Home Screen

### No BoltRing Connected

If no BoltRing has yet been connected, the app should first check the NFC status of the mobile
device. The following conditions may occur:

The device has no NFC Chip

- NFC chip detected but no permission
-

the Home Screen shows:

- A welcome message: “Welcome to your BoltRing”
- A button: “Connect BoltRing”

## Screen: Connect BoltRing

Allows user to connect his/her BoltRing with the BoltRing Wallet App.

The screen shows the following elements:

- Editable “NAME” field prefilled with a random name (“XYZ BoltRing”)
- An image showing the position of the NFC chip of the mobile phone
