# PC Files

Downloads for PC Files, a small Linux Mint app that opens a Windows PC's
shared drives and desktop over the local network or a direct Ethernet cable.

## Install on Linux Mint

Open a terminal and run:

```bash
wget -qO- https://github.com/SlowPeekin/pc-files-download/releases/latest/download/pcfiles-linux.tar.gz | tar xz && bash pcfiles-linux/install.sh
```

The app then opens. Press **Find my PC**, click Yes on the PC when both show
the same 6-digit code, and enter your Windows password.

## Updates

The app updates itself from the [latest release](../../releases/latest).
Each release carries the app script (`pcfiles`), its helper (`pcfiles-root`),
the install bundle and the SHA-256 hashes in the release notes.
