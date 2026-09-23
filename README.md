# Okra Desktop Downloads

Official public downloads for Okra on Mac. The app's source is maintained separately in a private repository.

## Mac installer

[Download Okra v1.0.0-rc.52 for Apple silicon](https://github.com/okrapdf/desktop-releases/releases/download/desktop-v1.0.0-rc.52/Okra-1.0.0-rc.52.dmg)

Open With → Okra in Finder now shows the PDF in one window, reusing an empty Okra window instead of leaving it behind. Redact shows progress with a Cancel button, groups candidates by type with Approve All, skips street numbers and ZIP codes that were flagged as dates, and refuses to save a copy if any approved box cannot be applied. The format bar stays pinned while blocks scroll, and a selected block's source box is centered on the page.

Hover or select a parsed block to connect its PDF box to the matching Tags card with a green curve. The connection follows scrolling, zoom and resizing, and hides when either endpoint leaves view.

Choose a model from the compact **Parse with** picker, with its readiness and hardware requirements visible. Opening a file or changing models never starts a parse or model download. Parsed structured output opens in **Tags**, with source-linked blocks and tables and green selection on the page. Preview, JSON and CSV retain their copy and save actions.

Inspect and explicitly approve redaction candidates before exporting a separate redacted copy. New detections start with zero approvals, and approvals are not restored from disk. Selecting a candidate only locates it. Unique native text can refine a candidate's box; scanned or ambiguous text keeps its source block for review. The app refuses to overwrite the original PDF, including through symlinks and hardlinks.

Native document editing, recent files, the Markup palette, thumbnail sidebar, page organization and CLI remain available. Local models process on your Mac; the optional Gemini integration sends selected pages to Google when explicitly used with your own API key. Models have their own setup and hardware requirements; Apple Vision needs no model download.

The application and installer are Developer ID signed and Apple notarized. This prerelease requires macOS 13 or later on Apple silicon. Full Preview parity remains in progress.

[Release notes and SHA-256 checksum](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.52)

[Previous candidate: RC.51](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.51). RC.43 was not published.

## Updates

Use **Check for Updates…** in a current public-feed build, or install the signed DMG above.

[Public Sparkle update feed](https://raw.githubusercontent.com/okrapdf/desktop-releases/main/appcast.xml)

RC.25 and older installers contain the previous private feed address. Install the current signed DMG manually to move onto this public update channel.

Only published, signed installer artifacts are listed here. This repository contains download metadata; its automatically generated source archives are not the application source.
