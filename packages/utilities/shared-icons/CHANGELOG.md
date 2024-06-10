## 2.2.0 (2024-06-10)


### 🚀 Features

- avatar group created, test added, new hooks added

- avatar and avatar group improved, fallback added, loaded animation added

- **components:** badge stories added, icons packages renames

- **root:** tsup build improved

- **root:** plugin created to add multiples themes, standard variants created

- **root:** react 18, react aria packages upgraded

- **root:** stitches removed globally, react 18 implemented, pnpm setup changed

- **components:** radio & checkbox improved, custom examples added to the stories

- **pagination:** next, prev and ellipsis buttons added

- **switch:** component created

- **accordion:** stories added

- **accordion:** stories improved

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

- **input:** api improved

- **input:** start and end content added, new stories

- **root:** new version

- **root:** new snapshot published

- **popover:** a11y improved, titleProps passed by render props, form auto focus added

- **popover:** backdrop support added

- **dropdown:** new stories added

- **root:** new snapshot

- **image:** image component added

- **modal:** implementation done

- **modal:** new snapshot

- **root:** new snapshot

- **navbar:** tests added, animations improved

- **table:** big improvements

- **table:** sortable and load-more examples added

- **table:** component done

- **root:** divider and kbd components added, docs in progress

- **docs:** hero in progress, some components fixed

- **root:** tabs component created, animation improved

- **root:** tsup banner added to support use client directive

- **docs:** second section done desktop

- **docs:** a11y and responsive improved

- **docs:** demo modal for code examples added

- **docs:** page improvements

- **docs:** introduction and installation docs in progress

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

- **calendar:** initial structure


### 🩹 Fixes

- plop template error

- **drip:** animation

- **shared-icons:** exports

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

- **textarea:** styles issues and start/end content props added


### ❤️  Thank You

- Frozen FIsh
- Junior Garcia

# @nextui-org/shared-icons

## 2.0.7

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated

## 2.0.6

### Patch Changes

- [#1923](https://github.com/nextui-org/nextui/pull/1923) [`9189b3fbf`](https://github.com/nextui-org/nextui/commit/9189b3fbf2d6d6cc6566009c71b37d5fcc566291) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Textarea style rounded full styles issues fixed, start and end content props added

## 2.0.5

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

## 2.0.4

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

## 2.0.3

### Patch Changes

- [#1313](https://github.com/nextui-org/nextui/pull/1313) [`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New components:

  - Select
  - Listbox
  - ScrollShadow

## 2.0.2

### Patch Changes

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated
