# @backstage/plugin-gitops-profiles

## 0.3.4

### Patch Changes

- 9f1362dcc1: Upgrade `@material-ui/lab` to `4.0.0-alpha.57`.
- Updated dependencies
  - @backstage/core-components@0.4.2
  - @backstage/core-plugin-api@0.1.8

## 0.3.3

### Patch Changes

- Updated dependencies
  - @backstage/core-components@0.4.0

## 0.3.2

### Patch Changes

- Updated dependencies
  - @backstage/core-components@0.3.0
  - @backstage/core-plugin-api@0.1.5

## 0.3.1

### Patch Changes

- 9d40fcb1e: - Bumping `material-ui/core` version to at least `4.12.2` as they made some breaking changes in later versions which broke `Pagination` of the `Table`.
  - Switching out `material-table` to `@material-table/core` for support for the later versions of `material-ui/core`
  - This causes a minor API change to `@backstage/core-components` as the interface for `Table` re-exports the `prop` from the underlying `Table` components.
  - `onChangeRowsPerPage` has been renamed to `onRowsPerPageChange`
  - `onChangePage` has been renamed to `onPageChange`
  - Migration guide is here: https://material-table-core.com/docs/breaking-changes
- Updated dependencies
  - @backstage/core-components@0.2.0
  - @backstage/core-plugin-api@0.1.4
  - @backstage/theme@0.2.9

## 0.3.0

### Minor Changes

- d719926d2: **BREAKING CHANGE** Remove deprecated route registrations, meaning that it is no longer enough to only import the plugin in the app and the exported page extension must be used instead.

### Patch Changes

- 48c9fcd33: Migrated to use the new `@backstage/core-*` packages rather than `@backstage/core`.
- Updated dependencies
  - @backstage/core-plugin-api@0.1.3

## 0.2.7

### Patch Changes

- 062bbf90f: chore: bump `@testing-library/user-event` from 12.8.3 to 13.1.8
- 675a569a9: chore: bump `react-use` dependency in all packages
- Updated dependencies [062bbf90f]
- Updated dependencies [889d89b6e]
- Updated dependencies [3f988cb63]
- Updated dependencies [675a569a9]
  - @backstage/core@0.7.9

## 0.2.6

### Patch Changes

- Updated dependencies [40c0fdbaa]
- Updated dependencies [2a271d89e]
- Updated dependencies [bece09057]
- Updated dependencies [169f48deb]
- Updated dependencies [8a1566719]
- Updated dependencies [4c049a1a1]
  - @backstage/core@0.7.0

## 0.2.5

### Patch Changes

- accdfeb30: Migrated to new composability API, exporting the plugin instance as `gitopsProfilesPlugin` and pages as `GitopsProfilesClusterListPage`, `GitopsProfilesClusterPage`, and `GitopsProfilesCreatePage`.
- Updated dependencies [b51ee6ece]
  - @backstage/core@0.6.1

## 0.2.4

### Patch Changes

- Updated dependencies [12ece98cd]
- Updated dependencies [d82246867]
- Updated dependencies [c810082ae]
- Updated dependencies [5fa3bdb55]
- Updated dependencies [21e624ba9]
- Updated dependencies [da9f53c60]
- Updated dependencies [32c95605f]
- Updated dependencies [54c7d02f7]
  - @backstage/core@0.6.0
  - @backstage/theme@0.2.3

## 0.2.3

### Patch Changes

- Updated dependencies [efd6ef753]
- Updated dependencies [a187b8ad0]
  - @backstage/core@0.5.0

## 0.2.2

### Patch Changes

- Updated dependencies [2527628e1]
- Updated dependencies [1c69d4716]
- Updated dependencies [1665ae8bb]
- Updated dependencies [04f26f88d]
- Updated dependencies [ff243ce96]
  - @backstage/core@0.4.0
  - @backstage/theme@0.2.2

## 0.2.1

### Patch Changes

- Updated dependencies [7b37d65fd]
- Updated dependencies [4aca74e08]
- Updated dependencies [e8f69ba93]
- Updated dependencies [0c0798f08]
- Updated dependencies [0c0798f08]
- Updated dependencies [199237d2f]
- Updated dependencies [6627b626f]
- Updated dependencies [4577e377b]
  - @backstage/core@0.3.0
  - @backstage/theme@0.2.1

## 0.2.0

### Minor Changes

- 28edd7d29: Create backend plugin through CLI

### Patch Changes

- Updated dependencies [819a70229]
- Updated dependencies [ae5983387]
- Updated dependencies [0d4459c08]
- Updated dependencies [482b6313d]
- Updated dependencies [1c60f716e]
- Updated dependencies [144c66d50]
- Updated dependencies [b79017fd3]
- Updated dependencies [6d97d2d6f]
- Updated dependencies [93a3fa3ae]
- Updated dependencies [782f3b354]
- Updated dependencies [2713f28f4]
- Updated dependencies [406015b0d]
- Updated dependencies [82759d3e4]
- Updated dependencies [ac8d5d5c7]
- Updated dependencies [ebca83d48]
- Updated dependencies [aca79334f]
- Updated dependencies [c0d5242a0]
- Updated dependencies [3beb5c9fc]
- Updated dependencies [754e31db5]
- Updated dependencies [1611c6dbc]
  - @backstage/core@0.2.0
  - @backstage/theme@0.2.0
