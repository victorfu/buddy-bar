# BuddyBar

**A native macOS menu bar companion for Claude Code.**

BuddyBar puts Claude Code sessions, approvals, and buddy identity in your macOS menu bar. Built with Swift, AppKit, and SwiftUI — no Electron, no web views.

## Download

Head to [**Releases**](https://github.com/victorfu/buddy-bar/releases/latest) and grab the latest `BuddyBar.dmg`.

**Requirements:** macOS 14 (Sonoma) or newer.

## Install

1. Open the DMG and drag BuddyBar to Applications.
2. Launch BuddyBar — it lives in your menu bar.
3. If Claude Code CLI isn't installed yet, BuddyBar will walk you through setup on first launch.

## Auto Updates

BuddyBar checks for updates via Sparkle. When a new version is available, the app will prompt you to update in-app.

- Update feed: `https://victorfu.github.io/buddy-bar/updates/appcast.xml`

## Highlights

- **Glanceable session state** — idle, running, waiting-approval, compacting, completed, or error, right in the menu bar.
- **Approval handling** — respond to Claude Code permission requests from a native UI instead of hunting for terminal tabs.
- **Transcript-aware enrichment** — message counts, awaiting-input indicators, and activity timestamps surfaced automatically.
- **Usage visibility** — live 5h / weekly usage from your Claude Code login, plus local lifetime stats.
- **Sound cues and notifications** — configurable sounds and native macOS notifications for approvals and task completion.
- **System health glance** — CPU load and memory pressure shown inline, no extra permissions needed.
- **CLAUDE.md tools** — inspect, optimize, back up, and restore your workspace CLAUDE.md from Settings.
- **Plugin Store** — browse and install Claude plugins directly from the app.
- **Launch at login** — native macOS ServiceManagement toggle in Settings.

## Release Notes

Check the [Releases](https://github.com/victorfu/buddy-bar/releases) page for the full changelog per version.

## Feedback

Found a bug or have a feature request? Open an [issue](https://github.com/victorfu/buddy-bar/issues).


