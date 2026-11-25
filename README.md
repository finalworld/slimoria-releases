# Slimoria

**Very early development — actively being developed. Expect bugs and changes.**

## Download and play

1. [Download Slimoria Launcher for Windows](https://github.com/finalworld/slimoria-releases/releases/latest/download/SlimoriaLauncher.exe).
2. Open it and press **INSTALL**. No existing game installation is needed.
3. Wait for the progress bar and file verification, then press **PLAY**.

When a game patch is available, press **UPDATE**. Only changed files are downloaded. Your saved characters and edited loose maps are preserved. An existing packaged installation can be selected with **Choose game folder**.

Windows x64. No separate .NET installation required. The launcher itself does not yet self-update; download a newer launcher here when needed.

[Release notes and downloads](https://github.com/finalworld/slimoria-releases/releases/latest)

## Co-op preview

Choose your character, create a named game (with an optional password), or join an active game. All players should use the same version. LAN discovery is supported. Internet hosts need reachable UDP 7777; there is no automatic NAT traversal or relay yet. Co-op remains experimental.

## About this repository

Official download and update distribution for Slimoria. It contains release assets and public notes, not game source code or player saves. The game updater verifies signed manifests and file hashes. The launcher executable is not currently Windows Authenticode-signed.

Files named `block-*.gz`, `update.json` and `update.sig` are used automatically by the launcher. You only need **SlimoriaLauncher.exe**.
