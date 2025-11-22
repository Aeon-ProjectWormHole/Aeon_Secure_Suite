<p align="center">
  <img src="aeon-logo.svg" alt="Aeon Secure Suite logo" width="96" />
</p>

# Aeon Secure Suite

Offline, single-file encryption toolkit (messages, files, and vaults) plus MicroVault v1.9, a lightweight air-gapped file vault.

## Verification (SHA-256)

Aeon_Secure_Suite_v4.4.html  
`d3ea3b4da50f42fb12302dbea3d964ca9a850ef8bd3ee2c900713b47e73d8be5`

Aeon_MicroVault_v1.9.html  
`798e6858b8847a87fb908e36331b3c83ed04d60803af0906c6c81b4d31c18427`

## Why This Exists

I'm not a developer. I'm a person who believes technology should serve humanity, not extract from it.

I built this with AI assistance because privacy tools shouldn't require a computer science degree. They should be accessible to anyone who needs them.

This is part of Project Aeon—an initiative to rebuild trust between humans and technology through transparency, sovereignty, and compassion.

If this helps even one person protect something that matters to them, it was worth building.

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

## Authorship & AI collaboration

Aeon Secure Suite and MicroVault were conceived and created by **Steven Politowicz**.

Much of the implementation and wording was co-developed with the help of a large language model (LLM) assistant. All cryptography uses standard browser APIs (Web Crypto), and the code is shipped as a single, auditable HTML file so that anyone can inspect, verify, or fork it.

## Safety & limitations

- If you lose your passphrase, vault, or the HTML file, your encrypted data cannot be recovered.
- These tools do **not** protect you from malware, keyloggers, or a compromised operating system or browser.
- Going offline (air-gapped) helps, but it does not fix an already infected or monitored device.
- Use strong, unique passphrases and avoid storing life-or-death secrets here without expert review of your full setup.

## Bugs & security issues

If you find a bug, UX issue, or have questions, please open a GitHub Issue on this repository.

If you believe you’ve found a security problem, avoid sharing real private data in screenshots or examples. Describe what you did, what you expected, and what happened instead so the issue can be investigated and fixed.
