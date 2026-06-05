# Repository Policy

- **Public repos** contain only code, docs, and assets that are safe to share.  
- **Private repos** hold internal infrastructure, credentials, and client‑specific data.  
- **Naming:** Public repos start with `Savior-Systems-` to differentiate from internal services.  
- **License:** All public repos use the Apache‑2.0 license (see `LICENSE.md`).  
- **Secrets:** Never commit API keys, passwords, or Play Console IDs. The `metadata-check.yml` workflow enforces this.
