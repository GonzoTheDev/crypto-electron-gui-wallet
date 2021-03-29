# Crypto Electron GUI Wallet

![Logo](https://raw.githubusercontent.com/GonzoTheDev/cryptocoin-gui/master/images/appicons/256x256.png)

### CryptoCoin Introduction

Copyright (c) 2021 The CryptoCoin Project.   
Crypto is based on [Monero](README_original.md) and is forked from [Swap](https://github.com/swap-dev/swap).

![Build-Linux](https://github.com/swap-dev/swap/workflows/Build-Linux/badge.svg)

More information on the project can be found on the [website](https://crypt-o-coin.cash) and in the [github](https://github.com/GonzoTheDev/). Cryptocoin is an open source project, and totally driven by communities. We encourage people to offer PR to support a non-premine project. 


### About this project

This is the new electron GUI for Cryptocoin. It is open source and completely free to use without restrictions, anyone may create an alternative implementation of the Cryptocoin Electron GUI that uses the protocol and network in a compatible manner.

#### Pre-requisites
- Download latest [cryptocoind](https://github.com/GonzoTheDev/crypto/releases/latest)

#### Commands
```shell
nvm use 14
npm install -g quasar-cli
git clone https://github.com/GonzoTheDev/crypto-electron-gui-wallet
cd crypto-electron-gui-wallet
cp path_to_cryptocoind_binaries/cryptocoind bin/
cp path_to_cryptocoind_binaries/cryptocoin-wallet-rpc bin/
npm install
```

For building:

**Note:** This will only build the binaries for the system you run the command on. Running this command on `linux` will only make `linux` binaries, no `mac` or `windows` binaries.
```
npm run build
```
