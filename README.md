# Intentionally vulnerable Golang project

[![Run Dependency Check](https://github.com/gamertense/intentionally-vulnerable-golang-project/actions/workflows/dependency-check.yml/badge.svg)](https://github.com/gamertense/intentionally-vulnerable-golang-project/actions/workflows/dependency-check.yml)

This is just a minimal repo for testing Sonatype's `nancy` against an intentionally vulnerable list of
dependencies, and as well showing a small example of how to use it in GitHub Actions.

Project is currently setup to use both `dep` and `go mod` so you should be able to use either one.

To see how `nancy` will output when finding vulnerabilities, check out [this build on Travis-CI](https://travis-ci.org/github/sonatype-nexus-community/intentionally-vulnerable-golang-project/builds/671448888) or [this build on CircleCI](https://circleci.com/gh/sonatype-nexus-community/intentionally-vulnerable-golang-project/26)
