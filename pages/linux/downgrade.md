# downgrade

> Downgrade packages in Arch Linux
> Uses fzf to select version to downgrade to
> More information: <https://github.com/archlinux-downgrade/downgrade>.

- Downgrade xz to a version in pacman cache or the Arch Linux Archive:

`sudo downgrade xz`

- Downgrade xz to a version found in pacman cache:

`sudo downgrade --cached-only xz`

- Downgrade xz to a version found in the Arch Linux Archive:

`sudo downgrade --ala-only xz`

- Downgrade xz, kitty & pipewire to versions in pacman cache or the Arch Linux Archive and add the packages to IgnorePkg:

`sudo downgrade --ignore always xz kitty pipewire`
