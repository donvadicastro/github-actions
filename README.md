# Github actions
Collection of useful Github workflow actions.

## Build and tests
* [Build the project and run internal unit tests on each commit (including PR merge)](.github/workflows/build.yml)
* [Run E2E tests with  Cypress on the provisioned environment when pull-request updated or commit to the specific branch](.github/workflows/e2e.yml)
* [Run integration tests on top of Docker-provisioned infrastructure](.github/workflows/e2e-docker.yml)
* [Run extended verification suite when label assigned](.github/workflows/e2e-conditional.yml)

## Publishing and version handling
* [Publish artifact to NPM registry on creating new release tag](.github/workflows/npm-publish.yml)
* [Bump project patch version after each merge code to master](.github/workflows/bump.yml)
* [Auto-deploy compiled application to github.io during master merge](.github/workflows/gh-pages-publish.yml)

## Project quality
* [Ensure changelog is updated when pull-request created to master](.github/workflows/changelog.yml)
* [Creating separate issues for each existing TODO](.github/workflows/todo.yml)
* [Monitoring outdated and stale pull-requests on regular basis (each midnight)](.github/workflows/cron.yml)
* [Create architecture map in codesee on master merge](.github/workflows/codesee.yml)


