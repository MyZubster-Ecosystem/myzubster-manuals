# MyZubster Manuals

> 🌍 **Understand MyZubster in your language:** [Global multilingual guide](https://github.com/MyZubster-Ecosystem/myzubster/blob/main/docs/i18n/README.md) — English, Italiano, Español, Français, Deutsch, Português, 中文, 日本語, 한국어, العربية, हिन्दी, Русский, Türkçe, Bahasa Indonesia, Polski, Українська, বাংলা, اردو, فارسی, Kiswahili.
>
> MyZubster connects real-world observations, verifiable evidence, collaborative bounties and platform rewards. **MYZ is currently an internal reward/accounting ledger; external XMR/token/blockchain settlement is separate and independently verified.**

Manuals, runbooks and operator/contributor guides for the MyZubster ecosystem.

## Status

**Documentation bootstrap.** This repository is intended for durable, task-oriented manuals rather than product source code.

## Proposed structure

```text
manuals/
  core/
  gateway/
  app-web/
  ipfs/
  bounties/
  robotics/
  operations/
  security/
```

Each manual should state:

- target repository/component;
- tested version/commit where practical;
- prerequisites;
- exact procedure;
- verification steps;
- rollback/recovery notes when relevant;
- security/privacy warnings.

## Canonical references

- [Ecosystem Architecture](https://github.com/MyZubster-Ecosystem/myzubster/blob/main/docs/ECOSYSTEM.md)
- [MyZubster Bounty System](https://github.com/MyZubster-Ecosystem/myzubster/blob/main/BOUNTIES.md)
- [Documentation Hub](https://github.com/MyZubster-Ecosystem/myzubster-docs)

## Bounties

Documentation/manual work may be bountied when the issue defines the exact manual, acceptance criteria and reproducible verification.

Historical bounty amounts are not proof of payment. MYZ in the current core platform is an internal reward/accounting ledger; external settlement requires independent evidence.

See `BOUNTIES.md` for local scope.

## Security

Manuals must use placeholders for secrets and must never include real private keys, seed phrases, passwords, access tokens or production credentials.

Sensitive operational details should only be documented in the appropriate private location, not a public manual.

## Contributing

Prefer small manuals that a second person can execute from a clean environment. Include expected outputs without embedding secrets.

---

## Official project identity

MyZubster is maintained within the [MyZubster-Ecosystem](https://github.com/MyZubster-Ecosystem) organization. Canonical public administrator/maintainer reference: **[Daniel Ioni (@DanielIoni-creator)](https://github.com/DanielIoni-creator)**.

This link is a stable public project-identity reference. By itself, it is not a cryptographic signature or legal identity certification.
