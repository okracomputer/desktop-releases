# okraPDF Desktop Downloads

Official public downloads for okraPDF on Mac. The app's source is maintained separately in a private repository.

## Mac installer

[Download okraPDF v1.0.0-rc.40 for Apple silicon](https://github.com/okrapdf/desktop-releases/releases/download/desktop-v1.0.0-rc.40/Okra-1.0.0-rc.40.dmg)

RC.40 lets you change models in **OCR & Extract → Model** while a document is being parsed. The current parser pauses and the selected parser starts or resumes its own saved pages. Switch back to restore that model's progress or completed output. Gemini thinking templates keep separate results, and Cancel also stops a pending model switch. Opening a PDF or selecting a model while idle still requires Parse or Resume. API keys stay outside saved run files, and the source PDF stays unchanged.

Extracted Markdown renders in **Preview**; **Tags** keeps the source-linked block inspector. The output tabs are Preview, Tags, JSON and CSV. Copy and Save preserve the original Markdown.

The application and installer are Developer ID signed and Apple notarized. This prerelease requires macOS 13 or later on Apple silicon. Full Preview parity remains in progress.

[Release notes and SHA-256 checksum](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.40)

[Previous candidate: RC.39](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.39)

## Updates

Use **Check for Updates…** in a current public-feed build, or install the signed DMG above.

[Public Sparkle update feed](https://raw.githubusercontent.com/okrapdf/desktop-releases/main/appcast.xml)

RC.25 and older installers contain the previous private feed address. Install the current signed DMG manually to move onto this public update channel.

Only published, signed installer artifacts are listed here. This repository contains download metadata; its automatically generated source archives are not the application source.
