# Contributing

## The rule that matters most

**One owner per truth.** Before changing anything, identify which system owns the
domain you are touching. Coordination, product and runtime data never collapse
into each other.

## Before you open a pull request

1. **Verify locally.** Run the project's own test command and paste the real output.
2. **State the evidence.** Every claim needs a command, a result and a timestamp.
   Staging is not verification.
3. **Respect the boundary.** If your change reaches into another domain, it needs a
   versioned contract — not a direct dependency.

## Pull requests

- `main` is protected: no force-push, no deletion, one approving review required.
- Keep the diff scoped to one concern.
- Describe *what changed*, *how it was verified*, and *what remains*.

## Commit messages

Conventional prefixes are used throughout: `feat:`, `fix:`, `docs:`, `chore:`, `test:`.
