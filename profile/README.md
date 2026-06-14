# VitalSend

EU-based service for irreversible, one-time encrypted file handover.
A file is accessed exactly once, then destroyed.

[vitalsend.eu](https://vitalsend.eu)

## What's here

- **[crypto](https://github.com/vitalsend/crypto)** — client-side encryption,
  KDF, share-link codec, and the chunked-AEAD worker. The reference
  implementation behind every VitalSend share link. Auditable; reproducible.

The service itself, its transport, and its orchestration remain closed.

## License

The published code is licensed under **AGPL-3.0-only** (see each repo's
`LICENSE` file).

A **commercial license is available** for use cases incompatible with
AGPL's copyleft. Contact `support@vitalsend.eu`.

## Security

To report a vulnerability:

- Email **`security@vitalsend.eu`** — do not open a public GitHub issue.
- Full policy, scope, and safe harbour: [vitalsend.eu/security/disclosure/](https://vitalsend.eu/security/disclosure/)

## Who

Built by [Jörgen Karlsson](https://github.com/jorgen-k), founder of VitalSend.
