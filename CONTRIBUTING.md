# Contributing

Thanks for taking an interest in one of [@finallyjay](https://github.com/finallyjay)'s
projects. These are the default contribution guidelines; an individual repository
may ship its own `CONTRIBUTING.md`, which takes precedence.

## Workflow

All changes go through **issue → branch → pull request → merge**. Please do not
push directly to the default branch.

1. **Open an issue** describing the bug or proposal before starting non-trivial
   work, so we can agree on the approach.
2. **Branch** from the default branch using a short, descriptive name
   (e.g. `fix/...`, `feat/...`, `docs/...`).
3. **Keep changes focused.** One logical change per pull request.
4. **Open a pull request** linking the issue (`Closes #123`). Make sure CI is
   green — most repos run lint, tests, and a build on every PR.

## Code style

Match the conventions of the surrounding code. Most repositories include a
linter/formatter and a test suite; run them locally before opening a PR and keep
the diff free of unrelated formatting churn.

## Reporting bugs

Use the repository's issue templates where available. Include reproduction steps,
what you expected, and what actually happened.

## Security issues

Do **not** report security vulnerabilities through public issues — see
[`SECURITY.md`](./SECURITY.md) for private disclosure.
