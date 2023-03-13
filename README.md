# fish-atlas-sdk

This is an example library that was created for demo purpose

## Pre-requisites

* Install Node LTS
* Go through the "Bootstrapping your library" section if you have no versions in NPM yet

## Install

```shell
npm ci
```

## Bootstrapping you library

The next steps are applicable only for the situation when you don't have a library in the NPM repo yet

### Authenticate in NPM

Sign in to NPM locally

```shell
npm login
```

### Publish your first library version to NPM manually

```shell
npm publish
```

### Create you second initial changelog file and release it

```shell
npx standard-version
npm publish
git push origin main
```
