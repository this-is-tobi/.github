# Contributions

All contributions to my repositories are welcome and must be made via GitHub with a pull request following the rules below.

## Conventions

### Commit Messages

Commits must follow the specification of [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). It is possible to add the [VSCode extension for Conventional Commits](https://marketplace.visualstudio.com/items?itemName=vscodeshift.vscode-conventional-commits) to facilitate the creation of commits.

### Pull Requests

A pull request (PR) must be made with an updated branch that has been rebased onto the `main` branch (and without merge). Here are the steps:

1. __Fork the Repository__: Fork the repository on GitHub.
2. __Clone Your Fork__: Clone your forked repository to your local machine.
    ```sh
    git clone https://github.com/this-is-tobi/<repository_name>.git
    cd <repository_name>
    ```
3. __Create a New Branch__: Create a new branch for your changes.
    ```sh
    git checkout -b feature/your-feature-name
    ```
4. __Make Your Changes__: Add or modify the necessary files.
5. __Commit Your Changes__: Commit your changes following the Conventional Commits specification.
    ```sh
    git add .
    git commit -m "feat: add new feature"
    ```
6. __Rebase onto Main__: Ensure your branch is up-to-date with the `main` branch.
    ```sh
    git fetch origin
    git rebase origin/main
    ```
7. __Push Your Changes__: Push your changes to your fork.
    ```sh
    git push origin feature/your-feature-name
    ```
8. __Create a Pull Request__: Go to the original repository on GitHub and create a pull request from your branch.

## Linting and Testing

Check whether the repository has linting rules or tests to keep them clean and ensure that CI workflows pass. New features in repositories with tests should be accompanied by new tests to ensure that the new feature works properly.

## Code of Conduct

Please review and adhere to the [Code of Conduct](https://github.com/this-is-tobi/.github/CODE_OF_CONDUCT.md) for this project.