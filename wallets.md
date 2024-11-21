# Wallets

## Software wallets

Software wallets are programs you install on your computer or smartphone that allow you to send, receive, and store bitcoin. They're a good choice for smaller amounts or day-to-day spending.

### Mobile wallets

Mobile wallets turn your phone into a Bitcoin bank in your pocket. They're convenient for transactions on-the-go and often have features like QR code scanning. Some popular options:

* BlueWallet (iOS/Android): An easy to use wallet.
* Blockstream Green (iOS/Android): Multisig capable wallet from Blockstream.
* Zeus Wallet (iOS/Android): Privacy-focused with direct node connection.

Personal recommendation: Enable biometric or password unlock on your mobile wallet for added security. Even if your phone is unlocked, the app will still require authentication.

### Desktop wallets

Desktop wallets run on your computer and often have more advanced features than mobile wallets. Some good choices:

* Sparrow Wallet (Win/Mac/Linux): A full featured wallet with hardware wallet & multisig support.
* Electrum (Win/Mac/Linux): One of the original Bitcoin wallets, Electrum is feature-rich and actively developed.
* Nunchuk (iOS/Android/Win/Mac/Linux): A multisig wallet with collaborative features and hardware wallet support.
* Bitcoin Core (Win/Mac/Linux): The original Bitcoin client, offering full node capabilities for maximum security and privacy.

Personal recommendation: When setting up a desktop wallet, write down your seed phrase and store it securely. Encrypt your wallet file with a strong password for added protection.

### Hardware wallets

Hardware wallets are physical devices that secure your private keys in a dedicated security chip. They offer the best balance of security and ease-of-use for long-term storage of larger Bitcoin amounts.

**Popular options**

* Ledger (Nano S Plus / Nano X): Ledger devices feature a secure element chip and support a wide range of crypto assets. The Nano X has Bluetooth for mobile connectivity.
* Trezor (One / Model T): Trezor was the first widely available hardware wallet. The Model T features a color touchscreen and microSD card slot.
* Coldcard: Coldcard is a Bitcoin-only hardware wallet with a focus on security and advanced features like PSBT and multisig.
* Passport: Passport is a Bitcoin-only hardware wallet with a focus on security and ease of use, featuring a secure air-gapped design and support for multisig setups.
* Jade: Jade is a hardware wallet from Blockstream, designed for secure Bitcoin storage and fully integrated with Blockstream Green, supporting multisig and hardware wallet features.
* Seedsigner: Seedsigner is an open-source, air-gapped hardware wallet designed for securely generating and signing Bitcoin transactions, with a focus on privacy and self-custody.

Personal recommendation: Focus on a hardware wallet that only caters to Bitcoin and that can be operated without connecting it to your computer. This helps reduce potential vulnerabilities.

## Setup and usage

Setting up a hardware wallet involves following the manufacturer's instructions to generate your seed phrase and configure a PIN. In some cases, the process may also include dice rolls to help create a secure and random seed phrase. Once set up, you use the hardware wallet by connecting it to your computer or phone and approving transactions on the device. This connection can be done directly or indirectly, through the use of a microSD card.

Personal recommendation: When first setting up a hardware wallet, go through the process of sending a small test transaction. Wipe the device and restore it from the seed phrase to ensure your backup is correct before trusting it with larger amounts.

### Paper wallets

Paper wallets are a low-tech option where your Bitcoin private key is printed out onto paper. They were popular in the early days of Bitcoin but have fallen out of favor due to their fragility and the rise of hardware wallets.

Paper wallets are highly secure against online attacks, but vulnerable to physical damage and degradation over time. They're also not convenient for actually using bitcoin, as the entire balance must be swept when importing the key.

A printer can also potentially be compromised, putting your bitcoin at risk.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeUcWS752XXD_QNxx5g2AbXozsBEE78pcP8ez_3BemHLg1Y7HGeMrQM3r8mdyXOQgPZUUk3nhnOhzGT61PuJN58Ac16gwPx7F8WhxUMresNEbjcQuecCdYpjvFrFRYyMe6zNY7tTQ?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption><p>Example of a paper wallet.</p></figcaption></figure>

### Multisignature wallets

Multisignature (multisig) wallets require more than one key to authorize a transaction. This allows for shared control over funds, increased security, and advanced backup options.

With a multisig setup, you can have a 2-of-3 scheme where any 2 of the 3 keys can sign, a 3-of-5 scheme where any 3 of the 5 can sign, and so on. The keys can be spread across multiple devices, locations, and even holders for maximum resilience and security, obviously at the cost of convenience.

**Some common multisig use cases:**

* Spouse/Partner access: A 2-of-3 setup with keys held by you, your spouse, and a third-party service. If anything happens to you, your spouse and the service can recover the funds.
* Business funds: Multisig can require any 2 of the 3 company officers to sign for a spend, preventing unauthorized transfers.
* Advanced inheritance: Each heir can be given a key, with your lawyer holding the additional required key. Funds unlock when your estate is settled.

Multisig does come with added complexity in setup, backup, and transaction signing flows. It's recommended for more advanced users.

Personal recommendation: For a personal multisig setup, consider using multiple hardware wallets from different manufacturers with keys generated offline. Make sure that you distribute your backups for an effective storage solution.

### Lightning Network wallets

The Lightning Network is a "layer 2" payment protocol that enables fast, cheap, scalable bitcoin transactions. The Lightning Network allows you to send small amounts of bitcoin instantly for minimal fees.

To use the Lightning Network, you need a wallet that can open Lightning channels. Some good options:

* Phoenix Wallet (iOS/Android): A user-friendly, non-custodial Lightning wallet.
* Wallet of Satoshi, Blink or CoinOS: Custodial Lightning wallets with a focus on easy onboarding and use.
* Electrum (Desktop): A wallet for those that want to connect to their own node and would like to use more advanced configurations.

Personal recommendation: Before putting significant funds into Lightning channels, make sure you understand concepts like channel capacity and liquidity. Start with small amounts while learning.

## Custodial vs. non-custodial wallets

An important distinction to understand when choosing a wallet is custodial (hosted) vs. non-custodial (self-hosted).

Custodial wallets are designed to be a third-party (like an exchange) that holds your private keys. It's like a bank—convenient, but you have to trust the custodian. Examples include leaving coins on an exchange or using a service like Cash App or Wealthsimple.

Non-custodial wallets are designed to give you control of the keys. This can be a hardware wallet (like those mentioned above), desktop wallet, or non-custodial mobile wallet. These give you full sovereignty over your coins.

**Definition snippet:**

* Non-Custodial Wallet: A wallet where you control the private keys. The keys, and therefore the bitcoins, are fully under your control.

Personal recommendation: Always self-custody your bitcoin in a non-custodial wallet. Custodial solutions are for small amounts or coins actively being used. Remember: "Not your keys, not your coins."
