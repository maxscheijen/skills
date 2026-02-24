---
name: git-commit-message
description: Generate a conventional git commit message based on staged changes.
---

Look at the staged changes and generate a Conventional Commit message.

## Requirments

- Use the Conventional Commits format: `<type>(optional scope): <short summary>`.
- The first line must be short and high-level (max 72 characters).
- Add a blank line, then list details as bullet points.
- Output must be valid Markdown and contain only the commit message (no extra commentary).

## Example Output

The example output should formatted in markdown.

```md
feat(parser): add support for xyz

- Added the following
- Changed this
- Removed something else
```