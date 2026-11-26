# How our team uses Copilot

Short notes from the team on working with Copilot in this repository.

## What works well

- Let Copilot scaffold the repetitive parts of a change (forms, list rendering, CSS tokens).
- Ask it to explain an existing function before rewriting it.
- Review its suggestions the same way you would review a teammate's pull request: read the diff,
  run the tests, and check the accessibility of anything user-facing.

## Team agreements

- `.github/copilot-instructions.md` holds the conventions every suggestion should follow.
- `.github/workflows/copilot-setup-steps.yml` prepares the environment so Copilot can run the
  test suite before it proposes a change.
- Copilot is a collaborator, not a replacement for review: a human still approves every pull request.
