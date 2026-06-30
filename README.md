# Night Owl

**Autonomous overnight astrophotography for the macOS desktop.** Night Owl turns a
Mac into an unattended observatory controller for Seestar telescopes — it watches
the roof, captures the plan, culls the bad frames, organizes the keepers, and tracks
every target's progress, so you wake up to a sorted night's work instead of a folder
of raw `.fit` files.

This repository hosts Night Owl's **release builds and the Sparkle auto-update feed**.
The app source lives in a separate private repository.

---

## Download

**[⬇︎ Night Owl 1.1](https://bpodbielski.github.io/nightowl-releases/NightOwl-1.1.zip)** — macOS 14 (Sonoma) or later.

Unzip and drag **Night Owl.app** to your Applications folder. The build is signed
with a Developer ID and notarized by Apple, so it opens without a Gatekeeper
override.

### Updates
Night Owl updates itself. It checks this feed for new versions and offers to install
them in place — or check on demand from **Night Owl ▸ Check for Updates…**. No
reinstalling, no re-downloading.

---

## What it does

- **Autonomous capture** — native Seestar control over your local network; runs the
  night's plan unattended.
- **Roof-aware** — monitors the observatory roof feed and only images when it's safe.
- **Automatic culling** — flags satellite trails, clouds, and out-of-spec frames so
  only the good subs are kept.
- **Organize & archive** — routes keepers to Google Drive, a local library, or a
  processing app, with durable per-target capture-hour tracking that survives moves
  and re-imports.
- **Conditions & intelligence** — local weather, sky conditions, moon, and a
  site-tuned forecast of how good tonight will be.
- **Planning** — a season planner and nightly scheduler, a sky map, plate-solve
  pointing checks, and mosaic planning.
- **Imaging workbench** — in-app stacking and pre-processing driven by Siril and the
  RC-Astro tools.
- **Two-Mac setup (optional)** — run a headless "observatory" Mac that captures and
  stages, and a "workstation" Mac that pulls, verifies, and archives the keepers.

---

## Changelog

### 1.1
- Workstation reclaims disk space: after a night's verified keepers are archived to
  your external drive, the local working copies are removed automatically.
- Process from your archive: on the Workstation, the Process tab works from archived
  target folders, with integration hours read from the folder itself.
- Settings tailored to each node: options that don't apply to the selected node type
  are now hidden.

### 1.0
First release with built-in automatic updates.
- In-app updates via Sparkle.
- Accurate capture hours: integration time is reconciled per observation night, so a
  target's total reflects every night it was imaged.
- Sky map, plate-solve pointing checks, and mosaic planning.

---

*Night Owl is an independent project and is not affiliated with ZWO/Seestar.*
