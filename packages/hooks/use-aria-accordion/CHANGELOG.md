## 2.2.0 (2024-06-10)


### 🚀 Features

- **root:** progress and accordion build size reduced by spliting aria utils

- **root:** react aria packages upgraded to the latest version

- **root:** new snapshot published

- **root:** divider and kbd components added, docs in progress

- **root:** tsup banner added to support use client directive

- **docs:** home migrated to app directory

- **docs:** migrated to app directory

- **root:** packages updated

- **root:** pagination docs done, colors a11y improved

- **docs:** navbar in progress

- **root:** layout configuration added to the tailwind plugin, components were adapted

- **root:** react aria packages upgraded, SSRProvider removed since is no longer needed

- **root:** needless useId removed since react-aria now supports react 18

- **docs:** navbar docs fixed, popover and dropdown animations improved

- **root:** extendStyles renamed to extendVariants, compound and default variants support added

- **calendar:** initial structure


### 🩹 Fixes

- plop template error

- **plugin:** lodash dependencies

- **accordion:** accordion is no longer preventing spacebar

- **accordion:** ctrl+a shortcut inside

- **system:** listbox href issue (experimental)


### ❤️  Thank You

- black197
- Frozen FIsh
- Junior Garcia
- աӄա

# @nextui-org/use-aria-accordion

## 2.0.5

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

## 2.0.4

### Patch Changes

- [#2063](https://github.com/nextui-org/nextui/pull/2063) [`10f2b8f42`](https://github.com/nextui-org/nextui/commit/10f2b8f42b1d208e4edea366c6bbc37ef8614ef6) Thanks [@black197](https://github.com/black197)! - Fixes ctrl+a keyboard shortcut enabled inside Accordion with `selectionMode="multiple"` (#2055)

## 2.0.3

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated

## 2.0.2

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

## 2.0.1

### Patch Changes

- [#1630](https://github.com/nextui-org/nextui/pull/1630) [`bc424948c`](https://github.com/nextui-org/nextui/commit/bc424948c70ddbc5b00a9d732dafcd5008c78b1f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #1405 and #1608 accordion is no longer preventing spacebar key for Input/Textarea components
