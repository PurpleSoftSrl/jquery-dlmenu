# jquery-dlmenu

1. Mark sub-menu elements with `.dl-submenu`
2. Call `dlmenu` on any jQuery object

## Options
- `selectors?: {}`
- `backLabel?: string` (default: `"Back"`)
- `resetOnClose?: boolean` (default: `true`) Hide submenus on close
- `animatedClasses?: {}`
- `scrollBodyToClose?: boolean` (default: `true`)
- `clickOutsideToClose?: boolean` (default: `true`)
- `useActiveItemAsBackLabel?: boolean` (default: `false`)
- `useActiveItemAsLink?: boolean` (default: `false`)
- `onLevelClick?: ($menuItem, event) => void`
- `onLinkClick?: ($menuItem, event) => void`

## Changelog

This fork contains the following changes:

- Added `scrollBodyToClose` option [(bad8ae2)](https://github.com/aleclarson/jquery-dlmenu/commit/bad8ae2515e3e49ad1b2242c812666731d860cf6)

- Added `clickOutsideToClose` option [(bad8ae2)](https://github.com/aleclarson/jquery-dlmenu/commit/bad8ae2515e3e49ad1b2242c812666731d860cf6)

- Added `selectors: {}` option [(86cb002)](https://github.com/aleclarson/jquery-dlmenu/commit/86cb0025409d55f326121cb9f16090437db87464)
  - `menu` (the root menu)
  - `submenu` (nested menus)
  - `menuItem` (menu contents)
  - `trigger` (menu toggle)

- Default to no animations [(8039429)](https://github.com/aleclarson/jquery-dlmenu/commit/80394290b5ddd376ed4eee6e6205ead44ea972af)
