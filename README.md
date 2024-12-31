# ditana-mirrorlist

This package contains the mirrorlist for Ditana GNU/Linux repositories, used by the pacman package manager.

## Description

`ditana-mirrorlist` provides a curated list of mirror servers for Ditana. These mirrors are used by pacman to download and update packages for your Ditana system.

## Installation

This package is automatically installed by the Ditana Installer.

## Usage

The mirrorlist installed to `/etc/pacman.d/ditana-mirrorlist`. To use these mirrors, the Ditana Installer adds these lines to `/etc/pacman.conf`:

```
[ditana]
Include = /etc/pacman.d/ditana-mirrorlist
```

## Updating

To ensure you have the most up-to-date list of mirrors, regularly update your system:

```
sudo pacman -Syu
```

## Contributing

We are grateful for any additional mirrors. If you'd like to suggest a new mirror, please open a pull request on our GitHub repository.

For more information about Ditana GNU/Linux, visit [https://ditana.org](https://ditana.org)
