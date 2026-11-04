# Craft Anything Android PWA

This repository contains the built, installable browser app, not the Rust source tree.

## Publish

Serve the repository root over HTTPS. On Android, open the HTTPS address in Chrome and choose **Install app** or **Add to Home screen**.

The app analyzes selected files in the browser and does not upload them or call paid AI services. The browser build has a 512 MiB per-file cap because it processes files in memory.

The editable Rust source is in `apps/craft-anything-web` in the original Craft Anything workspace. Rebuild with Trunk after source changes, then replace these static files.
