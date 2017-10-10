# cz-freecodecamp

[![Greenkeeper badge](https://badges.greenkeeper.io/freeCodeCamp/cz-freecodecamp.svg)](https://greenkeeper.io/)

Status:
[![Build Status](https://travis-ci.org/freeCodeCamp/cz-freecodecamp.svg?branch=master)](https://travis-ci.org/freeCodeCamp/cz-freecodecamp)

A plugin for [commitizen](https://github.com/commitizen/cz-cli) built for
freeCodeCamp

**Table of Contents**

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

# Introduction

This Commitizen adapter helps standardize commit messages for freeCodeCamp so
being asked to fix incorrectly formatted commit messages will be less of a
problem.

# Installation

Install as a global adapter for freeCodeCamp repos

```shell
# Install the commitizen cli globally
npm install --global commitizen

# Install the freeCodeCamp commitizen adapter globally
npm install --global cz-freecodecamp

# Save the adapter into global config
echo '{ "path": "cz-freecodecamp" }' > ~/.czrc

```

# Usage

Usage on freeCodeCamp's repos

```shell
... # Make changes

# Stage changes
git add changed-file

# This adapter is bundled in the freeCodeCamp main repo as a dependancy.
# Either use the inbuilt script
npm run commit

# Or alternatively on any of freeCodeCamp's repos including the main repo,
# use git cz instead of git commit
git cz
```

Note: Please check the [contributing guidelines](https://github.com/freeCodeCamp/freeCodeCamp/blob/staging/CONTRIBUTING.md#method-1-editing-via-your-local-fork-recommended) on the main repo for more on usage.
