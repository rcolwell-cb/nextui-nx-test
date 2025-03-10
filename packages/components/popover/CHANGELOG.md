## 2.3.0 (2024-06-10)


### 🚀 Features

- add `updatePositionDeps` prop to popover component

- **popover:** popover & tooltip shared logic moved to aria-utils, popover in progress

- **popover:** needless container removed

- **root:** react aria packages upgraded to the latest version

- **popover:** component created, a11y passing, tests passing

- **root:** new snapshot published

- **popover:** a11y improved, titleProps passed by render props, form auto focus added

- **popover:** backdrop support added

- **dropdown:** initial structure

- **dropdown:** structure improved

- **root:** new snapshot

- **image:** image component added

- **modal:** initial structure created

- **modal:** implementation done

- **modal:** initial tests added

- **modal:** new snapshot

- **components:** focus visible & other states are now handled by data properties

- **root:** new snapshot

- **navbar:** navbar menu implemented

- **navbar:** open/close animation implemented in framer, tests added

- **navbar:** tests added, animations improved

- **navbar:** blur styles improved

- **table:** sortable and load-more examples added

- **table:** component done

- **root:** divider and kbd components added, docs in progress

- **root:** tabs component created, animation improved

- **root:** tsup banner added to support use client directive

- **docs:** second section done desktop

- **docs:** a11y and responsive improved

- **docs:** dark mode section improved

- **docs:** demo modal for code examples added

- **docs:** introduction and installation docs in progress

- **docs:** installations and frameworks guides added

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

- **docs:** popover examples added

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

- **root:** extendStyles renamed to extendVariants, compound and default variants support added

- **root:** new snapshot

- **docs:** extendVariants slots support

- **docs:** new snapshot, release blog in progress

- **root:** v2 published

- **root:** qa github action added

- **calendar:** initial structure


### 🩹 Fixes

- added aria hide outside to popover

- add peer dependencies

- plop template error

- revise shouldCloseOnInteractOutside for FreeSoloPopover

- lazy motion forward ref issue

- incorrect level of m.div

- lazyMotion forwardRef issue

- popover-based focus behaviour

- **popover:** placements

- **root:** card npm pkg

- **docs:** lsc navbar fixed

- **root:** button ring and examples

- **docs:** modal dynamic height, snadpack editor replaced by codeblock

- **pagination:** item tap highlight transparent

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

- **popover:** use layout effect on the server warning

- **popover:** allow pass custom z-index

- **dropdown:** popover and dropdown fixes

- **root:** peer dependecies update only when out of range

- **core:** update peer dependencies for several packages

- **popover:** isDismissable prop passed to aria popover hook

- **docs:** typos

- **components:** popover closing issue in autocomplete with open modal

- **popover:** unexpected props on a DOM element

- **popover:** isDisabled prop on a DOM element

- **popover:** ref not beign passed

- **popover:** trigger disabled prop warning

- **system:** listbox href issue (experimental)


### 🧱 Updated Dependencies

- Updated @nextui-org/use-safe-layout-effect to 2.2.0
- Updated @nextui-org/shared-utils to 2.2.0
- Updated @nextui-org/react-utils to 2.2.0
- Updated @nextui-org/use-aria-button to 2.2.0
- Updated @nextui-org/theme to 2.4.0


### ❤️  Thank You

- Frozen FIsh
- Jakob Guddas
- Junior Garcia
- Sung Ye In
- u3u
- աӄա

# @nextui-org/popover

## 2.1.23

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

- Updated dependencies [[`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a)]:
  - @nextui-org/button@2.0.33
  - @nextui-org/use-aria-button@2.0.8
  - @nextui-org/aria-utils@2.0.20
  - @nextui-org/framer-utils@2.0.20

## 2.1.22

### Patch Changes

- [#2854](https://github.com/nextui-org/nextui/pull/2854) [`3b14c21e0`](https://github.com/nextui-org/nextui/commit/3b14c21e02fedf15d7d22e911109dac60c4e780e) Thanks [@wingkwong](https://github.com/wingkwong)! - Revise popover-based focus behaviours (#2849, #2834, #2779, #2962, #2872, #2974, #1920, #1287, #3060)

- [#2929](https://github.com/nextui-org/nextui/pull/2929) [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Add support for disabling the animations globally.

- Updated dependencies [[`3b14c21e0`](https://github.com/nextui-org/nextui/commit/3b14c21e02fedf15d7d22e911109dac60c4e780e), [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2)]:
  - @nextui-org/aria-utils@2.0.19
  - @nextui-org/button@2.0.32
  - @nextui-org/framer-utils@2.0.19

## 2.1.21

### Patch Changes

- Updated dependencies []:
  - @nextui-org/button@2.0.31

## 2.1.20

### Patch Changes

- [#2784](https://github.com/nextui-org/nextui/pull/2784) [`183a4a6cf`](https://github.com/nextui-org/nextui/commit/183a4a6cfda193a076a4a30550ab93b72d51002d) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix `isDisabled` prop warning on NextUI components that don't support this property, it is also fixed for non-NextUI components.

- Updated dependencies [[`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0)]:
  - @nextui-org/aria-utils@2.0.18
  - @nextui-org/framer-utils@2.0.18
  - @nextui-org/react-utils@2.0.13
  - @nextui-org/button@2.0.30

## 2.1.19

### Patch Changes

- [`9e5dd8ce3`](https://github.com/nextui-org/nextui/commit/9e5dd8ce37c94c9ca1ba7b2049a6e55f1803fee9) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix ref not beign passed

## 2.1.18

### Patch Changes

- [#2741](https://github.com/nextui-org/nextui/pull/2741) [`f89356691`](https://github.com/nextui-org/nextui/commit/f89356691cecb8e54f5f820b2b4491537e7c11f3) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixes isDisabled prop on a DOM element

## 2.1.17

### Patch Changes

- Updated dependencies []:
  - @nextui-org/button@2.0.29
  - @nextui-org/aria-utils@2.0.17
  - @nextui-org/framer-utils@2.0.17
  - @nextui-org/react-utils@2.0.12

## 2.1.16

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fixed the issue where only two keyframes were supported with spring and inertia animations.

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added

  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated

- [#2494](https://github.com/nextui-org/nextui/pull/2494) [`a05aef0ac`](https://github.com/nextui-org/nextui/commit/a05aef0acb5a7b000c8131e8ba4f50f0adec01e5) Thanks [@wingkwong](https://github.com/wingkwong)! - fixed popover closing issue in autocomplete with open modal (#2475, #2082, #1987)

- [#2536](https://github.com/nextui-org/nextui/pull/2536) [`2b9f89023`](https://github.com/nextui-org/nextui/commit/2b9f89023ac087016083dcc205703ae1b2bc9cb8) Thanks [@wingkwong](https://github.com/wingkwong)! - revise shouldCloseOnInteractOutside for FreeSoloPopover

- [#2522](https://github.com/nextui-org/nextui/pull/2522) [`c5049edfd`](https://github.com/nextui-org/nextui/commit/c5049edfde7edaee2081d70e581739be9dcae2f9) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed unexpected props on a DOM element (#2474)

- [#2611](https://github.com/nextui-org/nextui/pull/2611) [`8761168d3`](https://github.com/nextui-org/nextui/commit/8761168d3459cd83ce571f4e65eb8ea6db8516ef) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed lazy motion forwardRef issue

- [#2616](https://github.com/nextui-org/nextui/pull/2616) [`eb51bf226`](https://github.com/nextui-org/nextui/commit/eb51bf226170e4bb37ae30990d1c3aa26d8c504b) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed incorrect level of m.div

- [#2458](https://github.com/nextui-org/nextui/pull/2458) [`7263daca0`](https://github.com/nextui-org/nextui/commit/7263daca08674338eb28529315070337ba0dfc17) Thanks [@wingkwong](https://github.com/wingkwong)! - fix(autocomplete): support isReadOnly for dynamic collections in Autocomplete

- [#2464](https://github.com/nextui-org/nextui/pull/2464) [`2894aecca`](https://github.com/nextui-org/nextui/commit/2894aecca1a2ef0dfb3066b9b8df24ce48c99dae) Thanks [@mezotv](https://github.com/mezotv)! - Changes the motion important to the more lightweight m component in framer motion to only load the required features.

- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14)]:
  - @nextui-org/button@2.0.28
  - @nextui-org/use-aria-button@2.0.7
  - @nextui-org/aria-utils@2.0.16
  - @nextui-org/framer-utils@2.0.16
  - @nextui-org/react-utils@2.0.11
  - @nextui-org/shared-utils@2.0.5
  - @nextui-org/use-safe-layout-effect@2.0.5

## 2.1.15

### Patch Changes

- [#2390](https://github.com/nextui-org/nextui/pull/2390) [`a235e324b`](https://github.com/nextui-org/nextui/commit/a235e324b9ee0c7d4f6af23b086860ac112ff633) Thanks [@u3u](https://github.com/u3u)! - Add `updatePositionDeps` prop to popover component

- [#2032](https://github.com/nextui-org/nextui/pull/2032) [`01aedcf09`](https://github.com/nextui-org/nextui/commit/01aedcf09b63daafef9ff5e0465040c0c91c809e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #2025 isDismissable prop passed to the aria-popover hook.

- Updated dependencies []:
  - @nextui-org/button@2.0.27

## 2.1.14

### Patch Changes

- Updated dependencies []:
  - @nextui-org/button@2.0.26
  - @nextui-org/aria-utils@2.0.15
  - @nextui-org/framer-utils@2.0.15

## 2.1.13

### Patch Changes

- Updated dependencies []:
  - @nextui-org/button@2.0.25
  - @nextui-org/aria-utils@2.0.14
  - @nextui-org/framer-utils@2.0.14

## 2.1.12

### Patch Changes

- [#1877](https://github.com/nextui-org/nextui/pull/1877) [`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated, changeset config changed to update peer dependencies only when out of range

- Updated dependencies [[`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648)]:
  - @nextui-org/button@2.0.24
  - @nextui-org/aria-utils@2.0.13
  - @nextui-org/framer-utils@2.0.13

## 2.1.11

### Patch Changes

- [#1874](https://github.com/nextui-org/nextui/pull/1874) [`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated to avoid the peer conflicts issue.

- Updated dependencies [[`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0)]:
  - @nextui-org/button@2.0.23
  - @nextui-org/system@2.0.12
  - @nextui-org/aria-utils@2.0.12
  - @nextui-org/framer-utils@2.0.12

## 2.1.10

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/button@2.0.22
  - @nextui-org/system@2.0.11
  - @nextui-org/theme@2.1.10
  - @nextui-org/use-aria-button@2.0.6
  - @nextui-org/aria-utils@2.0.11
  - @nextui-org/framer-utils@2.0.11
  - @nextui-org/react-utils@2.0.10
  - @nextui-org/shared-utils@2.0.4

## 2.1.9

### Patch Changes

- Updated dependencies [[`ceddd0d1d`](https://github.com/nextui-org/nextui/commit/ceddd0d1d941a669bab78ef7439a29531cff99a2), [`425a034bc`](https://github.com/nextui-org/nextui/commit/425a034bca4aa5a86cfe4bc47c084366a7ad7e87)]:
  - @nextui-org/button@2.0.21
  - @nextui-org/theme@2.1.9
  - @nextui-org/system@2.0.10
  - @nextui-org/react-utils@2.0.9
  - @nextui-org/aria-utils@2.0.10
  - @nextui-org/framer-utils@2.0.10

## 2.1.8

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/button@2.0.20
  - @nextui-org/system@2.0.9
  - @nextui-org/theme@2.1.8
  - @nextui-org/use-aria-button@2.0.5
  - @nextui-org/aria-utils@2.0.9
  - @nextui-org/framer-utils@2.0.9
  - @nextui-org/react-utils@2.0.8
  - @nextui-org/shared-utils@2.0.3

## 2.1.7

### Patch Changes

- [#1589](https://github.com/nextui-org/nextui/pull/1589) [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria packages upgraded

- Updated dependencies [[`a3be419cb`](https://github.com/nextui-org/nextui/commit/a3be419cb3c693ae8cace15f9a863274d759ddb1), [`5c30e0481`](https://github.com/nextui-org/nextui/commit/5c30e04811ef9f973d6b59107c909db72d9876b5), [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2)]:
  - @nextui-org/theme@2.1.7
  - @nextui-org/use-aria-button@2.0.4
  - @nextui-org/aria-utils@2.0.8
  - @nextui-org/button@2.0.19
  - @nextui-org/system@2.0.8
  - @nextui-org/framer-utils@2.0.8

## 2.1.6

### Patch Changes

- Updated dependencies [[`7c8341035`](https://github.com/nextui-org/nextui/commit/7c8341035dbdd120cd78221b3cabab2e40e7478d)]:
  - @nextui-org/theme@2.1.6
  - @nextui-org/button@2.0.18

## 2.1.5

### Patch Changes

- Updated dependencies [[`d61428d9e`](https://github.com/nextui-org/nextui/commit/d61428d9e6c1c0590593fb1f0136e226051b7e23), [`4db10a47e`](https://github.com/nextui-org/nextui/commit/4db10a47e96ad8315b5b96c2ff15574ac0fdeecc)]:
  - @nextui-org/theme@2.1.5
  - @nextui-org/system@2.0.7
  - @nextui-org/button@2.0.17
  - @nextui-org/aria-utils@2.0.7
  - @nextui-org/framer-utils@2.0.7

## 2.1.4

### Patch Changes

- Updated dependencies [[`043b8420c`](https://github.com/nextui-org/nextui/commit/043b8420cfb659cbb6bb36404807ec3cc8ac8592), [`641bf0885`](https://github.com/nextui-org/nextui/commit/641bf0885b6af2d7f36f27d83716a441975a5ca5)]:
  - @nextui-org/theme@2.1.4
  - @nextui-org/system@2.0.6
  - @nextui-org/button@2.0.16
  - @nextui-org/aria-utils@2.0.6
  - @nextui-org/framer-utils@2.0.6

## 2.1.3

### Patch Changes

- Updated dependencies [[`5702287e5`](https://github.com/nextui-org/nextui/commit/5702287e5622a8f0a0326c7cc0c200808c7971a8)]:
  - @nextui-org/theme@2.1.3
  - @nextui-org/button@2.0.15

## 2.1.2

### Patch Changes

- [#1458](https://github.com/nextui-org/nextui/pull/1458) [`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix dropdown trigger events and popover arrow styles

- Updated dependencies [[`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01)]:
  - @nextui-org/button@2.0.14
  - @nextui-org/theme@2.1.2

## 2.1.1

### Patch Changes

- Updated dependencies [[`cc839cdd`](https://github.com/nextui-org/nextui/commit/cc839cdd1fd54931bfba137e2f9b5e8007a7e47d)]:
  - @nextui-org/theme@2.1.1
  - @nextui-org/button@2.0.13

## 2.1.0

### Minor Changes

- [#1313](https://github.com/nextui-org/nextui/pull/1313) [`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New components:

  - Select
  - Listbox
  - ScrollShadow

### Patch Changes

- Updated dependencies [[`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e)]:
  - @nextui-org/theme@2.1.0
  - @nextui-org/button@2.0.12
  - @nextui-org/react-utils@2.0.7

## 2.0.12

### Patch Changes

- [#1410](https://github.com/nextui-org/nextui/pull/1410) [`6e7e834c2`](https://github.com/nextui-org/nextui/commit/6e7e834c2dc14c21b087da792c0576ab464a4a4a) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Popover style prop merged with the one returned by react-aria, other components merge props improvements

## 2.0.11

### Patch Changes

- [`406336269`](https://github.com/nextui-org/nextui/commit/40633626991d11f251619508f151dd7f435bda25) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - fix #1386 useLayoutEffect on the server warning

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.6
  - @nextui-org/button@2.0.11

## 2.0.10

### Patch Changes

- Updated dependencies [[`d0341020`](https://github.com/nextui-org/nextui/commit/d0341020e6d865ad3f0d3646fa70a24de75a722b)]:
  - @nextui-org/theme@2.0.5
  - @nextui-org/button@2.0.10

## 2.0.9

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.5
  - @nextui-org/button@2.0.9

## 2.0.8

### Patch Changes

- [#1359](https://github.com/nextui-org/nextui/pull/1359) [`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - \n

  - react-aria packages upgraded to the latest version
  - image storybooks fixed
  - other bug fixes..

- Updated dependencies [[`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171)]:
  - @nextui-org/framer-utils@2.0.5
  - @nextui-org/use-aria-button@2.0.3
  - @nextui-org/aria-utils@2.0.5
  - @nextui-org/button@2.0.8
  - @nextui-org/system@2.0.5

## 2.0.7

### Patch Changes

- Updated dependencies [[`710395f3`](https://github.com/nextui-org/nextui/commit/710395f3a2ca44238332237a49e948c933abe63d)]:
  - @nextui-org/system@2.0.4
  - @nextui-org/button@2.0.7
  - @nextui-org/aria-utils@2.0.4
  - @nextui-org/framer-utils@2.0.4

## 2.0.6

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.4
  - @nextui-org/button@2.0.6

## 2.0.5

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.3
  - @nextui-org/button@2.0.5

## 2.0.4

### Patch Changes

- [#1301](https://github.com/nextui-org/nextui/pull/1301) [`d794225c`](https://github.com/nextui-org/nextui/commit/d794225cb75121db3a72f430739b4eaacd1cf8b7) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Plugin types adapted to work with latest version of postcss

- Updated dependencies [[`d794225c`](https://github.com/nextui-org/nextui/commit/d794225cb75121db3a72f430739b4eaacd1cf8b7)]:
  - @nextui-org/button@2.0.4
  - @nextui-org/theme@2.0.4

## 2.0.3

### Patch Changes

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports
- Updated dependencies [[`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782), [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f)]:
  - @nextui-org/react-utils@2.0.2
  - @nextui-org/button@2.0.3
  - @nextui-org/system@2.0.3
  - @nextui-org/theme@2.0.3
  - @nextui-org/use-aria-button@2.0.2
  - @nextui-org/aria-utils@2.0.3
  - @nextui-org/framer-utils@2.0.3
  - @nextui-org/shared-utils@2.0.2

## 2.0.2

### Patch Changes

- Updated dependencies [[`459ac5ed`](https://github.com/nextui-org/nextui/commit/459ac5ed4537942517803ba14129226a791d6feb)]:
  - @nextui-org/theme@2.0.2
  - @nextui-org/button@2.0.2
  - @nextui-org/system@2.0.2
  - @nextui-org/aria-utils@2.0.2
  - @nextui-org/framer-utils@2.0.2

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated

- Updated dependencies [[`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140), [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140)]:
  - @nextui-org/framer-utils@2.0.1
  - @nextui-org/shared-utils@2.0.1
  - @nextui-org/use-aria-button@2.0.1
  - @nextui-org/react-utils@2.0.1
  - @nextui-org/aria-utils@2.0.1
  - @nextui-org/button@2.0.1
  - @nextui-org/system@2.0.1
  - @nextui-org/theme@2.0.1
