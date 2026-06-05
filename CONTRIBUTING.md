## Contributing Guidelines

We welcome thoughtful external contributions, but **Savior Systems** is primarily maintained by a core internal team. Contributions are evaluated on a case‑by‑case basis.

### Before opening an issue
- Search existing issues and the documentation to avoid duplicates.
- Ensure the request aligns with our public scope (no private infrastructure, internal client data, or proprietary designs).
- Use the appropriate issue template.

### Before opening a pull request
- Fork the repository and create a branch named `feature/<short‑description>` or `fix/<short‑description>`.
- Follow the coding style used in the repository (Kotlin/Java for Android projects, concise Rust/Go for tooling, etc.).
- Write clear, atomic commits. Follow the Conventional Commits format (`feat:`, `fix:`, `docs:` etc.).
- Run any project‑specific linting or tests locally before pushing.
- Do **not** include secrets, API keys, passwords, or any internal URLs in the commit.

### Review Process
- All PRs are reviewed by at least one maintainer.
- Security‑sensitive changes (e.g., CI workflows, credential handling) require additional review from the security contact.
- Once approved, the maintainer will merge using the **squash** strategy to keep history clean.

### Getting Help
- For questions about contribution expectations, open a `question` issue using the **Documentation** template.
- For urgent matters, contact the security email listed in `SECURITY.md`.
