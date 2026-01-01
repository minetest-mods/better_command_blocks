# Changelog

## v2.0 (December 31, 2025)
* Command blocks can be copied with aux1+right-click
* Added "Hover Note" option, like the non-coffee flavor of ACOVG
* Command blocks are placed facing the placer (as in ACOVG), and are no longer impossible to place vertically
* Improved formspec
* Fixed a potential issue where the player's wielded item could get deleted when interacting with command blocks
* Removed unnecessary checks for chain command blocks running multiple times per tick (unnecessary since chain direction got stricter in v1.1)

## v1.3
* Fixed a couple random things (commands can now begin with slashes again)

## v1.2
* Command blocks can be dug by hand.
* Repeating command blocks with a missing/invalid command will no longer stop repeating.

## v1.1 (May 31, 2024)
* Chain command blocks must now be facing the same direction as the previous command block to match ACOVG
* Command block success messages are no longer replaced with "success"
* Command block success messages are now broadcasted in chat, can be disabled by a setting.
* Reorganized the changelog (newer releases first)
* Fixed a bug caused when a command block replaces itself.

## v1.0 (May 5, 2024)
* Initial release.
* Currently ignores third result return value for Better Commands.