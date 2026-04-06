# BuddyBar Distribution

This repository hosts BuddyBar's public release artifacts and update metadata.

It does not contain the private BuddyBar application source code.

## Purpose

- GitHub Releases stores public `BuddyBar.dmg` assets
- GitHub Pages serves Sparkle appcast metadata
- GitHub Pages serves versioned release notes

## Pages Layout

GitHub Pages should publish from the `main` branch and `/docs` folder.

- Appcast: `docs/updates/appcast.xml`
- Release notes: `docs/releases/<version>/index.html`

## Expected URLs

- Feed: `https://victorfu.github.io/buddy-bar/updates/appcast.xml`
- Release notes: `https://victorfu.github.io/buddy-bar/releases/<version>/`

## Publishing Model

The private `buddy-bar-code` repository is expected to:

1. Build and notarize `BuddyBar.dmg`
2. Upload the DMG to this repository's GitHub Release
3. Update `docs/updates/appcast.xml`
4. Create `docs/releases/<version>/index.html`
