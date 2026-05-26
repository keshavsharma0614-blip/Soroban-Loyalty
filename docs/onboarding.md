# Onboarding Guide

Welcome! This guide walks through the full contribution process, from setting up the project to opening your first pull request.

If this is your first open-source contribution, don’t worry. The goal is to help you understand the workflow step by step.

---

# Before You Start

Before contributing, please follow the setup instructions in the README and CONTRIBUTING guide.

The README includes:

- Project requirements
- Installation steps
- Dependency setup
- Commands for running the project locally

---

# Finding an Issue to Work On

A good place to start is by looking for issues labeled:

- `good first issue`
- `documentation`
- `help wanted`

These issues are usually smaller in scope and easier for new contributors to understand.

Before starting work:

1. Read the issue carefully.
2. Check if someone is already assigned.
3. Leave a comment saying you would like to work on it.

Example:

```text
Hi! I’d like to work on this issue.
```

---

# Fork the Repository

Create your own copy of the repository by clicking the **Fork** button on GitHub.

After forking, clone your fork locally:

```bash
git clone <your-fork-url>
```

Move into the project directory:

```bash
cd <repository-name>
```

---

# Create a Branch

Create a separate branch for your work.

Example:

```bash
git checkout -b docs/update-onboarding-guide
```

Using separate branches helps keep changes organized and easier to review.

---

# Make Your Changes

Now you can start working on the issue.

Try to:

- Keep changes focused on the issue
- Follow the existing project style
- Write clear documentation and comments
- Avoid unrelated changes in the same PR

---

# Test Your Changes

Before submitting a pull request, run the recommended checks from the README or contributing documentation.

Example:

```bash
flutter analyze
flutter test
```

Make sure everything passes before opening a PR.

---

# Commit Your Changes

Stage and commit your work with a clear commit message.

Example:

```bash
git add .
git commit -m "docs: add onboarding guide for contributors"
```

Good commit messages make the project history easier to understand.

---

# Push Your Branch

Push your changes to your fork:

```bash
git push origin <branch-name>
```

---

# Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**.

A good pull request should include:

- A short summary of the changes
- Why the changes were made
- Any testing or verification steps

Keep the PR focused and easy to review.

---

# During Review

Maintainers may leave feedback or request changes. This is a normal part of the contribution process.

When updating your PR:

1. Make the requested changes
2. Commit and push again
3. Reply politely in the PR conversation

---

# Final Notes

Thank you for contributing!

Even small improvements help the project grow and make it easier for future contributors to get involved.
