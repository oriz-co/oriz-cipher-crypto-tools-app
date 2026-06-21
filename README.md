# Oriz Cipher — Crypto tools

> Encryption, decryption, hashing, and key-generation utilities for everyday cryptography work.

**Live at**: <https://crypto.oriz.in> · **Status**: scaffold

## What this is

Cipher turns plaintext into ciphertext (and back), generates keys, derives hashes, and signs and verifies messages. Everything runs client-side in your browser via the native WebCrypto API — no payloads ever hit a server.

## Per-feature inventory

| Feature                     | Status     |
| --------------------------- | ---------- |
| (tools not yet implemented) | 📜 planned |

## App-specific env vars

None beyond the family-wide set at `templates/.env.example`.

## Local dev

```bash
# from the workspace root (c:/D/oriz)
pnpm -F oriz-cipher-crypto-tools-app dev
```

## Knowledge

See [`./knowledge/`](./knowledge/) for app-specific decisions, runbooks, and services. Family rules / decisions / architecture live at the master repo's [`knowledge/`](../../../../knowledge/).

## License

Source-available, all rights reserved. See master [`LICENSE`](../../../../LICENSE) — same terms across the family.
