# Backup strategies

## Seed phrases

Your seed phrase is your master key to your bitcoin. It's a human-readable backup of your private keys. In most wallets, the seed phrase is a list of 12 or 24 words in a specific order.

If your wallet is lost, stolen, or damaged, you can recover your entire wallet and transaction history from the seed phrase. This is why securely backing up your seed phrase is the most important aspect of Bitcoin self-custody.

Definition snippet:

* Seed Phrase (Recovery Phrase): A list of words that are used to generate your wallet's private keys. Anyone with access to your seed phrase has control of your bitcoins.

When writing down your seed phrase, some best practices:

* Use a pen and paper, not a computer.
* Write neatly and double-check each word.
* Store the paper in a secure location like a fireproof safe or safety deposit box.
* Consider making multiple copies and storing them in different locations.
* Never store your seed phrase digitally, like in a phone note or cloud storage.

Personal recommendation: Write your seed phrase by hand on a piece of paper. Then stamp it into a piece of metal as a fire and flood resistant backup. Companies like Cryptosteel, Billfold, and Blockplate make metal backup devices for this purpose.

## Metal backups

While paper is a common way to backup a seed phrase, it's vulnerable to fire, flood, and general degradation over time. A more robust solution is to stamp, etch, or engrave your seed phrase into a piece of metal.

Metal is fireproof, waterproof, and much more durable than paper. It's an ideal medium for long-term seed phrase storage. When selecting a metal backup method, look for products that are:

* Made from corrosion-resistant metals like stainless steel or titanium.
* Easy to securely store and hide.
* Designed to prevent rearrangement of the words.

Several companies offer pre-made metal backup devices designed specifically for seed phrases. These are more expensive than DIY methods but are convenient and designed with seed phrases in mind.

Personal recommendation: If you're serious about Bitcoin self-custody, a metal seed phrase backup is a must. We recommend the Seedor, Seedplate or Stamp Seed.

## Redundancy and geographic distribution

When it comes to seed phrase backups, redundancy is key. One backup is good, but multiple backups are better. Some good ways to add redundancy:

* Make multiple metal backups and store them in different locations.
* Distribute parts of your seed phrase among trusted family members using Shamir's Secret Sharing or SeedXOR.

The idea is to balance security (protecting against theft and unauthorized access) with redundancy (protecting against loss or destruction).

Personal recommendation: Make at least three backups of your seed phrase. Store one in your home safe, one in a trusted party’s location, and distribute one using SeedXOR. This balances security and redundancy.

## Encrypted digital storage

While not recommended for primary backups, there are certain situations where you may want an encrypted digital backup of your seed phrase or wallet file. For example:

* A travel backup on an encrypted USB drive in case your main wallet is lost or stolen while abroad.
  * Hardware wallet’s, like the COLDCARD, offer this option.
* An emergency "dead man's switch" style backup with instructions on how to access.
* Storing an encrypted wallet file for a watch-only wallet.

If you do decide to store a seed phrase digitally, ensure it is heavily encrypted.&#x20;

Remember, an encrypted digital backup should supplement, not replace, your physical seed phrase backups. And never store an unencrypted seed phrase digitally!

Personal recommendation: In general, avoid storing seed phrases digitally. But if you do, use strong encryption and consider a database for key management. Always keep physical backups too.

## Inheritance planning

One of the key benefits of Bitcoin is that, like gold or cash, it can be directly passed on to heirs. However, if you don't plan for inheritance, your bitcoin can be lost forever when you die. Some steps to include bitcoin in your inheritance plan:

* Have a clear, written plan for your heirs on how to access your bitcoin. Include locations of seed phrases, hardware wallets, passphrases, etc.
* Consider a multi-signature setup with a trusted family member or your attorney, ensuring no one party can access the funds prematurely.
* Include Bitcoin in your will, with instructions on how your estate executor can distribute them.
* Have a "letter of intent" that clarifies what should happen to your bitcoin after you pass.
* Let your heirs know that you own bitcoin and how to find your instructions if something happens.

The key is to balance security (your heirs can't access the bitcoin prematurely) with clarity (they can access it when the time comes).

Personal recommendation: Work with an estate attorney who understands Bitcoin to include it in your will and estate plan. Have a clear plan written out, with instructions that are secure yet accessible to your heirs.

## Legal considerations

Bitcoin, despite being new technology, is covered by conventional estate law in most jurisdictions. Some legal considerations to keep in mind:

* Bitcoin is generally treated as property for tax and estate purposes. This means it's subject to capital gains tax and should be included in your estate valuation.
* If you hold your own private keys, bitcoin is treated as a bearer asset like gold or cash. Whoever holds the keys is considered the owner.
* Properly documenting your bitcoin holdings and including them in your will can help ensure they're correctly distributed to your heirs.
* Privacy and discretion are important. You don't necessarily want your bitcoin holdings to become public record through probate.
* Laws and regulations around bitcoin are still evolving. Stay informed and work with professionals who understand the space.

Remember, Bitcoin is still a new frontier when it comes to law and regulation. But with proper planning, you can ensure your bitcoin wealth is preserved and passed on according to your wishes.

Personal recommendation: Don't assume your heirs will know how to handle your bitcoin. Provide clear, detailed instructions and consider working with a professional who understands Bitcoin estate planning.

## Recovery methods

### Restoring from seed phrases

If your wallet is lost, damaged, or stolen, you can recover your funds by importing your seed phrase into a new wallet. The general process:

1. Install the same wallet software you were using on a new device. If your original wallet is no longer available, choose a wallet that is compatible with your seed phrase. Generally speaking, your seed phrase should be compatible with most wallet software.&#x20;
2. Look for an option to "Restore from backup" or "Import seed."
3. Carefully enter your seed phrase, double checking each word.
4. If you used a passphrase, you'll need to enter that as well.
5. Your wallet will regenerate your addresses and transaction history from the seed. This may take some time.
6. Once the process is complete, you should see your bitcoin balance and transaction history restored.

It's crucial to test your seed phrase backup before you need it. Recover a small amount first to a new device to ensure the process works before relying on it for larger amounts.

Personal recommendation: Regularly verify your backups by recovering from your seed to a new wallet. This ensures your seed is correctly written and the restoration process works as expected.

### Dealing with lost or damaged hardware wallets

If your hardware wallet or device with your bitcoin wallet is lost or damaged, don't panic. As long as you have your seed phrase, your funds are safe and recoverable.

For lost or stolen hardware wallet devices:

If your device is stolen, you can recover your funds with the seed phrase, as long as the thief hasn’t spent them. This is why a paraphrase can be useful.&#x20;

Instead of simply recovering your wallet, you’ll want to move your coins to a new wallet. This is called a “sweep”.&#x20;

A "sweep" is the process of transferring all the funds from one wallet to another, typically after recovery or if you want to move assets for security reasons. Unlike a regular transaction, where individual coins are sent, a sweep moves the entire balance in a single action, ensuring that all funds are transferred to the new wallet without leaving any behind.

1. Immediately “sweep” your funds to a new wallet using your seed phrase backup. This moves the funds to new addresses, invalidating the old private keys.
2. If your device had a PIN or password, consider those compromised. Generate a new seed on a new device.

For damaged devices:

1. Use one of your backups to restore your wallet on a new device.
2. As a precaution, consider sweeping the funds to a newly generated wallet once restored.

The key is to act quickly if a device is lost or stolen. The faster you move your funds to a new wallet, the lower the risk of theft.

Personal recommendation: Keep your devices physically secure to prevent theft or damage. But always be prepared to recover from your seed phrase in case the worst happens. Regular practice recoveries can help you stay prepared.

### Emergency recovery procedures

In addition to regular backups and recovery methods, it's wise to have a plan for emergency situations. This could be sudden incapacitation, unexpected travel, or a major natural disaster.

Some elements to consider in an emergency plan:

* A "break glass" encrypted backup of your seed phrases and important wallet info stored with a trusted person or in a secure remote location.
* Instructions for family on how to access your bitcoin in an emergency, including locations of seed phrases, passphrases, and hardware wallets.
* A "duress wallet" that holds a small amount of funds, in case you are ever forced to reveal a wallet under duress.
  * The COLDCARD trick PIN feature allows you to create a duress wallet, which, when triggered, will display as if the main PIN was entered, but only grants access to a wallet with limited funds. This is useful for protecting your main assets in the event of coercion.&#x20;
* Redundant hardware wallets in secure locations that can be quickly accessed if your primary is lost or unavailable.
* An "emergency contact" who knows about your Bitcoin setup and can help family access if needed.

The goal is to have a clear plan of action that can be executed quickly in a high stress situation. It should balance accessibility with security.

Personal recommendation: Write out your emergency plan and review it quarterly. Make sure key family members know it exists and how to execute it, but keep the specifics secure and compartmentalized.
