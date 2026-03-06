# Mosyl Audio — Bug Tracker

This repository is used to track bugs and issues across Mosyl Audio products. Before submitting a report, please read the guide below to help us resolve your issue as quickly as possible.

---

## How to Submit a Bug Report

1. Go to the [**Issues**](../../issues) tab and click **New Issue**.
2. Select **Bug Report** and click **Get started**.
3. Fill out each field as completely as you can — partial reports are harder to act on.
4. Click **Submit new issue** when you're done.

---

## Field Guide

### Which application?
Select the specific Mosyl Audio app where the bug occurred.

### Severity
Pick the option that best describes the impact:
- **Crash / App freeze** — the plugin or app stops responding or closes unexpectedly
- **Incorrect audio output** — the sound is wrong, distorted, silent, or behaves unexpectedly
- **Performance issue** — high CPU/memory usage, dropouts, or sluggishness
- **UI / visual glitch** — a visual element is broken, misaligned, or not displaying correctly

### Operating System
Select macOS, Linux, or Windows.

### OS Version
Include the exact version number — this matters because bugs are often OS-specific.
> Examples: `macOS 15.3`, `Windows 11 24H2`

### Plugin / App Version
Found in the app's UI. This is the most important field for tracking down bugs — please don't skip it.
> Example: `1.2.0`

### DAW and Version
If the bug happens inside a DAW (Digital Audio Workstation), tell us which one and its version. Leave this blank if you're using a standalone app.
> Examples: `Ableton Live 12.1`, `Logic Pro 11.1`, `Pro Tools 2024.6`

### What happened?
Describe the bug clearly and specifically. Avoid vague descriptions like "it doesn't work" — explain what you observed.
> Example: *"The reverb tail cuts off abruptly after 2 seconds regardless of the Decay setting."*

### Steps to reproduce
List the exact steps that cause the bug to appear. If we can't reproduce it, we can't fix it.
> Example:
> 1. Insert the plugin on an audio track
> 2. Set Decay to 8s and Wet to 100%
> 3. Play a short audio clip
> 4. Reverb tail stops at exactly 2 seconds

### Expected behavior
Describe what you expected to happen. This helps us understand if it's a bug or a misunderstanding of intended behavior.

### Additional context
Anything extra that might help: screenshots, screen recordings, audio samples, or crash logs. The more context, the faster we can diagnose the issue.

---

## Tips for a Good Report

- **One bug per report.** If you've found multiple issues, open a separate report for each.
- **Check existing issues first.** Search [open issues](../../issues) to avoid duplicates.
- **Be specific.** Reproducible bugs get fixed. Vague reports get closed.

---

*Thank you for taking the time to report — it directly helps improve Mosyl Audio products.*
