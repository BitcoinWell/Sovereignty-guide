# Operational security

## Best practices for daily use

Operational Security (OPSEC) refers to the practices and protocols you employ to keep your Bitcoin secure in your day-to-day usage. Good OPSEC is just as important as secure wallet and backup setups.

Some OPSEC best practices:

* Device hygiene: Keep your Bitcoin-related devices free of malware and only use them for Bitcoin.
* Network security: Always use a secure network when transacting. Avoid public WiFi. Use Tor or a VPN if your threat model demands it.
* Physical security: Keep your hardware wallets and seed backups physically secure and hidden. Use a safe at home, safety deposit box, or hide them creatively.
* Information compartmentalization: Don't tell anyone more than they need to know about your Bitcoin holdings or setups. The best security is when no one knows you own Bitcoin at all.
* Discretion: Be careful about revealing that you own Bitcoin, especially significant amounts. This can make you a target for thieves or attackers.

Additional best practices for specific situations:

* Receiving Bitcoin: Always generate a new address for each transaction. Double check addresses before giving them out.
* Spending Bitcoin: Double check the destination address and amount before confirming a send. Use a wallet with coin control if you need to manage which UTXOs you're spending for privacy.
* Trading Bitcoin: Be extremely careful with exchange accounts. Only keep funds on exchanges that you're actively trading. Withdraw to your own wallet as soon as you're done trading.

The core mantra of OPSEC is "need to know". Always give out the minimum information necessary in any situation. The less known about your Bitcoin activities, the safer you'll be.

Personal recommendation: Cultivate a strong OPSEC mindset. Constantly ask yourself "Who can know what about my Bitcoin setup, and what's the minimum they need to know?". Apply this to every Bitcoin interaction.

## Physical security

Physical security refers to protecting your Bitcoin hardware and backups from physical theft or damage. This is a crucial and often overlooked aspect of Bitcoin security.

Some physical security best practices:

* Secure your hardware wallets: Keep your hardware wallets in a secure place when not in use, like a safe or a well-hidden spot in your home. Consider using a tamper-evident bag.
* Hide your seed phrases: Store your seed phrase backups in a different location from your hardware wallet. A safety deposit box or home safe are good options.
* Avoid attracting attention: Don't openly discuss your Bitcoin holdings, especially with strangers. Be discreet about any Bitcoin-related items you may have.
* Secure your workspace: If you have a dedicated area for Bitcoin activities, ensure it's private and secure. Use a room with a lock, and don't let others access your devices.
* Prepare for emergencies: Have a plan for how to secure (or quickly move) your Bitcoin hardware and backups in case of an emergency like a fire or natural disaster.
* Travel safely: If traveling with Bitcoin hardware, use a tamper-evident bag and keep it on your person or in a secure place like a hotel safe. Consider a "duress wallet" with a small balance in case of mugging.

Remember, in Bitcoin, possession largely equals ownership. If someone steals your hardware wallet or seed phrase backups, they can steal your Bitcoin. Physical security is a must.

Personal recommendation: Treat your Bitcoin hardware and backups like valuable jewelry or cash. Keep them hidden, keep them secure, and never let them out of your direct control.

## Digital security

Digital security refers to protecting your Bitcoin from online threats like malware, hackers, and phishing attacks. As Bitcoin is a purely digital asset, strong digital security is essential.

Some digital security best practices:

* Use dedicated devices: If possible, use devices dedicated only to Bitcoin. Don't use them for general web browsing or downloading apps.
* Keep software updated: Always keep your wallet software and device operating systems up-to-date with the latest security patches.
* Use strong passwords: Use long, unique passwords for all your Bitcoin-related accounts. A password manager can help with this.
* Enable 2FA: Turn on two-factor authentication (2FA) for any services that offer it, like exchanges. Use an app like Google Authenticator instead of SMS 2FA.
* Be careful what you click: Be extremely cautious about clicking links or downloading attachments, especially related to Bitcoin. Many scams try to trick you into revealing your private keys or seed phrases.
* Verify software signatures: When downloading Bitcoin wallet software, always verify the GPG signature to ensure it hasn't been tampered with.

Some more advanced digital security steps:

* Use a hardware wallet for any significant amount of Bitcoin.
* Run your software wallets on an operating system like Tails that runs from a USB stick and leaves no trace on the computer.
* Access Bitcoin related sites through Tor for added privacy.
* Use Linux instead of Windows or macOS on your Bitcoin devices.

The digital security threat landscape is constantly evolving. Stay informed about current threats and update your practices accordingly.

Personal recommendation: Invest in a hardware wallet as soon as you have more Bitcoin than you'd be comfortable carrying as cash. It's the single most important security step you can take.

## Protecting private keys

Your private keys are the most sensitive part of your Bitcoin setup. Anyone who gains access to them can steal your funds. Protecting them is paramount.

Some best practices for private key security:

* Never share your private keys: Your private keys should never be shared with anyone for any reason. The only exception is advanced multisig setups.
* Use hardware wallets: Hardware wallets keep your private keys secure in a dedicated device that is not connected to the internet. They are the most secure way to hold private keys.
* Secure your seed phrase: Your seed phrase is a human-readable backup of your private keys. Treat it like cash. Write it down and store it securely, never digitally.
* Use passphrases: Adding a passphrase to your wallet creates an additional layer of security beyond the seed phrase.
* Avoid address reuse: Reusing addresses can weaken the security of their private keys over time. Always generate a new address for receiving funds.

Be extremely cautious with any software or service that asks you to enter your private key or seed phrase. In most cases, this is not necessary and is a sign of a scam.

Personal recommendation: Consider your private keys and seed phrase to be as valuable as the Bitcoin they secure. Protect them accordingly.

### Two-Factor Authentication (2FA)

Two-Factor Authentication (2FA) is a security mechanism that requires two different methods to verify your identity. It usually involves something you know (like a password) and something you have (like your phone or a security key).

2FA is essential for any online account related to your Bitcoin, like exchanges or web wallets. It prevents an attacker from accessing your account with just your password.

Types of 2FA:

* SMS 2FA: You receive a text message with a code. This is better than no 2FA but is vulnerable to SIM swapping attacks.
* App-based 2FA: You use an app like Google Authenticator or Authy to generate codes. This is more secure than SMS.
* Hardware 2FA: A physical security key like a YubiKey is used to verify your identity. This is the most secure form of 2FA.

Best practices for 2FA:

* Enable 2FA on every account that offers it.
* Use app-based or hardware 2FA when possible
* Keep your 2FA device (phone or security key) physically secure.
* Configure a backup 2FA method in case you lose access to your primary one.
* For app-based 2FA, keep the backup codes in a secure place, like an encrypted password manager.

While 2FA doesn't directly protect your Bitcoin (that's what your hardware wallet is for), it's a crucial line of defense for any account that could give an attacker information about or access to your Bitcoin.

Personal recommendation: Use hardware 2FA like a YubiKey for your most important accounts, like your primary email and exchanges. It's a bit less convenient but significantly more secure.

### Avoiding common scams and phishing attacks

Scammers and phishing attackers often target Bitcoiners, as a successful attack can directly steal funds. Awareness and caution are your best defenses.

Some common Bitcoin scams:

* Phishing emails or messages: Attackers send messages purporting to be from a legitimate Bitcoin service, trying to trick you into revealing your login credentials or private keys.
* Malicious websites: Fake websites that mimic legitimate Bitcoin services, trying to steal login info or prompting you to enter your private keys.
* X/Telegram bots: Scam accounts on X or Telegram that impersonate well-known Bitcoiners and trick people into sending them bitcoin.
* Ponzi schemes: Scammers promising guaranteed high returns if you give them your Bitcoin to "invest". If it sounds too good to be true, it probably is.
* Malware: Malicious software that aims to steal your Bitcoin private keys or seed phrase when you enter them on your computer.

Some tips to avoid falling victim:

* Always double check the URL of any site asking for your Bitcoin information.
* Never enter your private keys or seed phrases into any website. No legitimate service will ever ask for this.
* Be extremely wary of any unsolicited messages about Bitcoin, especially if they pressure you to act fast or offer returns that seem too good to be true.
* Keep your computer secure and free of malware.
* Bookmark frequently used sites and use bookmarks rather than clicking links from messages.

In general, apply a high degree of skepticism to anything Bitcoin-related online, especially if it's unsolicited. Verify, verify, verify before taking any action.

Personal recommendation: The Bitcoin space attracts a high number of scammers because of the potential for high reward. Assume anything Bitcoin-related online is a scam until proven otherwise. Trust no one.

### Regular software updates and audits

The Bitcoin ecosystem is constantly evolving, with new software, upgrades, and best practices emerging regularly. Staying up-to-date and regularly auditing your setup is crucial for maintaining security.

Regular software updates:

* Keep your wallet software updated to the latest version. New versions often include important security patches.
* Keep your device's operating system and other software up-to-date as well.
* Subscribe to announcements from your wallet provider to be notified of important updates.

Regular audits:

* Periodically review your entire Bitcoin security setup. Check that you're following best practices and that your setup still meets your needs.
* Re-evaluate your backup and inheritance plan. Ensure they're still secure and that your designated heirs know what to do.
* Check your devices for malware and security issues.
* Review your physical security measures to ensure they're still adequate.
* Test your backups and disaster recovery plan to make sure they work as expected.

Conducting a comprehensive audit at least annually, or whenever there's a significant change in your setup or holdings, can help catch potential issues before they become problems.

Personal recommendation: Set a calendar reminder for your Bitcoin security audit, just as you would for a regular health checkup. Prevention is the best medicine.

### Physical security measures

In addition to the physical security of your hardware and backups, consider the physical security of your environment as well.

Home security measures:

* Install high-quality door locks and consider a home security system.
* Use a safe for storing Bitcoin hardware and backups at home. Look for a safe that is fireproof, waterproof, and securely anchored.
* Consider security cameras or motion detectors, especially covering the area where you keep your Bitcoin safe.
* Be discreet about your Bitcoin activities at home. Don't let service workers or visitors see your hardware or overhear sensitive conversations.

Personal security measures:

* Be cautious about revealing your Bitcoin holdings to others. This can make you a target for theft.
* When traveling with Bitcoin hardware, keep it in a tamper-evident bag on your person. Don't let it out of your direct control.
* In high-risk environments, consider carrying a "duress wallet" with a small balance to give up under threat, keeping your main wallet hidden.
* If faced with a physical threat, remember that your life and safety are more valuable than any amount of Bitcoin.

Remember, physical security threats to your Bitcoin can come from strangers or even people you know. The less others know about your Bitcoin holdings, the better.

Personal recommendation: A big part of physical security is keeping a low profile. The best way to prevent physical theft is to not make yourself an attractive target in the first place.

## Verifying cryptographic signatures

### Importance of verification

In the Bitcoin ecosystem, cryptographic signatures are used to verify the integrity of software downloads, messages, and transactions. Verifying these signatures is crucial for security.

When you download Bitcoin software, it will often be accompanied by a cryptographic signature. This signature verifies that the software has not been tampered with since it was signed by the developer. Verifying the signature ensures you're running the genuine software.

Similarly, messages or announcements from Bitcoin developers or organizations will often be signed. Verifying these signatures confirms the message really came from who it claims to be from.

Definition snippet:

* Digital Signature: A mathematical scheme for verifying the authenticity of digital messages or documents. It provides proof that the message was created by a known sender, and that the message was not altered in transit.

### Tools and methods

Verifying cryptographic signatures requires some technical know-how and the right tools. The exact process differs depending on what you're verifying.

For verifying software downloads:

1. Download the software and its signature file.
2. Get the developer's public key. This is usually available on their website or a key server.
3. Use a tool like GnuPG to verify the signature against the downloaded file and public key.

For verifying signed messages:

1. Get the message and its signature.
2. Obtain the signer's public key.
3. Use a tool like GnuPG to verify the signature against the message and public key.

Some Bitcoin wallets have built-in tools for verifying signed messages related to transactions.

Personal recommendation: Always verify signatures when downloading Bitcoin software. It's an extra step, but it's crucial for security. Make it a habit.

### Common pitfalls

Verifying signatures is a powerful security tool, but it's not foolproof. Some common pitfalls:

* Trusting the wrong public key: If you use the wrong public key to verify a signature, the verification will fail even if the signature is genuine. Always make sure you have the correct public key from a trusted source.
* Not checking key revocations: If a developer's private key is compromised, they may revoke their public key. Checking for revocations before verifying is important.
* Blindly trusting signed messages: A valid signature only means the message wasn't altered and came from the owner of the private key. It doesn't guarantee the signer is trustworthy. Always consider the reputation of the signer.
* Not verifying at all: The biggest pitfall is neglecting to verify signatures altogether. It's an important habit to build.

Remember, cryptographic signatures are a tool for verifying integrity and authenticity. They're a crucial part of a security toolkit, but not a guarantee of trustworthiness on their own.

Personal recommendation: If you're not comfortable verifying signatures yourself (it can be quite technical), only download software or follow instructions from sources you know and trust. Official websites or well-established community resources are usually a good bet.
