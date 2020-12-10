# nodejs-github-actions-sample

Node.js sample for installing, building, testing and publishing libraries

## Workflows

### Main

Triggers on pushes to any branch and pull_requests

See at [.github/workflows/main.yml](./.github/workflows/main.yml)

#### Steps

- Checkout
- Install
- Build
- Test

### Release

Triggers on creation of releases

See at [.github/workflows/release.yml](./.github/workflows/release.yml)

**Steps:** 

- ... same previous steps as main workflow
- Publish to [NPM Registry](https://registry.npmjs.org)

## GitHub Actions Documentations

- [Building and Testing Node.js](https://docs.github.com/en/free-pro-team@latest/actions/guides/building-and-testing-nodejs)
- [Publishing Node.js Packages](https://docs.github.com/en/free-pro-team@latest/actions/guides/publishing-nodejs-packages)
