---
name: 'Masa Token Release'
about: 'Start a new Masa Token release.'
labels: release
title: '📣 Masa Token release v'
assignees: teslashibe, mudler
---

## 🗺 What's left for release

<List of items with remaining PRs and/or Issues to be considered for this release>

## 🔦 Highlights

< top highlights for this release notes >

## ✅ Release Checklist

- [ ] **Stage 0 - Finishing Touches**
    - [ ] Make sure changes to the smart contracts repositories
    - [ ] Make sure there is enough liquidity "coverage" for stacking amount + calculated rewards of the users
- [ ] **Stage 1 - Manual testing**
  - How: Using the assets from master, make sure that test scenarios not covered by automatic tests are passing, and that docs are still aligned
    - [ ] Test smart contract changes in testnet for the chains:
        - [ ] BSC (Binance)
        - [ ] Ethereum
        - [ ] Base
        - [ ] Solana
        - [ ] Near
    - [ ] Test stacking
    - [ ] Test unstacking
    - [ ] Test claiming "locks"
    - [ ] Test bridge functionalities
- [ ] **Stage 3 - Release**
  - [ ] Make sure Smart contracts are updated and deployed in the following blockchains
    - [ ] BSC (Binance)
    - [ ] Ethereum
    - [ ] Base
    - [ ] Solana
    - [ ] Near
- [ ] **Stage 4 - After release**
  - [ ] Release notes needs to be updated in the documentation here: https://developers.masa.ai/docs/masa-oracle/RELEASE_NOTES
  - [ ] Update notion documentation about release

