# Contributing

These conventions apply to this repository and to every Rewaa repository you
work in afterwards.

## Branches

Never commit to `main`. Create a branch, and name it:

```
<type>/<short-description>
```

Use the same types as commit messages. Separate words with hyphens, keep it
short, and use only lowercase letters, numbers and hyphens.

```
docs/add-my-profile
feat/add-search-filter
fix/broken-date-format
```

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
Read that specification — it is short, and it is the source of truth rather than
this file.

```
<type>(<optional scope>): <description>
```

The description is lowercase, written in the imperative, and has no full stop
at the end. Imperative means "add", not "added" or "adds".

```
docs: add my profile
feat(auth): add password reset
fix(reports): correct week start in hours calculation
```

The types you will use most are `feat`, `fix`, `docs`, `refactor`, `test` and
`chore`.

## Pull requests

Open one when the work is ready to be read, not when it is perfect.

- Give it a title in the same format as a commit message.
- Fill in the description. Say what changed and why.
- Keep it to one subject. Two unrelated changes are two pull requests.
- Push new commits to the same branch when you address feedback. Do not close
  the pull request and open another one.

## What a reviewer looks for

- The branch name and commit messages follow the conventions above.
- The change does what the description says, and nothing else.
- Nothing secret is included. No passwords, no API keys, no tokens, no `.env`
  file, no connection strings. This applies to every repository, always. A
  secret committed once is compromised even after it is deleted, because it
  stays in the history.

## Getting help

Ask your mentor. A question asked early costs less than a day spent stuck.

For the mechanics of branching, committing and opening a pull request, work
through [Introduction to GitHub](https://github.com/skills/introduction-to-github)
from GitHub Skills first.
