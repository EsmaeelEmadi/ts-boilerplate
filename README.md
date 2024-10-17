# TS-Boilerplate

A simple TypeScript boilerplate that integrates Commitizen and Husky to standardize git commit messages and automate releases. This setup helps maintain consistent commit messages and simplifies the release process by automatically generating changelogs and version bumps.

## Features

- **TypeScript**: A base setup for building TypeScript projects.
- **Commitizen**: Enforces a consistent commit message format.
- **Husky**: Adds pre-commit hooks to ensure code quality and commit message standards.
- **Standard Releases**: Automates release versioning and changelog generation based on commit history.

## Getting Started

1. Clone this repository:
    ```sh
    git clone <your-repo-url>
    cd ts-boilerplate
    ```

2. Install dependencies:
    ```sh
    pnpm install
    ```

3. Prepare Husky hooks:
    ```sh
    pnpm run prepare
    ```

## Commit Guidelines

To create a commit using Commitizen, run:
```sh
git commit
```

## Making a Release

To generate a new release, run:
```sh
npm run release
```

