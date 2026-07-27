# GH CLI Practice

<p align="center">
  <img src="https://img.shields.io/badge/GitHub_CLI-gh-2088FF?style=for-the-badge&logo=github&logoColor=white" alt="GitHub CLI" />
  <img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Shell" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License" />
</p>

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

## Commands Reference

### Repos

```bash
gh repo list
gh repo create my-repo --public
gh repo view
```

### Pull Requests

```bash
gh pr create --title "My PR" --body "Description"
gh pr list
gh pr checkout <pr-number>
```

### Issues

```bash
gh issue create --title "Bug" --body "Details"
gh issue list
gh issue close <issue-number>
```

### General

```bash
gh browse
gh api /user
```

## Resources

- [GitHub CLI Official Docs](https://cli.github.com/manual/)
- [GitHub CLI Cheat Sheet](https://docs.github.com/en/get-started/using-github/github-cli)
