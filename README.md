# curseforge-flatpak

I've made this (first) flatpak because I'd rather isolate the mods from my system.</br>
Given it may be of use to someone else, I've made a repository for it.</br>
<br>
With flatpak-builder, dpkg-deb and wget present in the path:

## Install the SDK, version 24.08

flatpak install flathub org.freedesktop.Sdk</br>
flatpak install flathub org.freedesktop.Platform

## Download CurseForge and prepare it in the 'files' directory
./download

## Build the flatpak
./build

## Install the flatpak
./install

## Run the flatpak
./run

