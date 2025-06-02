# curseforge-flatpak

With flatpak-builder, dpkg-deb and wget present in the path:

## Install the SDK, version 24.08

flatpak install flathub org.freedesktop.Sdk __
flatpak install flathub org.freedesktop.Platform

## Download CurseForge and prepare it in the 'files' directory
./download

## Build the flatpak
./build

## Install the flatpak
./install

## Run the flatpak
./run

