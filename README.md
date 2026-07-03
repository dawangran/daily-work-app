# WorkPulse

WorkPulse is a local-first macOS app for daily work tracking, project progress, calendar-style boards, and weekly/monthly/yearly reviews.

## Download

Download the DMG from this repository:

- [WorkPulse-0.1.0-macos.dmg](WorkPulse-0.1.0-macos.dmg)

## Install

1. Download `WorkPulse-0.1.0-macos.dmg`.
2. Open the DMG.
3. Drag `WorkPulse.app` to `Applications`.
4. Launch WorkPulse from Launchpad or Finder.

This build is unsigned with an Apple Developer ID. On first launch, macOS may block it. If that happens, right-click `WorkPulse.app`, choose `Open`, then confirm.

## Features

- Daily work dashboard with tasks, progress, next actions, and project distribution.
- Project color coding and project detail history.
- Calendar-style week, month, and year boards.
- Weekly, monthly, and yearly review summaries.
- Optional OpenAI-compatible AI review generation.
- Chinese and English interface switching.
- Local-first storage with no account or cloud sync.

## Privacy

WorkPulse stores tasks and reviews locally on your Mac. API keys are stored in macOS Keychain. AI review is optional and only sends review summary data to the provider you configure.

See [PRIVACY.md](PRIVACY.md) for details.

## Repository Contents

This repository contains only the packaged macOS installer and release documentation. Source code is not included.
