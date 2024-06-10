## 2.2.0 (2024-06-10)


### 🚀 Features

- **components:** arrow icon added to the collapse item, new package added

- **root:** tsup build improved

- **tooltip:** migrated to react-aria and tw

- **root:** react 18, react aria packages upgraded

- **root:** stitches removed globally, react 18 implemented, pnpm setup changed

- **components:** prop getter type implemented to reduced the size of d.ts files

- **root:** first snapshot version

- **root:** clean package file taken from root

- **root:** new snapshot

- **root:** script added to inject the "use client" directive

- **root:** react aria id generation replaced by React 18 useId hook

- **chore:** progress component exported in the main package

- **root:** new snapshot

- **root:** new snapshot release

- **root:** new snapshot release

- **root:** progress and accordion build size reduced by spliting aria utils

- **root:** new snapshot

- **root:** new version

- **root:** new snapshot published

- **popover:** a11y improved, titleProps passed by render props, form auto focus added

- **popover:** backdrop support added

- **root:** new snapshot

- **image:** image component added

- **modal:** new snapshot

- **root:** new snapshot

- **navbar:** tests added, animations improved

- **table:** component done

- **root:** divider and kbd components added, docs in progress

- **root:** tabs component created, animation improved

- **root:** tsup banner added to support use client directive

- **docs:** home migrated to app directory

- **docs:** migrated to app directory

- **root:** packages updated

- **docs:** a11y and performance optimizations on landing page

- **root:** modal, popover and navbar menu issues fixed, navbar styles simplified, docs improved

- **root:** new snapshot

- **docs:** modal docs done

- **docs:** search cmdk implemented

- **root:** modal improved, flat colors changed

- **root:** new snapshot

- **docs:** pagination in progress

- **root:** pagination docs done, colors a11y improved

- **docs:** pagination improved

- **paignation:** automatic scroll added, styles improved

- **root:** utilities, update effect hook added, tabs improvements

- **root:** pagination and tabs improvements, cmdk recent searches fixed

- **root:** new snapshot

- **root:** new snapshot version

- **docs:** dropdown in progress

- **docs:** dropdown docs almost done

- **root:** semantic colors improved, dropdown search meta updated

- **docs:** dropdown docs in progress, some styles changes

- **docs:** dropdown styles and API changed, custom styles examples improved

- **docs:** dropdown done

- **docs:** navbar in progress

- **root:** layout configuration added to the tailwind plugin, components were adapted

- **root:** react aria packages upgraded, SSRProvider removed since is no longer needed

- **root:** needless useId removed since react-aria now supports react 18

- **docs:** navbar docs fixed, popover and dropdown animations improved

- **root:** animations management improved

- **root:** new ripple pkg created

- **root:** accordion animation improved, units introduced, button spacing migrated to units

- **accordion:** transition improved

- **modal:** mobile transition changed

- **root:** new snap

- **navbar:** docs improved, new release published

- **docs:** table docs in progress

- **docs:** more table examples added

- **docs:** table custom styles example added, api added

- **docs:** new snapshot, sandpack fixes, table fixes

- **docs:** theme docs in progress

- **docs:** customization docs added

- **docs:** override styles in progress

- **docs:** customization part done. new snapshot

- **root:** extendStyles function in progress

- **root:** extendStyles renamed to extendVariants, compound and default variants support added

- **root:** new snapshot

- **docs:** extendVariants slots support

- **docs:** new snapshot, release blog in progress

- **root:** v2 published

- **root:** RSC components added, packages modified, filter dom props  function adapted

- **calendar:** initial structure


### 🩹 Fixes

- plop template error

- **drip:** animation

- **input:** default label placement

- **dropdown:** styles fixed

- **plugin:** lodash dependencies

- **root:** radio and checkbox state memoized, accordion transition changed

- **root:** tabs perf issues, accordion overflow

- **root:** input, textarea and accordion perf issues

- **input:** on value change

- **root:** tailwind variants updated to fix the perf issues

- **progress:** max vand mix values fixed

- **root:** table sandpacks, input label placeholder

- **table:** styles issues

- **core:** new snapshot, system pkg build fixed

- **core:** export * from not supported on client components


### 🧱 Updated Dependencies

- Updated @nextui-org/react-rsc-utils to 2.2.0
- Updated @nextui-org/shared-utils to 2.2.0


### ❤️  Thank You

- Frozen FIsh
- Junior Garcia

# @nextui-org/react-utils

## 2.0.13

### Patch Changes

- [#2789](https://github.com/nextui-org/nextui/pull/2789) [`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #2749 Introduced named exports for several UI-related packages to enhance modularity and usability in Next.js projects.

## 2.0.12

### Patch Changes

- Updated dependencies [[`74eda3128`](https://github.com/nextui-org/nextui/commit/74eda312883b2e17df26f71442aba9fb3cd240be)]:
  - @nextui-org/react-rsc-utils@2.0.12

## 2.0.11

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated
- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`f864dc397`](https://github.com/nextui-org/nextui/commit/f864dc3974993b29ea5048483d7e0e998e8bef56)]:
  - @nextui-org/react-rsc-utils@2.0.11
  - @nextui-org/shared-utils@2.0.5

## 2.0.10

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/react-rsc-utils@2.0.10
  - @nextui-org/shared-utils@2.0.4

## 2.0.9

### Patch Changes

- Updated dependencies [[`cdc30db14`](https://github.com/nextui-org/nextui/commit/cdc30db14c75d9c2e05d928e52c08a49cc1b6437)]:
  - @nextui-org/react-rsc-utils@2.0.9

## 2.0.8

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/react-rsc-utils@2.0.8
  - @nextui-org/shared-utils@2.0.3

## 2.0.7

### Patch Changes

- Updated dependencies [[`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e)]:
  - @nextui-org/react-rsc-utils@2.0.7

## 2.0.6

### Patch Changes

- Updated dependencies [[`94d65df53`](https://github.com/nextui-org/nextui/commit/94d65df53392f0013438f4ca48716011e79a3c56)]:
  - @nextui-org/react-rsc-utils@2.0.6

## 2.0.5

### Patch Changes

- Updated dependencies [[`fe03c42f`](https://github.com/nextui-org/nextui/commit/fe03c42fa144b5066ebc8ad39c144aeef437d2c6), [`fe03c42f`](https://github.com/nextui-org/nextui/commit/fe03c42fa144b5066ebc8ad39c144aeef437d2c6)]:
  - @nextui-org/react-rsc-utils@2.0.5

## 2.0.4

### Patch Changes

- Updated dependencies [[`d13a14fa`](https://github.com/nextui-org/nextui/commit/d13a14facc1a92dac72e58a93e0452a86a2243c6)]:
  - @nextui-org/react-rsc-utils@2.0.4

## 2.0.3

### Patch Changes

- Updated dependencies [[`42001647`](https://github.com/nextui-org/nextui/commit/4200164712b6eb4b37a14fe9e005844ff770a180)]:
  - @nextui-org/react-rsc-utils@2.0.3

## 2.0.2

### Patch Changes

- [#1289](https://github.com/nextui-org/nextui/pull/1289) [`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - "use client" directive removed from components that didn't need it

  - packages adapted to support RSC imports
  - filterDomProps function was modified to enable/disabled it

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports
- Updated dependencies [[`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f)]:
  - @nextui-org/react-rsc-utils@2.0.2
  - @nextui-org/shared-utils@2.0.2

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated

- Updated dependencies [[`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140), [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140)]:
  - @nextui-org/shared-utils@2.0.1
