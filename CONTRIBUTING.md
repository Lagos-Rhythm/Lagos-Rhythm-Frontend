
---

# 1. `CONTRIBUTING.md`

````md
# Contributing Guidelines

Thank you for your interest in contributing to this project.
To keep development organized and maintain code quality, please follow the workflow and guidelines below.

---

# Project Architecture

This project uses a **separated architecture** instead of a monolithic repository.

Core services include:

- **Frontend** – user interface
- **Backend** – API and business logic
- **Supabase** – authentication and database
- **Cloudinary** – file and media storage

---

# Branching Strategy

The project uses the following branch structure:

main → production-ready code
dev → active development (default branch)

### Important Rules

- **Do NOT create pull requests directly to `main`.**
- **All contributions must target the `dev` branch.**
- The project maintainer is responsible for merging `dev` into `main`.

---

# Contribution Workflow

### 1. Fork or Clone the Repository

```bash
git clone <repo-url>
cd <project>
````

---

### 2. Checkout the Dev Branch

```bash
git checkout dev
git pull origin dev
```

---

### 3. Create a New Feature Branch

Always create your branch **from `dev`**.

Branch naming examples:

```
feature/add-login-page
feature/user-profile
fix/navbar-bug
fix/api-timeout
chore/update-dependencies
```

Create the branch:

```bash
git checkout -b feature/your-feature-name
```

---

### 4. Make Your Changes

Follow the project's coding standards and ensure:

* Clean, readable code
* Proper comments where necessary
* No unnecessary console logs
* No hardcoded secrets or credentials

---

### 5. Commit Your Changes

Use clear commit messages.

Examples:

```
feat: add login form validation
fix: resolve navbar overflow issue
chore: update dependencies
refactor: simplify auth middleware
```

---

### 6. Push Your Branch

```bash
git push origin feature/your-feature-name
```

---

### 7. Create a Pull Request

Create a **Pull Request to the `dev` branch**.

Ensure your PR:

* Uses the provided PR template
* Clearly explains the changes
* Links any related issue (if applicable)

---

# Pull Request Guidelines

Before submitting a PR, ensure:

* Your code builds successfully
* No merge conflicts with `dev`
* Code follows project standards
* The PR description clearly explains the purpose of the change

---

# Code Quality Expectations

Contributors should aim for:

* Maintainable code
* Modular structure
* Performance-conscious implementation
* Consistent formatting

---

# Maintainer Responsibilities

The maintainer will:

* Review pull requests
* Request changes if necessary
* Merge approved PRs into **dev**
* Handle releases from **dev → main**

---

# Questions

If you're unsure about anything, please open an **issue** before starting work.

We appreciate your contributions

````

---

# 2. `.github/pull_request_template.md`

```md
# Pull Request

## Description

Provide a clear and concise description of the changes made.

Example:
- Added login validation
- Fixed navbar layout bug
- Implemented user profile API

---

## Type of Change

Please check the relevant option.

- [ ] New feature
- [ ] Bug fix
- [ ] Code refactor
- [ ] Performance improvement
- [ ] Documentation update
- [ ] Other (please describe)

---

## Related Issue

Link any related issue.

Example:

Closes #12

---

## Changes Made

List the key changes in this PR:

-
-
-

---

## Testing

Explain how this was tested.

Example:

- Tested locally
- Checked responsiveness
- Verified API response

---

## Screenshots (if applicable)

Add screenshots or screen recordings if the change affects the UI.

---

## Checklist

Before submitting your PR, confirm the following:

- [ ] My branch was created from `dev`
- [ ] My PR targets the `dev` branch
- [ ] I tested my changes locally
- [ ] My code follows the project's standards
- [ ] I have added necessary documentation (if needed)

---

## Notes for Reviewers

Add anything reviewers should know.
````

---


