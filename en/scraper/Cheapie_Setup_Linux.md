# Cheapie Setup on Linux

Original author: [Nicolas Lucien](https://github.com/Tech-FZ) |
Editors: [Nicolas Lucien](https://github.com/Tech-FZ) |
Last updated: 18th February, 2024

Cheapie is a program which is supposed to help users save money by comparing prices without visiting every possible website of every possible corporation and doing a lot of research. This has been tested on Ubuntu 22.04 LTS x64 with Python 3.10.12, but it probably also works with other Linux distributions, you just have to adjust it.

## Installation

### Desktop Environment

If you don't have a desktop environment on your server, you must install one as the Cheapie Scraper uses PySimpleGUI for a selector. I'll leave that up to you.

### Dependencies

First of all, open your terminal. To update your Linux installation, check which one is right for you and type it in.

| Distribution | Command |
| ------------ | ------- |
| Debian/Ubuntu/Linux Mint | `sudo apt update && sudo apt upgrade` |
| Fedora/RHEL 8+ | `sudo dnf upgrade --refresh` or `sudo dnf update` |
| Gentoo | `sudo emaint -a sync && sudo emerge --ask --verbose --update --deep --newuse @world` |
| Arch | `sudo pacman -Syu` |
| openSUSE Leap/SUSE | `sudo zypper patch && sudo zypper up` |
| openSUSE Tumbleweed | `sudo zypper patch && sudo zypper dup` |

Then, install the Python Virtual Environment.

(insert continuation here)