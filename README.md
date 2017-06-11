# cz-freecodecamp

[![Greenkeeper badge](https://badges.greenkeeper.io/freeCodeCamp/cz-freecodecamp.svg)](https://greenkeeper.io/)

Status:
[![Build Status](https://img.shields.io/travis/freecodecamp/cz-freecodecamp.svg?style=flat-square)](https://travis-ci.org/freecodecamp/cz-freecodecamp)

A plugin for [commitizen](https://github.com/commitizen/cz-cli) built for
freeCodeCamp

**Table of Contents**

- [Introduction](#introduction)
- [Local Installation](#local-installation)
- [Usage](#usage)

# Introduction

This Commitizen adapter helps standardize commit messages for freeCodeCamp so
being asked to fix incorrectly formatted commit messages will be less of a
problem.

# Local Installation

```shell
# Install general tool globally
npm install -g commitizen

# Install freeCodeCamp specific adapter
git clone https://github.com/freeCodeCamp/cz-freecodecamp.git

# Add freeCodeCamp plugin to be used
cd cz-freecodecamp
echo '{ "path": "'$(pwd)'" }' > ~/.czrc

# Install node modules for adapter
npm install
```

# Usage

```shell
... # Make changes

# Stage changes
git add changed-file

# Use git cz instead of git commit
git cz
```
