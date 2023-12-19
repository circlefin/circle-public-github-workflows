# circle-public-github-workflows

This contains a collection of shared Github Workflows which may be used by pubicly exposed repositories.

## Workflows

This repository contains the following shareable workflows under `.github/workflows`:

* actions-lint - Lints github workflows and actions.
* attach-release-assets - Attaches SBOM and other build artifacts to releases along with a manifest file.
* conventional-commit-release - Lints commit messages and PR titles to ensure compliance with [Conventional Commits](https://www.conventionalcommits.org); on default branch builds it will execute the [release-please action](https://github.com/google-github-actions/release-please-action) to generate Github releases & changelogs.
* pr-scan - Executes the [dependency-review-action](https://github.com/actions/dependency-review-action) to check for vulnerabilities and license compliance in pull request dependencies.
