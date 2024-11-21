# Advanced topics

## Multisig setups for businesses

Businesses holding significant Bitcoin have unique security needs. Multi-signature (multisig) setups are often the right solution.

In a multisig setup, more than one key (from different people or devices) is required to move funds. This provides several benefits for businesses:

* Theft Prevention: No single person can run off with the company's Bitcoin.
* Error Prevention: Multisig prevents accidental loss from one person losing a key or making an error.
* Shared Responsibility: Financial controls can be split between different roles, like the CEO, CFO, and board.
* Continuity: If a keyholder leaves the company or becomes unavailable, the funds are not lost.

Some common business multisig setups:

* 2-of-3: Two of three designated keyholders must sign to move funds. Good for small businesses.
* 3-of-5: Three of five keyholders must sign. Better for larger businesses with more roles.

Multisig can be set up using hardware wallets, where each signer has their own device. For even higher security, dedicated multisig hardware devices or secure key storage services can be used.

Personal recommendation: For businesses, I recommend a 2-of-3 setup at minimum, with keys held by different individuals in different roles (not all executives). Use hardware devices from different manufacturers for each key.

## Cold storage solutions for large holdings

For large, long-term Bitcoin holdings, cold storage is the most secure option. Cold storage means keeping the keys entirely offline, never exposing them to an internet-connected device.

Some cold storage solutions suitable for large holdings:

* Hardware wallets in secure locations: Store hardware wallets, each holding a portion of the funds, in multiple secure locations.
* Multisig with geographic distribution: Set up multisig where the keys are held in different physical locations for added resilience.

With cold storage, it's crucial to have robust backup and inheritance plans. If keys are lost, the funds are likely gone forever.

Personal recommendation: For truly large holdings, consider a hybrid approach with a multisig setup where some keys are in cold storage and others are more accessible. This balances security and convenience.

## Bitcoin Core integration

Bitcoin Core is the reference implementation of the Bitcoin protocol. It's the most scrutinized, secure, and feature-rich Bitcoin software available.

Integrating Bitcoin Core into your setup can provide several benefits:

* Validation: Bitcoin Core fully validates all transactions and blocks, providing the highest level of security and rule enforcement.
* Privacy: By default, Bitcoin Core does not share address information with peers, enhancing on-chain privacy.
* Compatibility: Bitcoin Core is compatible with a wide range of wallets and services, making it a versatile backbone for your setup.
* Feature Support: Bitcoin Core supports advanced features like multisig, hardware wallet integration, and coin control.

To integrate Bitcoin Core:

1. Install Bitcoin Core on a secure machine (can be a dedicated device or a general-purpose computer).
2. Sync the full blockchain (this can take several days).
3. Enable the wallet functionality if you want to use Bitcoin Core as a wallet.
4. Configure your other wallets and services to connect to your Bitcoin Core node.

Keep in mind that running Bitcoin Core requires a significant amount of disk space (over 400GB as of 2023) and bandwidth. It's a commitment, but one that provides significant benefits.

Personal recommendation: If you're technically inclined and have the resources, running your own Bitcoin Core node is one of the best things you can do for your sovereignty and privacy. Point your wallets to it and enjoy the benefits of fully validating your own transactions.
