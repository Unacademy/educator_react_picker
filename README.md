# educator_react_picker

> Picker is a cross-platform UI component for selecting an item from a list of options.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**educator_react_picker** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

Picker is a cross-platform UI component for selecting an item from a list of options.

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | React Native |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `@babel/core`
- `@babel/runtime`
- `@expo/webpack-config`
- `@react-native/eslint-config`
- `@semantic-release/git`
- `@testing-library/react-native`
- `@types/react`
- `babel-jest`
- `babel-plugin-module-resolver`
- `detox`


---

## Repository Structure

```
educator_react_picker/
├── .clang-format
├── .eslintignore
├── .eslintrc.js
├── .flowconfig
├── .github/
│   ├── CODEOWNERS
│   ├── workflows
├── .gitignore
├── .npmignore
├── .prettierrc
├── .releaserc
├── .yarn
├── .yarnrc.yml
├── FabricExample/
│   ├── .bundle
│   ├── .eslintrc.js
│   ├── .gitignore
│   ├── .prettierrc.js
│   ├── .watchmanconfig
├── LICENSE
├── README.md
├── RNCPicker.podspec
├── android/
│   ├── build.gradle
│   ├── gradle.properties
│   ├── src
├── app.config.js
├── babel.config.js
├── e2e
├── example/
│   ├── .gitignore
│   ├── .watchmanconfig
│   ├── android
│   ├── app.json
│   ├── babel.config.js
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `FabricExample/.bundle/config` | Source file |
| `FabricExample/.eslintrc.js` | Source file |
| `FabricExample/.gitignore` | Source file |
| `FabricExample/.prettierrc.js` | Source file |
| `FabricExample/.watchmanconfig` | Source file |
| `FabricExample/App.tsx` | Source file |
| `FabricExample/Gemfile` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/educator_react_picker.git
cd educator_react_picker
# Follow language-specific setup
```

### Available Scripts

```bash
# prepare
npm run prepare   # bob build

# build
npm run build   # bob build

# start
npm run start   # react-native start

# start:macos
npm run start:macos   # react-native start --projectRoot ./ --use-react-native-macos

# ios
npm run ios   # cd example && react-native run-ios

# web
npm run web   # expo web

# android
npm run android   # react-native run-android

# macos
npm run macos   # cd example && react-native run-macos

# test
npm run test   # yarn validate:eslint && yarn validate:flow && yarn validate:typescript && yarn test:jest

# validate:eslint
npm run validate:eslint   # eslint 'js/**/*.js' 'example/**/*.js'

```


---

## Running the Application

```bash
npm run start   # react-native start
```

---

## Infrastructure & CI/CD

- CI/CD pipeline configured (`.github/workflows` or equivalent)
- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> #  `@react-native-picker/picker`



[![npm version](https://img.shields.io/npm/v/@react-native-picker/picker.svg)](https://www.npmjs.com/package/@react-native-picker/picker)
[![Build](https://github.com/react-native-picker/picker/workflows/Build/badge.svg)](https://github.com/react-native-picker/picker/actions) ![Supports Android, iOS, MacOS, and Windows](https://img.shields.io/badge/platforms-android%20|%20ios|%20macos|%20windows-lightgrey.svg) ![MIT License](https://img.shields.io/npm/l/@react-native-picker/picker.svg) [![Lean Core Extracted](https://img.shields.io/badge/Lean%20Core-Extract

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
