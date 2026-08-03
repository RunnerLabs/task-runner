# TaskRunner

**Plan faster. Start on time. Stay local.** TaskRunner lets you create one task or ten, schedule automatic starts and recurring work, run focused timers, connect nearby computers through private LAN rooms, and hand self-contained dashboards to a phone by QR. Native release packages are available for Windows and Linux x64.

[Visit the TaskRunner website](https://runnerlabs.github.io/task-runner/) or choose a release:

- [Windows 10/11 x64 setup executable](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.5/TaskRunner_0.9.5_x64-setup.exe)
- [Windows 10/11 x64 MSI package](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.5/TaskRunner_0.9.5_x64_en-US.msi)
- [Linux x64 AppImage](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.5/TaskRunner_0.9.5_amd64.AppImage)
- [Linux x64 Debian package](https://github.com/RunnerLabs/task-runner/releases/download/v0.9.5/TaskRunner_0.9.5_amd64.deb)

## About this repository

This public repository contains only the landing page and public release downloads. The desktop application's source code is maintained separately and is not published here.

Windows and Linux packages are attached to GitHub Releases and are never committed to the website source.

## Linux installation

AppImage:

```bash
chmod +x TaskRunner_0.9.5_amd64.AppImage
./TaskRunner_0.9.5_amd64.AppImage
```

Debian, Ubuntu, Linux Mint, Pop!_OS, and related distributions:

```bash
sudo apt install ./TaskRunner_0.9.5_amd64.deb
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

The current Windows and Linux beta packages are unsigned. Windows SmartScreen may display an unknown-publisher warning. Linux desktop environments may ask you to confirm that the AppImage is executable. Only download TaskRunner from this repository's official Releases page.
