## 2.4.0 (2024-06-10)


### 🚀 Features

- switch default validationBehavior to aria and allow switching via props

- **hooks:** needed hooks to create input added

- **input:** initial structure and styles created

- **input:** api improved

- **input:** start and end content added, new stories

- **input:** styles fixed, input focus when wrapper is clicked applied

- **input:** srotybook improved, custom with hooks example added

- **input:** tests added

- **root:** new version

- **root:** react aria packages upgraded to the latest version

- **root:** new snapshot published

- **popover:** a11y improved, titleProps passed by render props, form auto focus added

- **popover:** backdrop support added

- **root:** new snapshot

- **image:** image component added

- **modal:** new snapshot

- **input:** data management improved

- **root:** new snapshot

- **navbar:** tests added, animations improved

- **navbar:** blur styles improved

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

- **calendar:** initial structure

- **test:** react hook form tests & stories


### 🩹 Fixes

- added missing helper text wrapper to textarea

- add peer dependencies

- plop template error

- **input:** default label placement

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

- **stories:** fixed password field story issues

- **core:** new snapshot, system pkg build fixed

- **input:** duplicate triggering of input events

- **input:** don't always use controlled mode

- **packages:** validation state deprecated, isInvalid prop adjusted

- **select:** without label and input helperWrapper relative

- **root:** peer dependecies update only when out of range

- **core:** update peer dependencies for several packages

- **theme:** update input and select styling and add data attribute for

- **input:** label position and styles

- **textarea:** styles issues and start/end content props added

- **input:** label placement outside when label is missing

- **input:** clearable feature

- **components:** input label overlapping issue

- **docs:** typos

- **components:** number input label #2268 fixed

- **input:** keep input component's position in innerWrapper steady

- **input:** isClearable & add test cases to input

- **system:** listbox href issue (experimental)


### 🧱 Updated Dependencies

- Updated @nextui-org/use-safe-layout-effect to 2.2.0
- Updated @nextui-org/shared-icons to 2.2.0
- Updated @nextui-org/shared-utils to 2.2.0
- Updated @nextui-org/react-utils to 2.2.0
- Updated @nextui-org/theme to 2.4.0


### ❤️  Thank You

- black197
- Frozen FIsh
- Jakob Guddas
- Junior Garcia
- Prakash Choudhary
- Ryo Matsukawa
- Sung Ye In
- Tianen Pang
- Tommaso De Rossi
- աӄա

# @nextui-org/input

## 2.2.1

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

## 2.2.0

### Minor Changes

- [#2987](https://github.com/nextui-org/nextui/pull/2987) [`540aa2124`](https://github.com/nextui-org/nextui/commit/540aa2124b45b65a40e73f5aea2b90405fe1fe9a) Thanks [@ryo-manba](https://github.com/ryo-manba)! - Change validationBehavior from native to aria by default, with the option to change via props.

### Patch Changes

- [#2929](https://github.com/nextui-org/nextui/pull/2929) [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Add support for disabling the animations globally.

## 2.1.21

### Patch Changes

- [#2796](https://github.com/nextui-org/nextui/pull/2796) [`355235320`](https://github.com/nextui-org/nextui/commit/35523532030468837939d127b68bee30bbc4e2b0) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixes the isClearable function in the input component (#2791)

- [#2072](https://github.com/nextui-org/nextui/pull/2072) [`1dacf52f3`](https://github.com/nextui-org/nextui/commit/1dacf52f305a410cbf59d067d1977024d982ad03) Thanks [@black197](https://github.com/black197)! - Fix #2069 keep input component's position steady

## 2.1.20

### Patch Changes

- Updated dependencies [[`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0)]:
  - @nextui-org/react-utils@2.0.13

## 2.1.19

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.12

## 2.1.18

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added

  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fixed react-hook-form uncontrolled components (#1969)

- [#2316](https://github.com/nextui-org/nextui/pull/2316) [`52dafd08f`](https://github.com/nextui-org/nextui/commit/52dafd08f178483e79dc847b61d1c761af26eb8e) Thanks [@mrbadri](https://github.com/mrbadri)! - Add RTL support to the input component

- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14)]:
  - @nextui-org/react-utils@2.0.11
  - @nextui-org/shared-icons@2.0.7
  - @nextui-org/shared-utils@2.0.5

## 2.1.17

### Patch Changes

- [#2371](https://github.com/nextui-org/nextui/pull/2371) [`e4ba43b4e`](https://github.com/nextui-org/nextui/commit/e4ba43b4e39203566614ac0aa58e844e9421c86e) Thanks [@wingkwong](https://github.com/wingkwong)! - fixed input label overlapping issue (#2255)

- [#2028](https://github.com/nextui-org/nextui/pull/2028) [`0ba165f0f`](https://github.com/nextui-org/nextui/commit/0ba165f0fd2257f5b8302b32a9f5eb1ecde8d890) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #1979 labelPlacement is outside when not having a label for input, autocomplete and select components.

- [#2031](https://github.com/nextui-org/nextui/pull/2031) [`436ba1cd8`](https://github.com/nextui-org/nextui/commit/436ba1cd8412dc044651ab38ff2ed770f35377ff) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #1984 input clearable feature fixed

- [#2274](https://github.com/nextui-org/nextui/pull/2274) [`e6f36281c`](https://github.com/nextui-org/nextui/commit/e6f36281cb8bcf6784c2fee47860f618dea9346c) Thanks [@Prakash7895](https://github.com/Prakash7895)! - Fix #2268, when using a number input and with a 0 for the initial value, the label (default or labelPlacement='inside') does not animate to the correct position. Even when the user is setting the value to 0, the label does not alter its state unless a number other than 0 is inputted.

## 2.1.16

### Patch Changes

- [#1928](https://github.com/nextui-org/nextui/pull/1928) [`d2bd008ba`](https://github.com/nextui-org/nextui/commit/d2bd008ba3d4de73f4405f1997b15466efd19a81) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Texarea label validation added to avoid rendering the element when there is no label.

## 2.1.15

### Patch Changes

- [#1923](https://github.com/nextui-org/nextui/pull/1923) [`9189b3fbf`](https://github.com/nextui-org/nextui/commit/9189b3fbf2d6d6cc6566009c71b37d5fcc566291) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Textarea style rounded full styles issues fixed, start and end content props added

- Updated dependencies [[`9189b3fbf`](https://github.com/nextui-org/nextui/commit/9189b3fbf2d6d6cc6566009c71b37d5fcc566291)]:
  - @nextui-org/shared-icons@2.0.6

## 2.1.14

### Patch Changes

- [#1901](https://github.com/nextui-org/nextui/pull/1901) [`6a6d426b1`](https://github.com/nextui-org/nextui/commit/6a6d426b10fa7f92dfb20611e261347027393193) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Label position changed for Select and Input, this avoids to break the layout when having long descriptions and no placeholder
  - Input/Select styles improved, label opacity removed

## 2.1.13

### Patch Changes

- [#1877](https://github.com/nextui-org/nextui/pull/1877) [`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated, changeset config changed to update peer dependencies only when out of range

- [#1884](https://github.com/nextui-org/nextui/pull/1884) [`acba2cf8f`](https://github.com/nextui-org/nextui/commit/acba2cf8f5ba1526bd44c6851e0ed7fdc6c0b8ae) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Input, Textarea, Select, Autocomplete and Textarea helper wrapper styles fixed

- [#1891](https://github.com/nextui-org/nextui/pull/1891) [`e728a8967`](https://github.com/nextui-org/nextui/commit/e728a8967b1775be6a919f3b6bd6fc2267cc002d) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Input/Autocomplete/Textarea/Select styles adapted to custom default color, label truncate added

## 2.1.12

### Patch Changes

- [#1874](https://github.com/nextui-org/nextui/pull/1874) [`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated to avoid the peer conflicts issue.

- Updated dependencies []:
  - @nextui-org/system@2.0.12

## 2.1.11

### Patch Changes

- [#1869](https://github.com/nextui-org/nextui/pull/1869) [`e84158db6`](https://github.com/nextui-org/nextui/commit/e84158db620954b0f1d71206acbf3d46f43b0b89) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Select without label position fixed
  - Input helperWrapper slot is now relative to its parent
- Updated dependencies [[`e84158db6`](https://github.com/nextui-org/nextui/commit/e84158db620954b0f1d71206acbf3d46f43b0b89)]:
  - @nextui-org/theme@2.1.12

## 2.1.10

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/system@2.0.11
  - @nextui-org/theme@2.1.10
  - @nextui-org/react-utils@2.0.10
  - @nextui-org/shared-icons@2.0.5
  - @nextui-org/shared-utils@2.0.4

## 2.1.9

### Patch Changes

- [#1631](https://github.com/nextui-org/nextui/pull/1631) [`425a034bc`](https://github.com/nextui-org/nextui/commit/425a034bca4aa5a86cfe4bc47c084366a7ad7e87) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - validationState prop deprecated, "isInvalid" prop adjusted, invalid checkbox and radios state improved

- Updated dependencies [[`425a034bc`](https://github.com/nextui-org/nextui/commit/425a034bca4aa5a86cfe4bc47c084366a7ad7e87)]:
  - @nextui-org/theme@2.1.9
  - @nextui-org/system@2.0.10
  - @nextui-org/react-utils@2.0.9

## 2.1.8

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/system@2.0.9
  - @nextui-org/theme@2.1.8
  - @nextui-org/react-utils@2.0.8
  - @nextui-org/shared-icons@2.0.4
  - @nextui-org/shared-utils@2.0.3

## 2.1.7

### Patch Changes

- [#1589](https://github.com/nextui-org/nextui/pull/1589) [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria packages upgraded

- Updated dependencies [[`a3be419cb`](https://github.com/nextui-org/nextui/commit/a3be419cb3c693ae8cace15f9a863274d759ddb1), [`5c30e0481`](https://github.com/nextui-org/nextui/commit/5c30e04811ef9f973d6b59107c909db72d9876b5), [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2)]:
  - @nextui-org/theme@2.1.7
  - @nextui-org/system@2.0.8

## 2.1.6

### Patch Changes

- Updated dependencies [[`7c8341035`](https://github.com/nextui-org/nextui/commit/7c8341035dbdd120cd78221b3cabab2e40e7478d)]:
  - @nextui-org/theme@2.1.6

## 2.1.5

### Patch Changes

- Updated dependencies [[`d61428d9e`](https://github.com/nextui-org/nextui/commit/d61428d9e6c1c0590593fb1f0136e226051b7e23), [`4db10a47e`](https://github.com/nextui-org/nextui/commit/4db10a47e96ad8315b5b96c2ff15574ac0fdeecc)]:
  - @nextui-org/theme@2.1.5
  - @nextui-org/system@2.0.7

## 2.1.4

### Patch Changes

- [#1543](https://github.com/nextui-org/nextui/pull/1543) [`043b8420c`](https://github.com/nextui-org/nextui/commit/043b8420cfb659cbb6bb36404807ec3cc8ac8592) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #1492 \n

  - Select and Input spaces fixed on helper wrapper
  - New select wrapper added `mainWrapper` which contains the helperWrapper and the trigger slots
  - Outside input with start content fixed

- Updated dependencies [[`043b8420c`](https://github.com/nextui-org/nextui/commit/043b8420cfb659cbb6bb36404807ec3cc8ac8592), [`641bf0885`](https://github.com/nextui-org/nextui/commit/641bf0885b6af2d7f36f27d83716a441975a5ca5)]:
  - @nextui-org/theme@2.1.4
  - @nextui-org/system@2.0.6

## 2.1.3

### Patch Changes

- Updated dependencies [[`5702287e5`](https://github.com/nextui-org/nextui/commit/5702287e5622a8f0a0326c7cc0c200808c7971a8)]:
  - @nextui-org/theme@2.1.3

## 2.1.2

### Patch Changes

- [#1458](https://github.com/nextui-org/nextui/pull/1458) [`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix dropdown trigger events and popover arrow styles

- Updated dependencies [[`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01)]:
  - @nextui-org/theme@2.1.2

## 2.1.1

### Patch Changes

- Updated dependencies [[`cc839cdd`](https://github.com/nextui-org/nextui/commit/cc839cdd1fd54931bfba137e2f9b5e8007a7e47d)]:
  - @nextui-org/theme@2.1.1

## 2.1.0

### Minor Changes

- [#1313](https://github.com/nextui-org/nextui/pull/1313) [`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New components:

  - Select
  - Listbox
  - ScrollShadow

### Patch Changes

- Updated dependencies [[`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e)]:
  - @nextui-org/theme@2.1.0
  - @nextui-org/shared-icons@2.0.3
  - @nextui-org/react-utils@2.0.7

## 2.0.14

### Patch Changes

- [#1406](https://github.com/nextui-org/nextui/pull/1406) [`4e7789c1f`](https://github.com/nextui-org/nextui/commit/4e7789c1f6c283b2c2116d0d80cd1ea94e5da025) Thanks [@remorses](https://github.com/remorses)! - Input is no more always controlled, supporting mutations via ref

## 2.0.13

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.6

## 2.0.12

### Patch Changes

- Updated dependencies [[`d0341020`](https://github.com/nextui-org/nextui/commit/d0341020e6d865ad3f0d3646fa70a24de75a722b)]:
  - @nextui-org/theme@2.0.5

## 2.0.11

### Patch Changes

- [#1369](https://github.com/nextui-org/nextui/pull/1369) [`abe1ba58`](https://github.com/nextui-org/nextui/commit/abe1ba58de03d8651c24d01de5e2d0a91334b50e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - fix #1332 undefined value removed from input value

## 2.0.10

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.5

## 2.0.9

### Patch Changes

- [#1359](https://github.com/nextui-org/nextui/pull/1359) [`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - \n

  - react-aria packages upgraded to the latest version
  - image storybooks fixed
  - other bug fixes..

- Updated dependencies [[`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171)]:
  - @nextui-org/system@2.0.5

## 2.0.8

### Patch Changes

- Updated dependencies [[`710395f3`](https://github.com/nextui-org/nextui/commit/710395f3a2ca44238332237a49e948c933abe63d)]:
  - @nextui-org/system@2.0.4

## 2.0.7

### Patch Changes

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.4

## 2.0.6

### Patch Changes

- [#1323](https://github.com/nextui-org/nextui/pull/1323) [`42001647`](https://github.com/nextui-org/nextui/commit/4200164712b6eb4b37a14fe9e005844ff770a180) Thanks [@tianenpang](https://github.com/tianenpang)! - Fixed event functions call twice.

- Updated dependencies []:
  - @nextui-org/react-utils@2.0.3

## 2.0.5

### Patch Changes

- [#1309](https://github.com/nextui-org/nextui/pull/1309) [`ac605eb7`](https://github.com/nextui-org/nextui/commit/ac605eb71f8aa945525a1c659b7bd17037303762) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - onValueChange returned value fixed, it nows return a plain string

## 2.0.4

### Patch Changes

- [#1301](https://github.com/nextui-org/nextui/pull/1301) [`d794225c`](https://github.com/nextui-org/nextui/commit/d794225cb75121db3a72f430739b4eaacd1cf8b7) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Plugin types adapted to work with latest version of postcss

- Updated dependencies [[`d794225c`](https://github.com/nextui-org/nextui/commit/d794225cb75121db3a72f430739b4eaacd1cf8b7)]:
  - @nextui-org/theme@2.0.4

## 2.0.3

### Patch Changes

- [#1289](https://github.com/nextui-org/nextui/pull/1289) [`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - "use client" directive removed from components that didn't need it

  - packages adapted to support RSC imports
  - filterDomProps function was modified to enable/disabled it

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports
- Updated dependencies [[`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782), [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f)]:
  - @nextui-org/react-utils@2.0.2
  - @nextui-org/system@2.0.3
  - @nextui-org/theme@2.0.3
  - @nextui-org/shared-icons@2.0.2
  - @nextui-org/shared-utils@2.0.2

## 2.0.2

### Patch Changes

- Updated dependencies [[`459ac5ed`](https://github.com/nextui-org/nextui/commit/459ac5ed4537942517803ba14129226a791d6feb)]:
  - @nextui-org/theme@2.0.2
  - @nextui-org/system@2.0.2

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated

- Updated dependencies [[`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140), [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140)]:
  - @nextui-org/shared-icons@2.0.1
  - @nextui-org/shared-utils@2.0.1
  - @nextui-org/react-utils@2.0.1
  - @nextui-org/system@2.0.1
  - @nextui-org/theme@2.0.1
