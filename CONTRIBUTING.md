# Contributing to PGDN

Thanks for wanting to contribute! This org spans multiple repos (scanners, orchestrators, data models, research).
This guide applies across **all repositories in `pgdn-network`**.

## Ways to contribute
- **Code**: scanners, modules, parsers, normalizers, orchestrator adapters.
- **Research**: methodology, datasets, reproducible network scans.
- **Docs**: READMEs, examples, tutorials (when public docs are ready).
- **Issues**: bug reports, triage, reproduction cases.

## Ground rules
- Be respectful. Follow our [Code of Conduct](../CODE_OF_CONDUCT.md).
- Keep security in mind; avoid posting sensitive data. Use the **Discord** for disclosure.
- Prefer small, focused PRs.
- Write tests when adding behavior; update docs/README in that repo.

## Workflow
1. **Discuss** (optional but encouraged): open a GitHub Discussion/Issue or join our **Discord**.
2. **Fork & branch**: `feature/<short-name>` or `fix/<short-name>`.
3. **Commit style**: Conventional Commits (e.g., `feat(scanner): add ssh banner probe`).
4. **PR**: Link issues, include rationale and testing notes, and any security considerations.
5. **Review**: Maintainers will review for scope, security, and style.

## Development standards
- Language/tooling varies per repo; follow that repo’s README and `Makefile`/`package.json` targets.
- Keep external dependencies minimal and auditable.
- Log responsibly; never log secrets or PII.
- Default license is **MIT** across OSS repos.

## Security
If your contribution touches security-sensitive areas or reveals a vulnerability, **do not** open a public issue.
Report privately via **Discord** (see [SECURITY.md](../SECURITY.md)).

## Community
- Org: https://github.com/pgdn-network
- Discord: <discord-invite-url-here>

Thanks again — you’re helping secure decentralized infrastructure.
