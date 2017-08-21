---
layout: post
title: "JiaLi Passion"
date: 2017-08-21
---

My first post.

## How to run Mac OSX Sierra on VirtualBox on Mac

checkout this, https://github.com/jonanh/osx-vm-templates

1. download `Install macOS Sierra.app` from AppStore.
2. git clone https://github.com/jonanh/osx-vm-templates
3. cd prepare_iso
4. chmod +x *.sh
5. ./prepare_vdi.sh /Applications/Install macOS Sierra.app ./
6. ./prepare_ovf.sh ./macOS_10.12.6_16G29.vdi ./
7. Install VirtualBox and import from macOS_10.12.6_16G29.vdi 