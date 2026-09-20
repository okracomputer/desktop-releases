# okraPDF Desktop Downloads

Official public downloads for okraPDF on Mac. The app's source is maintained separately in a private repository.

## Mac installer

[Download okraPDF v1.0.0-rc.45 for Apple silicon](https://github.com/okrapdf/desktop-releases/releases/download/desktop-v1.0.0-rc.45/Okra-1.0.0-rc.45.dmg)

The empty workspace now centers Open PDF and a compact recent-file list. Recent rows have short folder labels, dates and consistent action menus. Locate appears inline only after a known source-access issue; Locate Original remains available in the row menu.

The compact Markup palette brings Pen, Highlight, Eraser and Text together with independent styles, swatches, custom colors and Apply/Cancel controls. OCR review adds a source-box toggle, compact Tags and Preview, and selected model/processing-location visibility. This candidate also fixes a workspace-service startup cleanup wait. Source PDFs remain unchanged.

Gemini 3.8 Flash and Gemini 3.5 Flash are available in **Settings → Models** and **OCR & Extract → Model** with your own Gemini API key. Both use high thinking, up to 65,536 output tokens and the same ParseBench layout prompts. Request errors show Google’s details; incomplete pages can be retried with Resume. Local defaults remain unchanged.

Extracted Markdown renders in **Preview**; **Tags** keeps the source-linked block inspector. The output tabs are Preview, Tags, JSON and CSV. Copy and Save preserve the original Markdown.

The application and installer are Developer ID signed and Apple notarized. This prerelease requires macOS 13 or later on Apple silicon. Full Preview parity remains in progress.

[Release notes and SHA-256 checksum](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.45)

[Previous candidate: RC.44](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.44). RC.43 was not published.

## Updates

Use **Check for Updates…** in a current public-feed build, or install the signed DMG above.

[Public Sparkle update feed](https://raw.githubusercontent.com/okrapdf/desktop-releases/main/appcast.xml)

RC.25 and older installers contain the previous private feed address. Install the current signed DMG manually to move onto this public update channel.

Only published, signed installer artifacts are listed here. This repository contains download metadata; its automatically generated source archives are not the application source.
