# Pull Request Automation Skill

## Goal
<!-- Goal -->
This skill describes how to automate the pull request workflow using Git and GitHub. It helps organize commits, branches and pull request creation.

## Scope
<!-- Scope -->
Apply such skill when finishing a feature, bug fix or repository update.

## Process
<!-- Process -->

1. Verify modified files
2. Create a new branch
3. Add changed files
4. Create a descriptive commit
5. Push the branch to GitHub
6. Open a pull request
7. Add title and description
8. Review changes before merging

## Rules
<!-- Rules -->

- Never push directly to main
- Use descriptive branch names
- Use meaningful commit messages
- Keep pull requests focused on a single change
- Review files before creating the pull request

## Output Format
<!-- Output Format -->

Follow the next guidelines when creating branches and pull requests

- Name branches as feature/<feature-name>
- Use feat:, fix: or docs: on commit messages
- Create clear pull request titles
- Add a short description explaining the changes

## Example
<!-- Example -->

### Branch Creation

```bash
git checkout -b feature/add-login-page