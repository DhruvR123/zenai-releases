# ZenAI Release Distribution Channel

This repository serves exclusively as the automated binary update distribution endpoint for the ZenAI desktop application.

### Hosted Release Artifacts
- **latest.json**: Cryptographically signed OTA update manifest consumed by the desktop updater.
- **ZenAI_*_x64-setup.exe**: Signed standalone Windows x64 application installer packages.
- **ZenAI_*_x64-setup.exe.sig**: Detached Ed25519 digital signatures.
- **SHA256SUMS.txt**: SHA-256 cryptographic checksums for binary integrity verification.

> **Security & Privacy Notice**: This repository hosts only compiled, cryptographically signed distribution binaries and version manifests. No source code, internal architecture, or developer assets are stored or distributed here.
