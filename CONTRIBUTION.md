# Contributing to CodeClayTools

Welcome! Whether you're Future Me or someone new, here's how we do things at CodeClayTools.

## 🔀 Branching Strategy

All work happens through feature branches. Direct commits to `main` are disallowed.

### Allowed Branch Types

| Type     | Prefix       | When to use                                    |
|----------|--------------|-------------------------------------------------|
| `build/` | Build        | Infrastructure, packaging, tooling              |
| `feature/` | Feature     | New functionality or major modifications        |
| `chore/` | Chore        | Dependency bumps, config updates, etc.          |
| `fix/`   | Fix          | Bugfixes or regression fixes                    |

### Examples

- `feature/cli-export-support`
- `fix/typo-on-helptext`
- `build/github-actions-integration`
- `chore/update-readme-links`

## ✅ Pull Request Requirements

All branches must be merged via pull request (PR). No direct commits to `main`.

PRs should:

- Have a clear title and description.
- Reference issues (if any) with `Fixes #123`.
- Be peer reviewed (if not solo).
- Pass all CI checks (if configured).

## 🧪 Code Quality

We prefer:

- Clear structure over cleverness.
- Small commits with descriptive messages.
- Comments where intent isn’t obvious.
- A broken feature is worse than a missing one.

## 🔐 Protected Branches

The `main` branch is protected with the following:

- PR required for merge
- Status checks must pass (if enabled)
- Linear history (squash merges or rebases)
- No force-pushes, ever

## 🚀 Automation (Coming Soon)

Planned:

- GitHub Actions for linting, builds, and tests.
- PR auto-labeling based on branch name.
- Dependency update workflows.

## 🙌 Thanks!

Whether you're fixing typos or shipping entire subsystems, thanks for making CodeClayTools better.
