# Git Messages Skill

The goal of this skill is to assist developers in creating clear and effective commit messages for their Git repositories.

This skill helps generate:

- commit messages
- pull request titles
- pull request descriptions

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