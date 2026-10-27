# Contributing Guidelines

Thank you for your interest in contributing to this repository! Please follow these guidelines when submitting changes.

## Branching & Pull Requests

- **Protected Default Branch**: Direct pushes and force-pushes to the default branch (`main` / `master`) are disabled.
- **Feature Branches**: Always create a dedicated branch for your work (e.g., `feat/short-description`, `fix/issue-description`, or `docs/update-topic`) and submit changes via a **Pull Request**.
- **Focused Changes**: Keep pull requests focused on a single concern or issue. Avoid bundling unrelated formatting or refactoring changes.
- **Review & Thread Resolution**: All review comments and conversation threads must be resolved before a pull request can be merged.

## Commit Sign-Off (DCO)

All commits in this repository must be **signed off** under the [Developer Certificate of Origin (DCO)](https://developercertificate.org/) using the `-s` (`--signoff`) flag:

```bash
git commit -s -m "feat: describe your change"
```

This appends a `Signed-off-by: Your Name <your.email@example.com>` trailer to your commit message. Commits without a valid `Signed-off-by:` trailer will be rejected by the repository ruleset.

> [!TIP]
> You can configure Git to sign off commits automatically:
> ```bash
> git config --global format.signoff true
> ```

## Pre-Submission Checklist

- [ ] Changes are on a feature/topic branch (not directly on `main` / `master`).
- [ ] Every commit includes a `Signed-off-by:` trailer (`git commit -s`).
- [ ] Project builds cleanly and all existing tests/linters pass locally.
- [ ] Documentation is updated if behavior or configuration changed.
