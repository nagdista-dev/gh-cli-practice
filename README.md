# GH CLI Practice

Hands-on practice exercises for mastering **GitHub CLI (`gh`)** — the official command-line tool for GitHub.

## What's Inside

This repository contains practice files and exercises for learning how to use `gh` for common GitHub workflows:

- Creating and managing repositories
- Working with pull requests
- Managing issues and labels
- Cloning, forking, and pushing to repos
- GitHub Actions and CI/CD from the terminal

## Prerequisites

- [GitHub CLI](https://cli.github.com/) installed (`gh`)
- A GitHub account authenticated with `gh auth login`

## Getting Started

```bash
# Authenticate with GitHub
gh auth login

# Clone this repo
gh repo clone nagdista-dev/gh-cli-practice

# Check your auth status
gh auth status
```

## Useful Commands Reference

```bash
# Repos
gh repo list
gh repo create my-repo --public
gh repo view

# Pull Requests
gh pr create --title "My PR" --body "Description"
gh pr list
gh pr checkout <pr-number>

# Issues
gh issue create --title "Bug" --body "Details"
gh issue list
gh issue close <issue-number>

# General
gh browse
gh api /user
```

## Resources

- [GitHub CLI Official Docs](https://cli.github.com/manual/)
- [GitHub CLI Cheat Sheet](https://raw.githubusercontent.com/cli/cli/trunk/pkg/cmd/pr/shared/defaults.go)
