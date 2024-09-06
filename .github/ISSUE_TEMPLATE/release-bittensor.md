---
name: 'Masa Bittensor Release'
about: 'Start a new Masa Bittensor release.'
labels: release
title: '📣 Masa Bittensor release v'
assignees: teslashibe, mudler
---

## 🗺 What's left for release

<List of items with remaining PRs and/or Issues to be considered for this release>

### :bug: Bug fixes

- [ ] item_1

### 🌍 Protocol/P2P

- [ ] item_1

### :test_tube: Code testing

- [ ] item_1

### 🚑 Code health

- [ ] item_1

### 🔍 Services

- [ ] item_1

###  📡  Testnet Environment

- [ ] item_1

### :robot: CI and release process

- [ ] item_1

### 🎁 Product:

- [ ] item_1

### 💻 Infra

- [ ] item_1

### :crystal_ball: Metrics 

- [ ] item_1

### 📖 Documentation

- [ ] item_1

## 🔦 Highlights

< top highlights for this release notes >

# Release Checklist

## Security
- [ ] Ensure dependencies are up to date and there are no known vulnerabilities.  Run `pip list --outdated` to see outdated dependencies.  If any dependencies need upgrading (and are in fact upgraded), run `pip freeze > requirements.txt` to update the requirements!

## Continuous Integration (CI)
- [ ] Ensure all CI tests are passing
  - [ ] Docker Build and Publish / check-and-build (subtensor)
  - [ ] Docker Build and Publish / check-and-build (subnet)
  - [ ] Docker Build and Publish / check-and-build (miner)
  - [ ] Docker Build and Publish / check-and-build (validator)
  - [ ] Docker Build and Publish / check-and-build (protocol)
  _it is possible that we will de-couple the protocol CI build and check in future iterations_

## Issue Tracking
- [ ] Verify there are no blockers to the release
_a typical release will [look like this](https://github.com/masa-finance/roadmap/issues/33), verify all issues are resolved!_

## Tagging
- [ ] Tag the `masa-bittensor` release, and ensure the latest tag is visible [here](https://github.com/masa-finance/masa-bittensor/tags)

## Release Notes
- [ ] Update release notes text.  An example of a previous release is [here](https://github.com/masa-finance/masa-bittensor/releases/tag/v0.5.0), built off of the `release.yml` configuration [here](https://github.com/masa-finance/masa-bittensor/blob/main/.github/release.yml)
- [ ] Ensure the latest release notes are captured [here](https://github.com/masa-finance/masa-bittensor/blob/main/docs/RELEASE_NOTES.md) so they automatically get published to our dev docs.

## Docker
- [ ] Confirm that Docker images are published correctly
_this was resolved in #160 and should work automatically!_

## Documentation
- [ ] Ensure documentation is updated.  This includes our setup documentation as well as advanced sections.  All markdown files [here](https://github.com/masa-finance/masa-bittensor/tree/main/docs) are automatically pushed to our developer docs website.  If certain documents do not appear, edit the sidebar [here](https://github.com/masa-finance/docs/blob/main/sidebars.js)
- [ ] Review and update installation instructions if needed: [Installation Guide](https://github.com/masa-finance/masa-bittensor?tab=readme-ov-file#install)

## Notifications
- [ ] Notify @giovaroma and @lacyg4.
- [ ] Ask DCG to bump the weights_version - btcli sudo set --param weights_version --value <version> --netuid 42
