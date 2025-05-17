# MSSE642 - Software Assurance

This repository contains coursework for MSSE 642 - Software Assurance at Regis University. It is organized into two main sections:

- **Discussions:** Weekly discussion posts covering software engineering concepts and tools.
- **Security Analysis:** Analytical papers and notes on software security topics.

---

## 📚 Discussions

- [Week 1](Discussions/week1/)
  - [Git Basics: Core Concepts and Architecture](Discussions/week1/discussion1.md)
  - [Initial Setup: GitHub Actions and Markdown Linting](Discussions/week1/initialSetup.md)

## 🔒 Security Analysis

- [Injection (Cross-site Scripting)](Security%20Analysis/week2/injection.md)

---

## ⚙️ GitHub Actions

This repository uses GitHub Actions to automate workflows, including:

- **Markdown Linting:** Automatically checks Markdown files for style and formatting issues on each push or pull request.
- **CI/CD Workflows:** Ensures code quality and consistency by running automated checks.

### Available Workflows

- `.github/workflows/markdown-lint.yml`: Runs markdownlint on all Markdown files to enforce style and formatting.
<!-- - `.github/workflows/ci.yml`: (If present) Runs tests and other CI checks to maintain code quality. -->

You can find workflow configuration files in the `.github/workflows/` directory.
