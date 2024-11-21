# Setting up your first wallet

Here's a quick start guide for setting up your first bitcoin wallet:

1. Choose a non-custodial wallet: Download a wallet like BlueWallet on your phone or Sparrow Wallet on your computer.
2. Install the app and create a new wallet: Be sure to select the option to create a new wallet rather than importing an existing one.
3. Write down your seed phrase: This is the most important step! Write down the 12-24 words the wallet gives you and store them securely. This is your master backup.
4. Send a small test transaction: Before putting large amounts in your wallet, send a small test amount to ensure everything is working correctly.
5. Backup your wallet: In addition to your seed phrase, consider making an encrypted backup of your wallet file if your wallet supports it.

Congratulations, you now have a basic Bitcoin wallet set up! Remember to keep your seed phrase secure, as anyone who gains access to it can steal your funds.

Personal recommendation: As you grow your Bitcoin holdings, graduate to a hardware wallet. They're the most secure option for long-term storage.

## Wallet configurations

### Single-signature setups

A single-signature wallet is the simplest and most common type of bitcoin wallet. It uses one private key to control the funds. If you lose that key (and don't have your seed phrase), your bitcoins are lost forever.

Single-sig wallets are a good choice for personal use and smaller holdings. They're easy to set up and use but come with the risk of a single point of failure.

Personal recommendation: Even with a single-sig wallet, practice good security. Encrypt your wallet file, backup your seed phrase, and consider using passphrase protection (see below).

#### Passphrase protection

Many wallets offer the ability to add an additional passphrase (sometimes called a "13th or 25th word") to your seed phrase. This passphrase acts as an extra layer of security.

With passphrase protection, someone would need both your seed phrase and your passphrase to gain access to your funds. It also allows you to create "hidden" wallets. Each unique passphrase generates a completely different wallet. This adds an additional level of security, as even if someone gains access to your seed phrase, they cannot access your funds without the correct passphrase. Furthermore, it provides flexibility in managing multiple wallets without needing to generate new seed phrases.

Passphrases should be strong, with upper and lower case letters, numbers, and symbols. And, of course, never store your passphrase with your seed phrase.

Personal recommendation: Passphrase protection is a cheap and easy way to level up your wallet security. We recommend it for all but the smallest wallets. Just don't forget your passphrase!

#### Multisignature setups

As discussed in the [Wallets section](wallets.md), multisig setups require multiple keys to spend funds. This can be a 2-of-2, 2-of-3, 3-of-5, or any other m-of-n scheme.

Multisig is powerful because it allows for redundancy and shared control. No single person or device can unilaterally spend the funds. Some advanced multisig setups include:

* Distributed Backups: Store one key with a service like Casa or Unchained Capital, one key on a hardware wallet, and give one to a trusted family member. Any 2 can recover funds.
* Business Accounts: Require 2-of-3 between the CEO, CFO, and company lawyer for large transactions.
* Advanced Inheritance: Give each heir a key, require 3 of 5 to spend. Include a dead man's switch service as one of the signers.

Multisig does come with added costs and complexities. It requires careful key management and coordination to spend. But for large holdings or crucial funds, it provides peace of mind.

Personal recommendation: If you're holding life-changing money in bitcoin, multisig is a must. The redundancy and spending controls are well worth the setup costs and effort.

Warning! Recovering funds from a multisignature wallet requires you to have enough devices or backups to form a quorum, as well as the Master XPUB. If you miss any of these elements, you won’t be able to recover your bitcoin.&#x20;

#### Hierarchical deterministic (HD) wallets

Most modern wallets are hierarchical deterministic (HD) wallets. HD wallets generate a tree structure of keys from a single seed phrase, rather than just a single key pair.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd2qs9VX2nfLkj8i0u9Om1oGWrp1xCEYIUlNt49ON8e6ONrVsDZYsri_WQ7gF-rc8qLKxoLYTHAJA6-6MKEUghcvwW_A5dzNsh4efYi3doMbSBlh-f-q3QeLheVmvUt5ap3zMzc?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption><p>Branches of keys generated from a unique seed.</p></figcaption></figure>

The practical benefit of HD wallets is that they can generate a nearly infinite number of addresses from the same seed phrase. This is useful for privacy (using a new address for each transaction) and organization (separate addresses for separate purposes or accounts).

HD wallets also allow for more efficient backups. Since all addresses are generated from the seed phrase, you only need to backup the seed once.

Personal recommendation: If your wallet supports it, take advantage of the HD structure by using a new receiving address for each transaction. This makes your transaction history more private and doesn’t add any additional complexity or nuance when spending bitcoin later on.

#### Wallet interoperability standards

To ensure wallets can communicate and funds can be recovered across different wallet software, there are some key interoperability standards to be aware of:

* BIP39: The standard for generating seed phrases from a list of 2048 words. Most wallets use BIP39.
* BIP32: The specification for hierarchical deterministic (HD) wallets.
* BIP44: Defines a logical hierarchy for deterministic wallets, with different address paths for each coin type.
* PSBT: Partially Signed Bitcoin Transactions, a standard format for unsigned multisig transactions.

When setting up a wallet or recovering funds, ensuring it follows these standards will make the process much smoother. All of the wallets we have mentioned follow these standards.&#x20;

Personal recommendation: When choosing a wallet, look for one that adheres to BIPs 39, 32, and 44 at a minimum. This will ensure you can recover your wallet with a different software if needed.

#### Recommendations for different user types

* Bitcoin Beginners: Start with a user-friendly mobile wallet like BlueWallet or Blockstream Green. Write down your seed phrase and store it securely.
* HODLers: Graduate to a hardware wallet like a Passport or Coldcard for long-term storage. Consider a passphrase or multisig for large amounts.
* Businesses: Use a dedicated wallet with multisig functionality. Require multiple signers for large transactions. Have a clear backup and disaster recovery plan.
* Privacy Focused: Practice good UTXO management and consider Coinjoining. More on this in the Privacy section.
* Lightning Users: Use a non-custodial Lightning wallet like Phoenix or Bitkit for fast, cheap transactions. Remember to backup your channels.

The best wallet for you will depend on your unique situation, but in general, look for active development, adherence to standards, and open-source code that has been audited.

Personal recommendation: Don't get paralyzed by all the wallet choices. Start with a basic setup, and as you learn and grow, you can always migrate to a more advanced wallet. The important thing is to begin practicing self-custody.
