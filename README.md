<div align="center">
    <h1>Toolb<sub>o</sub>xes</h1>
    <h3>Toolbox/Distrobox images made by Sernik members</h3>
</div>

<div align="center">

[![fedora-toolbox](https://github.com/sernik-tech/toolbxes/actions/workflows/build-fedora-toolbox.yml/badge.svg)](https://github.com/sernik-tech/toolbxes/actions/workflows/build-fedora-toolbox.yml) [![ubuntu-toolbox](https://github.com/sernik-tech/toolbxes/actions/workflows/build-ubuntu-toolbox.yml/badge.svg)](https://github.com/sernik-tech/toolbxes/actions/workflows/build-ubuntu-toolbox.yml) [![arch-toolbox](https://github.com/sernik-tech/toolbxes/actions/workflows/build-arch-toolbox.yml/badge.svg)](https://github.com/sernik-tech/toolbxes/actions/workflows/build-arch-sernik.yml) [![google-chrome](https://github.com/sernik-tech/toolbxes/actions/workflows/build-google-chrome-toolbox.yml/badge.svg)](https://github.com/sernik-tech/toolbxes/actions/workflows/build-google-chrome-toolbox.yml)

</div>

Custom images made for use with Toolbox and Distrobox with the purpose of making for one to just pull and have all of the tools they need. Based off of the work of [Universal Blue](https://github.com/ublue-os/toolboxes).

## Images

### Fedora Sernik

Simple Fedora image that comes prepackaged with basic utilities, such as a handful of [Modern Unix](https://github.com/ibraheemdev/modern-unix) utilities, and other goodies like yt-dlp. For general usage.

### Ubuntu Sernik

Ubuntu image that comes with VSCodium, ADB (Android debugging bridge) and other related development and debugging tools. For general usage, but by default more towards development related purposes.

### Arch Sernik

Arch image based off of [bazzite-arch](https://github.com/ublue-os/bazzite-arch) with minor changes. Come with Steam, Lutris and other gaming related utilities. For general usage, but by default more towards gaming.

##### The minor change in question: We don't package OBS Studio (obs-vkcapture-git) unlike bazzite as well as removing a few changes that limit Bazzite-arch to be an image *only* suitable for gaming.

### Google Chrome

A probably useless Ubuntu image with the attempt to have a minimal container with nothing but Google Chrome preinstalled. For people who need to use it but prefer not have it installed onto their actual system (as an alternative to Flatpak as well).
