# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0] - 2022-01-27
### Added
- Transparent overlay window
- Change gold spending based on health
- Queue to communicate between the game process and GUI
- pywin32 to requirements.txt

### Changed
- Screen coordinates now have a naming convention, _pos for bbox & _loc for click locations

### Fixed
- Tacticians Crown check now checks against the proper string

### Removed
- Printing to the console from in game
- PyAutoGUI from requirements.txt

## [1.2.0] - 2022-01-26
### Added
- Health check

## [1.1.0] - 2022-01-19
### Changed
- README
- Screen coords now use (x, y, x+w, y+h) instead of (x, y, w, h)
- Moved bench occupied check to arena functions
- Reformatted imports 
- All screenshot functions now use ImageGrab.grab instead of pyautogui.screenshot
- Added function annotation to various functions

### Removed
- PyAutoGUI

## [1.0.0] - 2022-01-06
### Added
- Files
- README
- LICENSE

[1.2.0]: https://github.com/jfd02/TFT-OCR-BOT/tree/54eea1991fcbd338eb720a69fad3193e1b393824
[1.1.0]: https://github.com/jfd02/TFT-OCR-BOT/tree/af6258fb3aaa5e3807fce2375338c4af328472d1
[1.0.0]: https://github.com/jfd02/TFT-OCR-BOT/tree/6b7ce114ef35c45d4fc8328bed5520ed04a39592