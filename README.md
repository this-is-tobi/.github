# Github templates :wrench:

This repository serves as a centralized location for default GitHub configurations and templates for repositories in this organization or user account. By defining shared templates here, we streamline the process of maintaining consistency and quality across all my repositories.

## Purpose

The `.github` repository is used to store and manage:

- __Issue Templates__: Predefined formats to guide contributors when reporting issues.
- __Pull Request Templates__: Standardized templates for contributors to follow when submitting pull requests.
- __Default Community Files__: Such as `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and `SECURITY.md`, which apply to all repositories within the organization unless overridden.

## Files and Structure

The repository is organized as follows:

```sh
./ 
├── .github/ 
│   ├── ISSUE_TEMPLATE/ 
│   │   │   # Template for reporting bugs
│   │   ├── BUG_REPORT.md
│   │   │   # Template for requesting new features
│   │   ├── FEATURE-REQUEST.md
│   │   │   # Configuration for issue templates
│   │   └── config.yml
│   └── PULL_REQUEST_TEMPLATE/ 
│       │   # Default pull request template
│       └── PR.md
│   # Guidelines for contributing to my projects
├── CONTRIBUTING.md
│   # Code of conduct for contributors
├── CODE_OF_CONDUCT.md
│   # Security reporting guidelines
└── SECURITY.md
```

### Key Features

1. __Consistency__: Ensures all repositories under the organization or user account have a consistent set of community files and practices.
2. __Ease of Use__: Contributors and maintainers can rely on predefined templates, saving time and effort.
3. __Centralized Updates__: Changes to templates can be managed centrally and apply automatically where appropriate.

## How It Works

GitHub automatically detects and uses the files in this repository as default templates for repositories in this account:

- __Issue and Pull Request Templates__: Repositories without custom templates will use the ones defined here.
- __Community Health Files__: These files (`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, etc.) will automatically apply to all repositories unless overridden.

## Customization for Specific Repositories

If a repository needs its own version of a template or workflow, it can define the file locally in its `.github` directory, overriding the default provided by this repository.

For more information about GitHub's `.github` repository features, see [GitHub documentation on default community health files](https://docs.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file).
