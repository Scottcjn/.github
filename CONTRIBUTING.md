# Contributing to Scottcjn Repositories

Thanks for contributing to the Scottcjn and Elyan Labs project set. This repository provides default community-health files for the account, so this guide applies when an individual repository does not already have a more specific `CONTRIBUTING.md`.

## Start Here

1. Read the target repository README and any local docs before opening a change.
2. Check existing issues and pull requests so you do not duplicate active work.
3. Keep each pull request focused on one repository and one clear improvement.
4. Use a descriptive branch name, such as `docs/fix-readme-link` or `tests/add-parser-coverage`.

If a repository has its own contributing guide, follow that guide first. Repository-specific instructions always take precedence over this default file.

## Good First Contributions

Useful contributions include:

- Documentation fixes, setup notes, and broken-link repairs.
- Small examples that make an existing workflow easier to reproduce.
- Focused tests for existing behavior.
- README, profile, funding, and community-health improvements.
- Clear bug fixes with a minimal explanation of the affected behavior.

Avoid broad rewrites, unrelated formatting churn, generated files, or large dependency changes unless a maintainer asks for them.

## Local Workflow

For documentation-only changes:

```bash
git diff --check
```

For code changes, use the commands documented by the target repository. If the repository does not document validation yet, run the smallest relevant local checks for the files you changed and describe them in the pull request.

Before opening a pull request:

- Rebase or merge the latest default branch if your branch is stale.
- Confirm only intended files changed.
- Remove local build artifacts, caches, logs, credentials, and machine-specific paths.
- Include the commands you ran and their results in the pull request body.

## Style

- Write clear, direct Markdown with stable headings.
- Prefer ASCII text unless the surrounding file already uses non-ASCII content for a clear reason.
- Keep examples copy-pasteable and avoid placeholders that look like real credentials.
- Link to canonical project docs instead of duplicating long setup instructions across repositories.
- Preserve existing license, funding, and attribution language unless the change is specifically about correcting that metadata.

## Pull Request Checklist

When you open a pull request, include:

- The repository and file paths changed.
- A short summary of the problem and fix.
- Validation commands, or a note that the change is documentation-only.
- Any compatibility notes for older hardware, operating systems, or package managers.
- Screenshots only when the change affects rendered pages or visual output.

## Bounty Work

Some repositories participate in the RustChain bounty program. For bounty work:

- Read the bounty issue carefully before claiming work.
- Comment on the bounty issue only after you have a concrete target and duplicate checks are clean.
- Keep payment details out of source files.
- Report the pull request, validation, and remaining maintainer-review blocker on the bounty issue.

Maintainers decide whether a submission qualifies for bounty acceptance. A merged pull request or maintainer comment is the source of truth.

## Questions

If the target repository has issues enabled, ask focused questions there. Otherwise, open a draft pull request with a small proposed change and explain what feedback you need.
