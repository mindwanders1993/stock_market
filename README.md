# Branching Strategy

This document outlines the branching strategy and commit guidelines for the project, following the Gitflow Workflow. This workflow is suitable for projects with scheduled releases and multiple versions.

## Branches

- `main`: This branch contains stable production code that is ready for deployment.
- `develop`: This is the integration branch where features are combined and tested before being released.
- `feature/`: Branches with this prefix are used for developing new features. For example, `feature/new-chart-tool`.
- `release/`: This prefix is used for branches that are preparing for a new production release. They are used for final tweaks and adjustments.
- `hotfix/`: These branches are used for quick fixes that need to be applied directly to production.

## Commit Guidelines

To maintain a clear and navigable history, commit messages should adhere to the following guidelines:

- Commit messages should be clear and descriptive, explaining why the change was made.
- Each commit should represent a single logical change to make it easier to track changes and troubleshoot issues.
- Use the following prefixes to categorize your changes:
  - `feat:` for new features or additions to the project.
  - `fix:` for bug fixes.
  - `docs:` for changes to documentation.
  - `style:` for formatting, missing semi colons, etc.; no code change.
  - `refactor:` for refactoring existing code.
  - `test:` for adding or correcting tests.
  - `chore:` for mundane tasks like updating build tasks, package manager configs, etc.

By following these guidelines, we can ensure a smooth and efficient workflow for everyone involved in the project.