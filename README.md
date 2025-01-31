# WalletConnect v1.x.x

## Introduction

WalletConnect is an open protocol to communicate securely between Wallets and Dapps \(Web3 Apps\). The protocol establishes a remote connection between two apps and/or devices using a Bridge server to relay payloads. These payloads are symmetrically encrypted through a shared key between the two peers. The connection is initiated by one peer displaying a QR Code or deep link with a standard WalletConnect URI and is established when the counter-party approves this connection request. It also includes an optional Push server to allow Native applications to notify the user of incoming payloads for established connections.

## Getting Started

Currently the WalletConnect protocol has references implementations written in Typescript for the Client, the Bridge Server and the Push server.

To quickly setup for your Dapp or Wallet, go to [Quick Start](https://github.com/WalletConnect/walletconnect-docs/tree/4665484efb48d649211b3afa7e6a38eac4f3d104/quick-start/README.md) for code examples.

To read in more detail about the WalletConnect protocol, go to [Technical Specification](tech-spec.md)

Additionally you can also consult the API references for [Client](client-api.md), [Bridge Server](bridge-server.md) and [Push Server](push-server.md)

## Useful Links

**Test Wallet:** [test.walletconnect.org](https://test.walletconnect.org) \([Source code](https://github.com/WalletConnect/walletconnect-test-wallet)\)

![test wallet](.gitbook/assets/img_3394.jpg)

**Example Dapp:** [example.walletconnect.org](https://example.walletconnect.org) \([Source code](https://github.com/WalletConnect/walletconnect-example-dapp)\)

![example dapp](.gitbook/assets/screenshot-2019-01-31-16.52.57.png)

## Community

Share your experience, contribute or ask questions with the WalletConnect Community

- Github: [https://github.walletconnect.org](https://github.walletconnect.org)
- Discord: [https://discord.walletconnect.org](https://discord.walletconnect.org)
- Twitter: [https://twitter.walletconnect.org](https://twitter.walletconnect.org)
