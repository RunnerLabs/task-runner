# TaskRunner

**Made in TaskRunner. Local first.** TaskRunner lets you create one task or ten, schedule automatic starts and recurring work, run focused timers, connect nearby computers through private LAN rooms, and hand self-contained dashboards to a phone by QR. The current native release is for Windows x64; Linux packaging is planned separately.

[Visit the TaskRunner website](https://runnerlabs.github.io/task-runner/) or choose a release:

- [Windows 10/11 x64 setup executable](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.6-1/TaskRunner_0.9.6-1_x64-setup.exe)
- [Windows 10/11 x64 MSI package](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.6-1/TaskRunner_0.9.6-1_x64_en-US.msi)
- [SHA-256 checksums](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.6-1/TaskRunner_0.9.6-1_SHA256SUMS.txt)
- [Windows release notes](https://github.com/RunnerLabs/task-runner/releases/tag/v0.9.6-1)

## Current release highlights (v0.9.6-1)

- Local AI planner profiles for Ollama, LM Studio, and hosted OpenAI-compatible endpoints, with saved instructions and review-before-add task cards.
- Pocket offline mode with timers, completion and restore actions, notes, task creation, and exactly-once encrypted sync when the desktop reconnects.
- Mochi as the first pixel companion, coach renaming, clearer controls, and eight Pocket themes.
- Host diagnostics now tolerate delayed listener startup, repeated start clicks are suppressed, and Pocket retries cannot duplicate queued actions.
- Task views stay distinct as work moves between Today, Inbox, Active, and Done. Windows installer metadata and download links are aligned at v0.9.6-1.

Known follow-up: Pocket task creation cancel behavior is being hardened so cancel always closes the flow without creating a task.

For the visual changelog, see the [What’s new section on the website](https://runnerlabs.github.io/task-runner/#updates) and the [full release notes](https://github.com/RunnerLabs/task-runner/releases/tag/v0.9.6-1).

## About this repository

This public repository contains only the landing page and public release downloads. The desktop application's source code is maintained separately and is not published here.

Windows and Linux packages are attached to GitHub Releases and are never committed to the website source.

## Linux installation

Linux packages will be published in a later release.

```bash
chmod +x TaskRunner_<version>_amd64.AppImage
./TaskRunner_<version>_amd64.AppImage
```

Debian, Ubuntu, Linux Mint, Pop!_OS, and related distributions:

```bash
sudo apt install ./TaskRunner_<version>_amd64.deb
```

To use local rooms, keep the host app open, connect devices to the same local network, and allow TaskRunner through the Linux firewall if prompted.

## Website contents

- `index.html` - responsive public landing page
- `assets/moonhouse.woff` - Moonhouse webfont
- `assets/task_runner_green.png` - TaskRunner social and thumbnail artwork
- `assets/taskrunner-ascii.png` - TaskRunner ASCII artwork
- `assets/taskrunner-icon-192.png` and `assets/taskrunner-icon-512.png` - public site icons
- `FONT-LICENSE.md` - Moonhouse usage and credit information

## Beta notice

The current Windows beta packages are unsigned. Windows SmartScreen or antivirus software may display a publisher warning; verify the published SHA-256 checksum before installing. Only download TaskRunner from this repository's official Releases page.
