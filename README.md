# Swap Electron GUI Wallet

### Introduction
Swap uses Cryptonote Privacy Blockchain + Cuckaroo29s (Proof of Work)

Stable Network | No Governance Fee | No Premine | No BS

More information on the project can be found on the [website](https://xwp.one) and in the [github](https://github.com/swap-dev/). Swap is an open source project, and totally driven by communities. We encourage people to offer PR to support a non-premine project. 
<p align="center">
 <img src="https://raw.githubusercontent.com/swap-dev/swap-electron-gui-wallet/v3.0.1/src-electron/icons/mrcuug.png" width="600">
</p>

### About this project

This is the new electron GUI for Swap. It is open source and completely free to use without restrictions, anyone may create an alternative implementation of the Swap Electron GUI that uses the protocol and network in a compatible manner.

#### Pre-requisites
- Download latest [swapd](https://github.com/swap-dev/swap/releases/latest)

#### Commands
```shell
nvm use 11.9.0
npm install -g quasar-cli
git clone https://github.com/swap-dev/swap-electron-gui-wallet
cd swap-electron-gui-wallet
cp path_to_swapd_binaries/swapd bin/
cp path_to_swapd_binaries/swap-wallet-rpc bin/
npm install
```

For building:

**Note:** This will only build the binaries for the system you run the command on. Running this command on `linux` will only make `linux` binaries, no `mac` or `windows` binaries.
```
npm run build
```
