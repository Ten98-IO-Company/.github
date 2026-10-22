# Contributing to Ten98

Thanks for your interest in improving Ten98. These guidelines apply to every repository in this organisation unless a repository has its own CONTRIBUTING file.

## Before you start

- **Questions and ideas:** start a thread in the repository's Discussions tab.
- **Bugs and feature requests:** open an issue using the forms provided.
- **Security problems:** report them privately; see [SECURITY.md](SECURITY.md).
- **Setup and architecture:** each repository's wiki explains how to run, configure and test it.

## Making a change

1. Find or open an issue, so the change is agreed before you spend time on it.
2. Fork the repository and create a branch for your change.
3. Keep the change focused. Reuse what already exists before adding dependencies.
4. Add or update tests. A fix should come with a check that fails without it.
5. Run the repository's checks (see its wiki) and make sure they pass.
6. Open a pull request that explains what changed, why, and how you checked it.

## Ground rules

- Never commit passwords, API keys, tokens, `.env` files, databases or personal data.
- Tests must not make paid or real provider calls; use the mocks and stubs provided.
- Keep third-party licence notices when you reuse code, and check that the licence is compatible.
- Contributions are distributed under the repository's licence (MIT unless stated otherwise).

By taking part, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
