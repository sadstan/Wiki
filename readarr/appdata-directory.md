---
title: Readarr Appdata Directory
description: 
published: true
date: 2021-06-09T15:54:35.529Z
tags: 
editor: markdown
dateCreated: 2021-06-09T15:54:32.028Z
---

## Windows

`C:\ProgramData\Readarr`

## Linux

Unless otherwise specified Readarr will store it's application data in the home folder of the user Readarr is running under `/home/$USER/.config/Readarr` (`~/.config/Readarr`)

`/var/lib/Readarr`

## OS X

`/Users/$USER/.config/Readarr (~/.config/Readarr)`

## Synology

`/usr/local/Readarr/var/.config/Readarr`

`/volume1/@appstore/Readarr/var/.config/Readarr`

## QNAP

`/share/MD0_DATA/homes/admin/.config/Readarr`

`/share/CACHEDEV1_DATA/Readarr_CONFIG`

## Argument

The `-data=` argument forces the location of the AppData folder, so your startup command may be forcing a specific location. This is required when trying to run multiple instances. On windows this would be `/data=`

The `-nobrowser` argument refrains from launching/opening the browser on startup. On windows this would be `/nobrowser`
