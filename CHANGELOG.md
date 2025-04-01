# @justmiracle/result

## 2.0.0

### Major Changes

- 06b2830: BREAKING CHANGES: Complete API overhaul to "fuck around and find out" pattern

  - Renamed `ok` to `fuckAround`
  - Renamed `err` to `findOut`
  - Renamed `isOk` to `didItWork`
  - Renamed `isErr` to `didYouFuckUp`
  - Renamed `error` field to `consequences`
  - Updated types to `FuckedAround` and `FoundOut`
  - Updated documentation to reflect new naming

  Migration Guide:

  - Replace all `ok(value)` with `fuckAround(value)`
  - Replace all `err(error)` with `findOut(error)`
  - Replace all `isOk(result)` with `didItWork(result)`
  - Replace all `isErr(result)` with `didYouFuckUp(result)`
  - Update type references from `Ok/Err` to `FuckedAround/FoundOut`
  - Update error field references to consequences

## 1.2.0

### Minor Changes

- 831cb94: added makeSafe

## 1.1.3

### Patch Changes

- 88c1d1e: test: added type test for map function
- f07b71a: updated the return type of err util

## 1.1.2

### Patch Changes

- 73dccef: Corrected the entryfile path in package.json

## 1.1.1

### Patch Changes

- b47796b: fixed npmignore and README

## 1.1.0

### Minor Changes

- c37262b: Added CI for quality checking and publishing
