# PC Files

Downloads for PC Files: reach a Windows PC from a Linux Mint laptop over the
local network or a direct Ethernet cable. Drives, two-way remote desktop,
system monitor, terminal and power controls. Local network only.

## Windows PC

Download and run [PC-Files-Setup.exe](../../releases/latest/download/PC-Files-Setup.exe),
tick the drives and press **Apply sharing**.

## Linux Mint laptop

Open a terminal and run:

```bash
wget -qO- https://github.com/SlowPeekin/pc-files-download/releases/latest/download/pcfiles-linux.tar.gz | tar xz && bash pcfiles-linux/install.sh
```

The app opens and looks for the PC by itself. Click Yes on the PC when both
show the same 6-digit code, then enter your Windows password.

## Updates

All three programs update themselves from the [latest release](../../releases/latest).
Each release carries the files and their SHA-256 hashes in the release notes;
nothing is installed unless the hash matches.
