## 2.2.0 (2024-06-10)


### 🚀 Features

- **calendar:** initial structure


### 🩹 Fixes

- add peer dependencies

- plop template error

- **root:** peer dependecies update only when out of range

- **core:** update peer dependencies for several packages

- **menu:** add hideSelectedIcon prop to menu and listbox

- **dropdown:** focus behaviour on press / enter keydown

- **component:** update type definition to prevent primitive values as items

- **system:** listbox href issue (experimental)


### 🧱 Updated Dependencies

- Updated @nextui-org/shared-icons to 2.2.0
- Updated @nextui-org/shared-utils to 2.2.0
- Updated @nextui-org/react-utils to 2.2.0
- Updated @nextui-org/test-utils to 2.2.0
- Updated @nextui-org/use-aria-menu to 2.2.0
- Updated @nextui-org/use-is-mobile to 2.2.0
- Updated @nextui-org/theme to 2.4.0


### ❤️  Thank You

- Frozen FIsh
- Junior Garcia
- Ryo Matsukawa
- Sung Ye In
- աӄա

# @nextui-org/menu

## 2.0.24

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

- Updated dependencies [[`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a), [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a)]:
  - @nextui-org/use-aria-menu@2.0.4
  - @nextui-org/aria-utils@2.0.20
  - @nextui-org/divider@2.0.28

## 2.0.23

### Patch Changes

- [#2953](https://github.com/nextui-org/nextui/pull/2953) [`c8f792ccd`](https://github.com/nextui-org/nextui/commit/c8f792ccd78a80000e6f5b15e6f22cac947fd531) Thanks [@ryo-manba](https://github.com/ryo-manba)! - Fix update type definition to prevent primitive values as items (#2938)

- [#2970](https://github.com/nextui-org/nextui/pull/2970) [`7df2c71ec`](https://github.com/nextui-org/nextui/commit/7df2c71ecc5f06d60807b6b3502d3a118080a0d5) Thanks [@wingkwong](https://github.com/wingkwong)! - Focus on the first item when pressing Space / Enter key on dropdown menu open (#2863)

- [#2929](https://github.com/nextui-org/nextui/pull/2929) [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Add support for disabling the animations globally.

- Updated dependencies [[`3b14c21e0`](https://github.com/nextui-org/nextui/commit/3b14c21e02fedf15d7d22e911109dac60c4e780e), [`f24a97311`](https://github.com/nextui-org/nextui/commit/f24a97311ab4dd16dafb56d35fe7c6db81798129)]:
  - @nextui-org/aria-utils@2.0.19
  - @nextui-org/use-aria-menu@2.0.3
  - @nextui-org/divider@2.0.28

## 2.0.22

### Patch Changes

- Updated dependencies [[`b8e6b2fe2`](https://github.com/nextui-org/nextui/commit/b8e6b2fe25bbbf52f656bbcac52fc00714f464bc)]:
  - @nextui-org/use-aria-menu@2.0.2
  - @nextui-org/divider@2.0.27

## 2.0.21

### Patch Changes

- Updated dependencies [[`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0)]:
  - @nextui-org/aria-utils@2.0.18
  - @nextui-org/react-utils@2.0.13
  - @nextui-org/divider@2.0.27

## 2.0.20

### Patch Changes

- [#2746](https://github.com/nextui-org/nextui/pull/2746) [`6b56e43a3`](https://github.com/nextui-org/nextui/commit/6b56e43a350d045c36eb9983c7f48ba61db7cdd2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #2743 #2751 internal react-aria use-menu hooks implemented to pass down the press events and control the pressUp one

- Updated dependencies [[`6b56e43a3`](https://github.com/nextui-org/nextui/commit/6b56e43a350d045c36eb9983c7f48ba61db7cdd2)]:
  - @nextui-org/use-aria-menu@2.0.1

## 2.0.19

### Patch Changes

- Updated dependencies []:
  - @nextui-org/aria-utils@2.0.17
  - @nextui-org/divider@2.0.27
  - @nextui-org/react-utils@2.0.12

## 2.0.18

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated
- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14)]:
  - @nextui-org/divider@2.0.26
  - @nextui-org/use-is-mobile@2.0.7
  - @nextui-org/aria-utils@2.0.16
  - @nextui-org/react-utils@2.0.11
  - @nextui-org/shared-utils@2.0.5

## 2.0.17

### Patch Changes

- Updated dependencies []:
  - @nextui-org/divider@2.0.25
  - @nextui-org/aria-utils@2.0.15

## 2.0.16

### Patch Changes

- Updated dependencies []:
  - @nextui-org/divider@2.0.24
  - @nextui-org/aria-utils@2.0.14

## 2.0.15

### Patch Changes

- [#1915](https://github.com/nextui-org/nextui/pull/1915) [`135cc21e6`](https://github.com/nextui-org/nextui/commit/135cc21e6f0f2bee1f19e7e5799b6cea8179b7f5) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #1888 `hideSelectedIcon` added to menu and listbox sections.

- Updated dependencies []:
  - @nextui-org/divider@2.0.23

## 2.0.14

### Patch Changes

- [#1877](https://github.com/nextui-org/nextui/pull/1877) [`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated, changeset config changed to update peer dependencies only when out of range

- Updated dependencies [[`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648)]:
  - @nextui-org/divider@2.0.23
  - @nextui-org/aria-utils@2.0.13

## 2.0.13

### Patch Changes

- [#1874](https://github.com/nextui-org/nextui/pull/1874) [`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Peer dependencies updated to avoid the peer conflicts issue.

- Updated dependencies [[`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0)]:
  - @nextui-org/divider@2.0.22
  - @nextui-org/system@2.0.12
  - @nextui-org/aria-utils@2.0.12

## 2.0.12

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/divider@2.0.21
  - @nextui-org/system@2.0.11
  - @nextui-org/theme@2.1.10
  - @nextui-org/use-aria-press@2.0.1
  - @nextui-org/use-is-mobile@2.0.6
  - @nextui-org/aria-utils@2.0.11
  - @nextui-org/react-utils@2.0.10
  - @nextui-org/shared-utils@2.0.4

## 2.0.11

### Patch Changes

- Updated dependencies [[`425a034bc`](https://github.com/nextui-org/nextui/commit/425a034bca4aa5a86cfe4bc47c084366a7ad7e87)]:
  - @nextui-org/theme@2.1.9
  - @nextui-org/divider@2.0.20
  - @nextui-org/system@2.0.10
  - @nextui-org/react-utils@2.0.9
  - @nextui-org/aria-utils@2.0.10

## 2.0.10

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/divider@2.0.19
  - @nextui-org/system@2.0.9
  - @nextui-org/theme@2.1.8
  - @nextui-org/use-is-mobile@2.0.5
  - @nextui-org/aria-utils@2.0.9
  - @nextui-org/react-utils@2.0.8
  - @nextui-org/shared-utils@2.0.3

## 2.0.9

### Patch Changes

- [#1589](https://github.com/nextui-org/nextui/pull/1589) [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria packages upgraded

- Updated dependencies [[`a3be419cb`](https://github.com/nextui-org/nextui/commit/a3be419cb3c693ae8cace15f9a863274d759ddb1), [`5c30e0481`](https://github.com/nextui-org/nextui/commit/5c30e04811ef9f973d6b59107c909db72d9876b5), [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2)]:
  - @nextui-org/theme@2.1.7
  - @nextui-org/aria-utils@2.0.8
  - @nextui-org/use-is-mobile@2.0.4
  - @nextui-org/divider@2.0.18
  - @nextui-org/system@2.0.8

## 2.0.8

### Patch Changes

- Updated dependencies [[`7c8341035`](https://github.com/nextui-org/nextui/commit/7c8341035dbdd120cd78221b3cabab2e40e7478d)]:
  - @nextui-org/theme@2.1.6
  - @nextui-org/divider@2.0.17

## 2.0.7

### Patch Changes

- Updated dependencies [[`d61428d9e`](https://github.com/nextui-org/nextui/commit/d61428d9e6c1c0590593fb1f0136e226051b7e23), [`4db10a47e`](https://github.com/nextui-org/nextui/commit/4db10a47e96ad8315b5b96c2ff15574ac0fdeecc)]:
  - @nextui-org/theme@2.1.5
  - @nextui-org/divider@2.0.16
  - @nextui-org/system@2.0.7
  - @nextui-org/aria-utils@2.0.7

## 2.0.6

### Patch Changes

- Updated dependencies [[`043b8420c`](https://github.com/nextui-org/nextui/commit/043b8420cfb659cbb6bb36404807ec3cc8ac8592), [`641bf0885`](https://github.com/nextui-org/nextui/commit/641bf0885b6af2d7f36f27d83716a441975a5ca5)]:
  - @nextui-org/theme@2.1.4
  - @nextui-org/system@2.0.6
  - @nextui-org/divider@2.0.15
  - @nextui-org/aria-utils@2.0.6

## 2.0.5

### Patch Changes

- Updated dependencies [[`5702287e5`](https://github.com/nextui-org/nextui/commit/5702287e5622a8f0a0326c7cc0c200808c7971a8)]:
  - @nextui-org/theme@2.1.3
  - @nextui-org/divider@2.0.14

## 2.0.4

### Patch Changes

- [#1463](https://github.com/nextui-org/nextui/pull/1463) [`904f53877`](https://github.com/nextui-org/nextui/commit/904f5387793cf8cc594d4ff8c32e378439a8e4fa) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria utils pkg updated

## 2.0.3

### Patch Changes

- [#1458](https://github.com/nextui-org/nextui/pull/1458) [`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix dropdown trigger events and popover arrow styles

- Updated dependencies [[`4e94c115`](https://github.com/nextui-org/nextui/commit/4e94c115281c2774424d687877e036a9af1bce01)]:
  - @nextui-org/divider@2.0.13
  - @nextui-org/theme@2.1.2

## 2.0.2

### Patch Changes

- Updated dependencies [[`cc839cdd`](https://github.com/nextui-org/nextui/commit/cc839cdd1fd54931bfba137e2f9b5e8007a7e47d)]:
  - @nextui-org/theme@2.1.1
  - @nextui-org/divider@2.0.12

## 2.0.1

### Patch Changes

- [#1313](https://github.com/nextui-org/nextui/pull/1313) [`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New components:

  - Select
  - Listbox
  - ScrollShadow

- Updated dependencies [[`baec5502`](https://github.com/nextui-org/nextui/commit/baec55029de7f17ba84d3e6c8c98358fd1f2695e)]:
  - @nextui-org/theme@2.1.0
  - @nextui-org/divider@2.0.11
  - @nextui-org/react-utils@2.0.7
