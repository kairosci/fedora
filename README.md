# HyDE Fedora installer

Builds and installs the Fedora tools HyDE currently consumes from upstream
source: `hyq` (from [HyDE-Project/hyprquery](https://github.com/HyDE-Project/hyprquery)) and
`awww` plus `awww-daemon` (from [LGFae/awww](https://codeberg.org/LGFae/awww)).
Source revisions are pinned so local installs and CI use the same inputs.

Run on Fedora with `dnf` and `sudo` available:

```bash
./install-tools.sh
```

The default install prefix is `/usr/local`. Set `PREFIX` to override it.
