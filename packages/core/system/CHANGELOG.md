## 2.4.0 (2024-06-10)


### 🚀 Features

- added locale prop to NextUIProvider

- switch default validationBehavior to aria and allow switching via props

- **root:** structure improvements, initial build working

- **root:** improving repo structure

- **root:** build working, plop templates changed, jest upgraded

- **components:** text compoenent added, structure improved

- **components:** divider component added

- **components:** link component in progress, plop fixed

- **components:** link component added

- **core:** root function added to use NextUI.<element> as a component, snippet structure started, plop templated improved

- **system:** root proxy types improved

- **components:** checkbox component added, react-aria dependecies were separated

- **root:** generated types size reduced

- **system:** media and utils are now customizable!

- **system:** tokens types mapped to use the prop without the "$" symbol

- **system:** scale variants can be generated dynamically

- **root:** tsup build improved

- **link:** stories improved

- **snippet:** migrated

- **root:** react 18, react aria packages upgraded

- **root:** stitches removed globally, react 18 implemented, pnpm setup changed

- **components:** prop getter type implemented to reduced the size of d.ts files

- **root:** first snapshot version

- **root:** clean package file taken from root

- **root:** new snapshot

- **root:** script added to inject the "use client" directive

- **root:** react aria id generation replaced by React 18 useId hook

- **progress:** component done, needless useId removed, SSR provider exported again

- **chore:** progress component exported in the main package

- **root:** new snapshot

- **root:** new snapshot release

- **root:** new snapshot release

- **root:** progress and accordion build size reduced by spliting aria utils

- **root:** new snapshot

- **root:** new version

- **popover:** popover & tooltip shared logic moved to aria-utils, popover in progress

- **root:** react aria packages upgraded to the latest version

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

- **docs:** second section done desktop

- **docs:** a11y and responsive improved

- **docs:** demo modal for code examples added

- **root:** new snapshot

- **button:** spinner added

- **docs:** accordion done

- **docs:** badge done

- **docs:** chip and circular progress done

- **docs:** navbar manifest added

- **docs:** import tabs added, link docs in progress

- **docs:** progress done, internal APi improved

- **docs:** skeleton docs in progress

- **docs:** skeleton docs completed, navbar menu toggle fixed

- **docs:** snippet done

- **docs:** input docs done

- **docs:** docs structure improved, steps added and toc autoscroll

- **docs:** headings and toc enhacements

- **docs:** textarea docs done

- **docs:** some improvements applied, button and spinner styles fixed

- **root:** react aria packages upgraded, fix input types

- **docs:** radio group done

- **docs:** switch docs done

- **docs:** popover docs almost done

- **docs:** popover docs done

- **docs:** tooltip docs done

- **docs:** tabs docs done

- **docs:** accordion improved, badge fixed, modal started

- **modal:** improved on mobile

- **docs:** modal docs in progress

- **root:** warning and success colors a11y improved on light theme, docs bugs fixed

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

- **root:** new snapshot

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

- **root:** extendStyles function created for component without slots

- **root:** extendStyles renamed to extendVariants, compound and default variants support added

- **root:** new snapshot

- **docs:** extendVariants slots support

- **docs:** new snapshot, release blog in progress

- **root:** v2 published

- **root:** RSC components added, packages modified, filter dom props  function adapted

- **system:** extend props for nextui provider

- **calendar:** initial structure


### 🩹 Fixes

- add peer dependencies

- plop template error

- **drip:** animation

- **input:** default label placement

- **root:** card npm pkg

- **docs:** lsc navbar fixed

- **root:** button ring and examples

- **docs:** modal dynamic height, snadpack editor replaced by codeblock

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

- **root:** peer dependecies update only when out of range

- **docs:** typos

- **core:** named exports and client directive

- **core:** export * from not supported on client components

- **system:** listbox href issue (experimental)


### 🧱 Updated Dependencies

- Updated @nextui-org/react-utils to 2.2.0


### ❤️  Thank You

- Frozen FIsh
- Jakob Guddas
- Junior Garcia
- Ryo Matsukawa
- Sung Ye In
- Tianen Pang
- աӄա

# @nextui-org/system

## 2.2.1

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed listbox href issue (#3105)

- Updated dependencies []:
  - @nextui-org/system-rsc@2.1.2

## 2.2.0

### Minor Changes

- [#2987](https://github.com/nextui-org/nextui/pull/2987) [`540aa2124`](https://github.com/nextui-org/nextui/commit/540aa2124b45b65a40e73f5aea2b90405fe1fe9a) Thanks [@ryo-manba](https://github.com/ryo-manba)! - Change validationBehavior from native to aria by default, with the option to change via props.

### Patch Changes

- [#2915](https://github.com/nextui-org/nextui/pull/2915) [`e3afa4789`](https://github.com/nextui-org/nextui/commit/e3afa4789a1ac0fa929b2acaca5bd9c520567ab8) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - The `cn` utility was moved the `theme` package and updated to support NextUI custom classes.

- [#2929](https://github.com/nextui-org/nextui/pull/2929) [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Add support for disabling the animations globally.

- Updated dependencies [[`e3afa4789`](https://github.com/nextui-org/nextui/commit/e3afa4789a1ac0fa929b2acaca5bd9c520567ab8), [`1109baea6`](https://github.com/nextui-org/nextui/commit/1109baea6ac6aa3feb2be90ef065f61b2c2a06a9)]:
  - @nextui-org/system-rsc@2.1.2

## 2.1.2

### Patch Changes

- [#2789](https://github.com/nextui-org/nextui/pull/2789) [`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #2749 Introduced named exports for several UI-related packages to enhance modularity and usability in Next.js projects.

- Updated dependencies [[`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0)]:
  - @nextui-org/react-utils@2.0.13
  - @nextui-org/system-rsc@2.1.1

## 2.1.1

### Patch Changes

- [#2758](https://github.com/nextui-org/nextui/pull/2758) [`74eda3128`](https://github.com/nextui-org/nextui/commit/74eda312883b2e17df26f71442aba9fb3cd240be) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Named exports for rsc packages, "use client;" directive added to "@nextui-org/react" package

- Updated dependencies [[`74eda3128`](https://github.com/nextui-org/nextui/commit/74eda312883b2e17df26f71442aba9fb3cd240be)]:
  - @nextui-org/system-rsc@2.1.1
  - @nextui-org/react-utils@2.0.12

## 2.1.0

### Minor Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated
- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`c5049edfd`](https://github.com/nextui-org/nextui/commit/c5049edfde7edaee2081d70e581739be9dcae2f9)]:
  - @nextui-org/system-rsc@2.1.0
  - @nextui-org/react-utils@2.0.11

## 2.0.15

### Patch Changes

- Updated dependencies [[`a978687b0`](https://github.com/nextui-org/nextui/commit/a978687b0736d1e15943ef46628fc4fa0723ddc7)]:
  - @nextui-org/system-rsc@2.0.11

## 2.0.14

### Patch Changes

- Updated dependencies [[`6ecdc278a`](https://github.com/nextui-org/nextui/commit/6ecdc278aba927ee38a799679b8eb99cba99cab9)]:
  - @nextui-org/system-rsc@2.0.10

## 2.0.13

### Patch Changes

- Updated dependencies [[`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648)]:
  - @nextui-org/system-rsc@2.0.9

## 2.0.12

### Patch Changes

- Updated dependencies [[`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0)]:
  - @nextui-org/system-rsc@2.0.8

## 2.0.11

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/system-rsc@2.0.7

## 2.0.10

### Patch Changes

- Updated dependencies [[`f6531c5f6`](https://github.com/nextui-org/nextui/commit/f6531c5f603d7f6308a597962ec6fab62c92fa93)]:
  - @nextui-org/system-rsc@2.0.6

## 2.0.9

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/system-rsc@2.0.5

## 2.0.8

### Patch Changes

- [#1589](https://github.com/nextui-org/nextui/pull/1589) [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria packages upgraded

- Updated dependencies []:
  - @nextui-org/system-rsc@2.0.4

## 2.0.7

### Patch Changes

- Updated dependencies [[`d61428d9e`](https://github.com/nextui-org/nextui/commit/d61428d9e6c1c0590593fb1f0136e226051b7e23)]:
  - @nextui-org/system-rsc@2.0.4

## 2.0.6

### Patch Changes

- [#1513](https://github.com/nextui-org/nextui/pull/1513) [`641bf0885`](https://github.com/nextui-org/nextui/commit/641bf0885b6af2d7f36f27d83716a441975a5ca5) Thanks [@tianenpang](https://github.com/tianenpang)! - Extend props for NextUIProvider and update default locale from en to en-US.

- Updated dependencies []:
  - @nextui-org/system-rsc@2.0.3

## 2.0.5

### Patch Changes

- [#1359](https://github.com/nextui-org/nextui/pull/1359) [`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - \n

  - react-aria packages upgraded to the latest version
  - image storybooks fixed
  - other bug fixes..

## 2.0.4

### Patch Changes

- [#1350](https://github.com/nextui-org/nextui/pull/1350) [`710395f3`](https://github.com/nextui-org/nextui/commit/710395f3a2ca44238332237a49e948c933abe63d) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Needless exports removed from system pkg

## 2.0.3

### Patch Changes

- [#1289](https://github.com/nextui-org/nextui/pull/1289) [`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - "use client" directive removed from components that didn't need it

  - packages adapted to support RSC imports
  - filterDomProps function was modified to enable/disabled it

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports
- Updated dependencies [[`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f)]:
  - @nextui-org/system-rsc@2.0.3

## 2.0.2

### Patch Changes

- Updated dependencies [[`459ac5ed`](https://github.com/nextui-org/nextui/commit/459ac5ed4537942517803ba14129226a791d6feb)]:
  - @nextui-org/theme@2.0.2

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated

- Updated dependencies [[`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140), [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140)]:
  - @nextui-org/theme@2.0.1
