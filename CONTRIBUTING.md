# Contributing to Adytalis projects

Each Adytalis repository can have its own `CONTRIBUTING.md` with its setup and checks; when it does, that one applies. These are the defaults.

1. **Start from an issue.** Every piece of work has an issue, assigned to the project owner. Search before opening a new one.
2. **Branch** from the repository's integration branch (usually `develop`), named `feature/<issue>-<task>` or `bugfix/<issue>-<task>`. One issue per branch.
3. **Commit** in the [Conventional Commits](https://www.conventionalcommits.org) style: `type(scope): summary`.
4. **Check** your change with the repository's own checks, and paste their output in the pull request.
5. **Open a pull request** against the integration branch, fill in the template, and write `Closes #<issue>`.
6. **Never** commit secrets, keys, tokens or personal data, and never force-push a shared branch.

Security problems go privately to the contact in [SECURITY.md](SECURITY.md). Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
