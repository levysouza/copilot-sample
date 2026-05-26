# Git Messages Skill

The goal of this skill is to assist developers in creating clear and effective commit messages for their Git repositories.

This skill helps generate:

- commit messages
- pull request titles
- pull request descriptions

Always analyze the current repository changes before generating any response.

Use available workspace context, including:
- staged changes
- unstaged changes
- git diff
- modified files
- renamed files
- deleted files

Never ask the user to paste the diff if changes are already available in the editor context.

You must infer:

- the main purpose of the change
- affected modules
- whether the change is a feature, fix, refactor, docs, test, or chore
- possible breaking changes

---

## Commit Message Generation

Format

<description>

Examples:

- add login validation
- fix null response on api call
- use type annotations instead of any

Rules:

- use lowercase
- keep concise
- max 72 characters
- use imperative tense
- focus on the main change

---

## Pull Request Titles

PR titles must follow Conventional Commits.

Examples:

- feat(auth): implement jwt authentication
- fix(api): prevent timeout on requests

---

## Pull Request Descriptions

Always include:

### Summary

Short explanation of the change (what, why, and how).

### Changes

List the main modifications of the PR.

### Testing

Explain how the change is tested.