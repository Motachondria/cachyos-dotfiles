# CachyOS Dotfiles

My personal dotfiles and configuration for CachyOS + KDE Plasma.

This repository is managed with [chezmoi](https://www.chezmoi.io/).

## System

- OS: CachyOS x86_64
- Desktop Environment: KDE Plasma
- Display Server: Wayland
- Shell: Fish
- Terminal: Konsole
- Bootloader: GRUB
- CPU: Intel Core i3-1005G1
- GPU: Intel Iris Plus Graphics G1
- RAM: 8 GB
- Storage:
  - 128 GB NVMe SSD
  - 1 TB HDD

## Included configuration

- KDE Plasma
- Plasma panel and widgets
- KDE global shortcuts
- KWin configuration and rules
- KDE input configuration
- Fish
- Fastfetch
- WirePlumber / Bluetooth configuration
- yt-dlp
- Yakuake autostart
- Arch Update timer
- Espanso systemd service

## Repository structure

```text
.
├── dot_config/
├── packages-native.txt
├── packages-aur.txt
├── .gitignore
├── LICENSE
└── README.md




```

## Restore on a fresh CachyOS installation

Install Git and chezmoi first.

Then initialize this repository:

```bash
chezmoi init <YOUR_GITHUB_USERNAME>/cachyos-dotfiles
```

Review changes before applying them:

```bash
chezmoi diff
```

Install the packages listed in:

- `packages-native.txt`
- `packages-aur.txt`

Browser cookies and authentication data are intentionally excluded from this repository.

## License

MIT
