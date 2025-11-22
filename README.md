# Aeon Secure Suite

Offline, single-file encryption toolkit (messages, files, and vaults) plus MicroVault v1.9, a lightweight air-gapped file vault.

## Verification (SHA-256)

Aeon_Secure_Suite_v4.4.html  
`d3ea3b4da50f42fb12302dbea3d964ca9a850ef8bd3ee2c900713b47e73d8be5`

Aeon_MicroVault_v1.9.html  
`798e6858b8847a87fb908e36331b3c83ed04d60803af0906c6c81b4d31c18427`

## What this is

- A pair of single-file tools you download and run locally in your browser.
- Aeon v4.4: encrypts messages, files, and simple vault entries fully offline.
- MicroVault v1.9: a small, air-gapped-friendly file vault for bundling files into one encrypted JSON.
- Uses standard Web Crypto (AES-256-GCM + PBKDF2-HMAC-SHA-256) with a human-readable threat model.

## What this isn’t

- Not a cloud service: if you lose the HTML file, the vault, or your passphrase, your data is gone.
- Not protection against malware, keyloggers, or a compromised operating system/browser.
- Not a magic invisibility cloak against powerful, well-resourced attackers.
- Not a substitute for good operational security (strong passphrases, safe devices, and safe habits).

## Quick start

1. Go to the [Releases](./releases) page on this repo and download:
   - `Aeon_Secure_Suite_v4.4.html`
   - `Aeon_MicroVault_v1.9.html`
2. (Optional but recommended) Verify the SHA-256 hashes match the values in the **Verification** section above.
3. Disconnect from the internet (or go fully offline if you want).
4. Open the HTML file(s) in a modern browser (File → Open, or drag into a browser window).
5. Follow the on-page instructions to lock/unlock messages, files, or vaults.
