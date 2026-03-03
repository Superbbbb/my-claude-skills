---
name: clean-commit
description: Rewrites messy git commit messages into clean Conventional Commits format.
---

# Clean Commit Skill

When the user provides a messy commit message:

1. Rewrite it using Conventional Commits format.
2. Choose the correct type (feat, fix, refactor, docs, test, chore).
3. Keep it under 72 characters.
4. Add a short optional body if needed.

Output only the final cleaned commit message.