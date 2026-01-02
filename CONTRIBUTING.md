Welcome to the project! To maintain high code quality and consistent progress, we ask that all contributors follow these guidelines.

1. Getting Started
Search First: Before starting new work, check the [Issues tab] to see if the task or bug is already being addressed.

Open an Issue: For new features or major changes, please open an issue first to discuss the design and approach with the maintainers.

2. Branching Strategy
We use a feature-branch workflow.

Main Branch: Always stable and deployable. No direct commits allowed.

Feature Branches: Create a branch from main using the following naming convention:

feat/feature-name (for new features)

fix/bug-name (for bug fixes)

docs/topic-name (for documentation updates)

3. Coding Standards & Linting
To ensure readability and maintainability, we enforce the following:

Style: Follow the language-specific style guide (e.g., Airbnb Style Guide for JavaScript, PEP 8 for Python).

Linting: Run npm run lint (or your local equivalent) before committing. PRs with linting errors will be automatically rejected by CI.

Formatting: Use Prettier or the provided IDE configuration to ensure consistent indentation.

4. Pull Request (PR) Process
This is our primary Quality Gate. Every PR must meet these requirements:

Template: Fill out the provided PR template (Summary, Impact, Testing steps).

Linked Issues: Include Closes #123 in the description to link the PR to its issue.

Tests: New features must include unit tests. Existing tests must pass.

Review: You must request a review from at least one peer. Self-merging is disabled via Branch Protection Rules.

5. Commit Message Convention
We use Conventional Commits to keep our history clean:

feat: A new feature.

fix: A bug fix.

docs: Documentation only changes.

refactor: A code change that neither fixes a bug nor adds a feature.

Example: feat: add encryption to user secrets storage

6. Definition of Done (DoD)
A task is considered "Done" only when:

[ ] Code follows project standards.

[ ] All automated CI/CD checks are Green.

[ ] Documentation (README or Wiki) has been updated.

[ ] At least one approving review is recorded.
