# Okra for Mac — Downloads

Official public downloads for Okra for Mac: private document processing on your Mac. Parse, extract, and redact documents with models that run locally. The app's source is maintained separately in a private repository.

[Watch the 58-second film](https://media.okra.computer/desktop-launch/v2-rc49/okra-desktop-launch-1080p.mp4) · [okra.computer](https://okra.computer)

## Mac installer

[Download Okra v1.0.0-rc.53 for Apple silicon](https://github.com/okrapdf/desktop-releases/releases/download/desktop-v1.0.0-rc.53/Okra-1.0.0-rc.53.dmg)

Rearranging pages and dropping documents into the thumbnail sidebar now happens instantly, the way it does in Preview. Moves, deletes and drops show on screen at once while the edit is verified in the background; if it can't be applied, the original page order comes back. Thumbnails move with their pages instead of re-rendering.

Hover or select a parsed block to connect its box on the page to the matching Tags card with a green curve. The connection follows scrolling, zoom and resizing, and hides when either endpoint leaves view.

Choose a model from the compact **Parse with** picker, with its readiness and hardware requirements visible. Opening a file or changing models never starts a parse or model download. Parsed structured output opens in **Tags**, with source-linked blocks and tables and green selection on the page. Preview, JSON and CSV retain their copy and save actions.

Inspect and explicitly approve redaction candidates before exporting a separate redacted copy. New detections start with zero approvals, and approvals are not restored from disk. Selecting a candidate only locates it. Unique native text can refine a candidate's box; scanned or ambiguous text keeps its source block for review. The app refuses to overwrite the original document, including through symlinks and hardlinks.

Native document editing, recent files, the Markup palette, thumbnail sidebar, page organization and CLI remain available. Local models process on your Mac; the optional Gemini integration sends selected pages to Google when explicitly used with your own API key. Models have their own setup and hardware requirements; Apple Vision needs no model download.

The application and installer are Developer ID signed and Apple notarized. This prerelease requires macOS 13 or later on Apple silicon. Full Preview parity remains in progress.

[Release notes and SHA-256 checksum](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.53)

[Previous candidate: RC.52](https://github.com/okrapdf/desktop-releases/releases/tag/desktop-v1.0.0-rc.52). RC.43 was not published.

## Updates

Use **Check for Updates…** in a current public-feed build, or install the signed DMG above.

[Public Sparkle update feed](https://raw.githubusercontent.com/okrapdf/desktop-releases/main/appcast.xml)

RC.25 and older installers contain the previous private feed address. Install the current signed DMG manually to move onto this public update channel.

Only published, signed installer artifacts are listed here. This repository contains download metadata; its automatically generated source archives are not the application source.
