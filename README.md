# Zap Android

[![Screenshot of Zap Android app](docs/screenshot.png)](https://zaphq.io/)

Native android lightning wallet for node operators focused on user experience and ease of use ⚡️

Zap Android is not a classical wallet, it is actually a remote control for one or more of your LND Nodes. Zap Android aims to give node operators the opportunity to use their node in everyday situations with a simple and appealing user interface.

The easiest way to get started is using [Umbrel](https://getumbrel.com/) to run LND on a raspberry pi and then connect Zap Android to that node.

## Features

**Wallet**
- [x] Manage multiple wallets/nodes
- [x] Contacts
- [x] Fiat currency prices
- [x] Support for Bech32 and P2SH addresses
- [x] BTC, mBTC, bit & Satoshi units
- [x] Open `lightning:` & `bitcoin:` urls
- [x] Available in many languages
- [x] LNURL support (pay, withdraw & channel)
- [x] Send funds without an invoice (keysend)
- [x] Transaction filter
- [x] Read NFC tags
- [x] [Avatars](https://github.com/michaelWuensch/avathor-rfc#avathor) 
- [x] Bitcoin only, no shitcoins!

**Security & Privacy**
- [x] Non-custodial
- [x] Tor support
- [x] PIN protected access
- [x] Scrambled PIN by default
- [x] Protection against screen recording
- [x] Option to hide total balance
- [x] User guardian system (Zap warns users when they are about to perform potentially dangerous or privacy leaking actions)
- [x] [Reproducible build](https://walletscrutiny.com/android/zapsolutions.zap/)

**Lightning**
- [x] Channel Management
- [x] Connect to remote Lnd node
- [x] Connect to BTCPay Server
- [x] Connect to lndconnect QR code

## Security

If you discover or learn about a potential error, weakness, or threat that can compromise the security of Zap, we ask you to keep it confidential and [submit your concern directly to the Zap security team](mailto:jimmymowschess@gmail.com?subject=[GitHub]%20Zap%20Security).

## Non-custodial

Zap Android is fully non-custodial. When using the app there is absolutely no interaction with any Zap team or service. We do not even know you are using our software.

## Get Help

If you are having problems with Zap, please report the issue in [GitHub][issues] or on [slack][slack] with screenshots and/or how to reproduce the bug/error.

A good product not only has good software tests but also checks the quality of the UX/UI. Putting ourselves in the shoes of a user is a very important design principle of Zap.

## Contribute

Hey! Do you like Zap? Awesome! We could actually really use your help!

Open source isn't just writing code. Zap could use your help with any of the following:

- [Translating](docs/TRANSLATING.md) the app
- Finding (and reporting!) bugs
- New feature suggestions
- Answering questions on issues
- Documentation improvements
- Reviewing pull requests
- Helping to manage issue priorities
- Fixing bugs/new features

If any of that sounds cool to you, feel free to dive in! [Open an issue][issues] or submit a pull request.

If you would like to help contribute to the project, please see the [Contributing Guide](docs/CONTRIBUTING.md)

If you want to setup a testing environment, please see the [Regtest Guide](docs/REGTEST.md)

And if you want to build the app yourself take a look at the [Installation Guide](docs/INSTALL.md)

## Maintainers
- [Michael Wünsch](https://github.com/michaelWuensch)

## License

This project is open source under the MIT license, which means you have full access to the source code and can modify it to fit your own needs. See [LICENSE](LICENSE) for more information.

[MIT](LICENSE) © Jack Mallers

[issues]: https://github.com/LN-Zap/zap-android/issues
[slack]: https://join.slack.com/t/zaphq/shared_invite/enQtMzgyNDA2NDI2Nzg0LTQwZWQ2ZWEzOWFhMjRiNWZkZWMwYTA4MzA5NzhjMDNhNTM5YzliNDA4MmZkZWZkZTFmODM4ODJkYzU3YmI3ZmI
