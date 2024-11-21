# Self-custody fundamentals

## Importance of self-custody

The ethos of Bitcoin is rooted in financial sovereignty—the idea that you should have full control over your money. When you leave your coins on an exchange or with a custodian, you're essentially trusting them with your wealth. History has shown, with catastrophes around the world like Mt. Gox 🇯🇵, Quadriga 🇨🇦 and FTX 🇺🇸 that this trust is often misplaced[^1].

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXduC07Fz5OfVRuiGTWuVouqcf1zLaMCdaceAAtIk6W3LzkcV86nChCHktteDtsGkBcWcK2WNsy9991EXbFj_1u0yfrjQD5dQLa-JBjzxTdpZqiyph-kgrARjVDlJ3e5S3_GbdS4Dw?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption></figcaption></figure>

Self-custody—where you hold your own private keys—is the only way to truly use Bitcoin as intended. It's the difference between your coins being an IOU and being actual bitcoins that you control entirely.

#### Definition snippet:

* Private Key: A secret number that allows bitcoins to be spent. If you don't control the private keys, you don't really control the coins.

## Risks and responsibilities

With the power of self-custody comes great responsibility. When you hold your own keys, there's no customer support to call if you lose your backup or send funds to the wrong address. It's crucial to understand these risks:

* Loss/theft of private keys: If your private keys are lost or stolen, your bitcoin can be taken and likely never recovered[^2].
* Inheritance: If you pass away or become incapacitated without a proper inheritance plan, your bitcoins could be lost forever.
* User error: Accidentally sending funds to the wrong address, falling for a scam, or improperly backing up your wallet can lead to irrecoverable losses.

Personal recommendation: Treat bitcoin self-custody with the respect it deserves. Educate yourself, start small, and don't cut corners on security. Every large holder started with a small amount, and your small amount could likely become a large holding in the future.

## Basic security principles

While later sections will dive deep into security practices, some basic principles apply to all self-custody setups:

* Backup your seed phrase: Write down your 12-24 word seed phrase and store it securely. This is your master backup.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeCS8vpe986uLckW7pjLU75SdQur5UTi-dTYl5xZua6XbhNqTbCML2c3Pg1AFQ5RnpfyO0K_qKLsQU9yCABD5m0A24ZAKfx5_-Oo1DCbsn0QYWESvC5dz1sYsypzKoepQOOG-6q1Q?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption></figcaption></figure>

Example of a 24-word seed phrase.

* Use hardware wallets for large amounts: Hardware wallets are the most secure way to store large Bitcoin holdings.
* Enable 2FA: Turn on two-factor authentication everywhere it's offered, using an app like Google Authenticator rather than SMS.
* Keep software updated: Always keep your wallet software and firmware updated to patch any security holes.
* Verify addresses: When sending bitcoin, always carefully check the "send to" address to avoid errors.

By keeping these basic principles in mind as we work through this guide, you'll build a strong foundation for your self-custody journey.

#### Historical context snippet:

* In 2014, Mt. Gox, one of the only and largest Bitcoin exchanges at the time, suffered a major security breach resulting in the loss of 850,000 BTC due to vulnerabilities in its security infrastructure. This incident underscored the risks of inadequate security practices in handling large amounts of bitcoin and the irreversible nature of bitcoin transactions, leading to increased awareness about self-custody and robust security protocols.

#### Advanced inheritance and redundancy using SeedXOR

To secure large holdings, consider using SeedXOR for redundancy. SeedXOR allows you to split your seed phrase into multiple parts that can later be combined to reconstruct the original seed. This offers an alternative to traditional backups by dispersing risk across multiple secure locations.

Setting Up SeedXOR:

* Step 1: Use a compatible tool (e.g., Coldcard or Passport) to generate XOR parts.
* Step 2: Create a set number of parts (e.g., 2 of 3) to allow flexibility in recovery.
* Step 3: Distribute each part in a separate, secure location (e.g., one in a home safe, one with a trusted family member, and one with your lawyer).

Example: A 2-of-3 SeedXOR setup allows any two shares to reconstruct the original seed, protecting your Bitcoin from loss if one location becomes compromised while preserving recovery options for heirs.

[^1]: &#x20;List of Major Bitcoin heists: [https://bitcointalk.org/index.php?topic=576337](https://bitcointalk.org/index.php?topic=576337)

[^2]: Physical bitcoin attacks: [https://github.com/jlopp/physical-bitcoin-attacks](https://github.com/jlopp/physical-bitcoin-attacks)
