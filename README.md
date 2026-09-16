# okraPDF Desktop Downloads

Official public downloads for okraPDF on Mac. The app's source is maintained separately in a private repository.

## Mac installer

[Download okraPDF v1.0.0-rc.38 for Apple silicon](https://github.com/okrapdf/desktop-releases/releases/download/desktop-v1.0.0-rc.38/Okra-1.0.0-rc.38.dmg)

RC.38 fixes Dots OCR 1.5, which failed on page 1 of every run. RC.37 drew OCR & Extract's source boxes on the page and linked them to its panel on hover, like a parsing workbench. It keeps the page steady while you edit: saved strokes stay on screen, Pen keeps drawing stroke after stroke, starting or closing Pen, Fill Form or Merge no longer blanks the page, and the page no longer shifts when an edit finishes. OCR & Extract reads the PDF on screen with one click, including right after you edit it; when a model still needs setup, its panel offers Extract with Apple Vision, and Apple Vision now reads stamped scans in full. Opening a PDF never starts a parse.

The application and installer are Developer ID signed and Apple notarized. This prerelease requires macOS 13 or later on Apple silicon. Full Preview parity remains in progress.

[Release notes and SHA-256 checksum](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.38)

[Previous candidate: RC.37](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.37)

## Updates

Use **Check for Updates…** in a current public-feed build, or install the signed DMG above.

[Public Sparkle update feed](https://raw.githubusercontent.com/okrapdf/desktop-releases/main/appcast.xml)

RC.25 and older installers contain the previous private feed address. Install the current signed DMG manually to move onto this public update channel.

Only published, signed installer artifacts are listed here. This repository contains download metadata; its automatically generated source archives are not the application source.
