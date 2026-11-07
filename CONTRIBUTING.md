# Contributions

Contributions to my repositories are welcome! They go through GitHub issues and pull requests, following the few rules below.

## Conventions

### Commit Messages

Commit messages follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification: they drive the changelog and the release versions. The [VSCode extension](https://github.com/vivaxy/vscode-conventional-commits) helps writing them.

### Pull Requests

Rebase your branch on `main`, without merge commits, before asking for a review, and open the pull request against `main`:

1. __Fork the repository__ on GitHub, then clone your fork and track the original repository:
    ```sh
    git clone https://github.com/<your-username>/<repository>.git
    cd <repository>
    git remote add upstream https://github.com/this-is-tobi/<repository>.git
    ```
2. __Create a branch__ for your change:
    ```sh
    git checkout -b feat/my-feature
    ```
3. __Commit__ following the Conventional Commits specification:
    ```sh
    git commit -m "feat: add my feature"
    ```
4. __Rebase__ onto the latest `main` of the original repository:
    ```sh
    git fetch upstream
    git rebase upstream/main
    ```
5. __Push__ to your fork, then open a pull request against `main`:
    ```sh
    git push --force-with-lease origin feat/my-feature
    ```

## Linting and Testing

Run the repository's linters and tests before pushing and make sure the CI workflows pass. In a tested repository, a new feature comes with its tests.

## Code of Conduct

Everyone taking part in my repositories is expected to follow the [code of conduct](https://github.com/this-is-tobi/.github/blob/main/CODE_OF_CONDUCT.md).
