# TaskRunner

TaskRunner lets you create one task or ten, schedule automatic starts and recurring work, run focused timers, connect nearby computers through private LAN rooms, and hand self-contained dashboards to a phone by QR. The current native release supports Windows and Linux x64.

[Visit the TaskRunner website](https://runnerlabs.github.io/task-runner/) or choose a release:

- [Windows 10/11 x64 setup executable](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.7/TaskRunner_0.9.7_x64-setup.exe)
- [Windows 10/11 x64 MSI package](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.7/TaskRunner_0.9.7_x64_en-US.msi)
- [Debian/Ubuntu x64 package](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.7/TaskRunner_0.9.7_amd64.deb)
- [Linux x64 AppImage](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.7/TaskRunner_0.9.7_amd64.AppImage)
- [SHA-256 checksums](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.7/TaskRunner_0.9.7_SHA256SUMS.txt)
- [Windows release notes](https://github.com/RunnerLabs/task-runner/releases/tag/v0.9.7)

## Current release highlights (v0.9.7)

- Local AI planner discovery, review-before-add cards, faithful optional fields, and exportable generation diagnostics.
- Multi-device Pocket rooms with shareable session links, direct QR generation from task drafts, synced task sounds and volume, offline actions, and encrypted reconnect queues.
- Byte, Ember, Mittens, Nova, and Axolotl companions, including independent outside-coach controls.
- Wallpaper import and fit controls, transparent acrylic styling, refreshed themes, and a themed notepad.
- Verified Windows and Linux trusted/public network controls, retained diagnostic logs, Calendar Clear schedule and Done controls, clearer alarm selection, modern typography, and stronger navigation contrast.

For the visual changelog, see the [What’s new section on the website](https://runnerlabs.github.io/task-runner/#updates) and the [full release notes](https://github.com/RunnerLabs/task-runner/releases/tag/v0.9.7).

## About this repository

This public repository contains only the landing page and public release downloads. The desktop application's source code is maintained separately and is not published here.

Windows and Linux packages are attached to GitHub Releases and are never committed to the website source.

## Linux installation

Portable Linux x64:

```bash
chmod +x TaskRunner_0.9.7_amd64.AppImage
./TaskRunner_0.9.7_amd64.AppImage
```

Debian, Ubuntu, Linux Mint, Pop!_OS, and related distributions:

```bash
sudo apt install ./TaskRunner_0.9.7_amd64.deb
```

To use local rooms, keep the host app open and connect devices to the same trusted local network. TaskRunner's Linux trust controls use NetworkManager and request system authorization before changing the active connection's zone or TaskRunner-specific firewall rules.

## Website contents

- `index.html` - responsive public landing page
- `assets/moonhouse.woff` - Moonhouse webfont
- `assets/task_runner_green.png` - TaskRunner social and thumbnail artwork
- `assets/taskrunner-ascii.png` - TaskRunner ASCII artwork
- `assets/taskrunner-icon-192.png` and `assets/taskrunner-icon-512.png` - public site icons
- `FONT-LICENSE.md` - Moonhouse usage and credit information

## Beta notice

The current Windows beta packages are unsigned. Windows SmartScreen or antivirus software may display a publisher warning; verify the published SHA-256 checksum before installing. Only download TaskRunner from this repository's official Releases page.
