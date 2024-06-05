---
name: '📣 Masa Product Release'
about: 'Start a new Masa Product release.'
labels: release
title: 'Masa Product release v'
assignees: teslashibe, mudler
---

## 🗺 What's left for release

<List of items with remaining PRs and/or Issues to be considered for this release>

## 🔦 Highlights

< top highlights for this release notes >

## ✅ Release Checklist

- [ ] **Stage 0 - Finishing Touches**
    - [ ] Make sure CI tests are passing.
    - [ ] Ensure SDK is aligned to have the neded Oracle features exposed for the release
    - [ ] Ensure the CLI is aligned to consume the latest SDK correctly
    - [ ] There is a Masa-Oracle release
    - [ ] Update release files to bump the version in the Oracle
- [ ] **Stage 1 - Manual testing**
  - How: Using the assets from master, make sure that test scenarios not covered by automatic tests are passing, and that docs are still aligned
    - [ ] ...
- [ ] **Stage 3 - Release**
  - [ ] Tag Oracle
  - [ ] Tag SDK
  - [ ] CLI and App needs to point to SDK version and have its own tag
- [ ] **Stage 4 - After release
  - [ ] ...
