# GPSies.com tracks dump, August 2019

This repository contains GPSies.com tracks dump made at August 2019. 

This dump is made by using scripts and open proxies, including TOR network, so only public-available data is listed here. No any other hacks were used. Track (`.gpx`) and corresponding description (`.html`) files are available.

This repo's release contains data about approximately 1_400_000 tracks worldwide, mostly bicycle.

This GIT repo itself does not contain any data, all data is available on [Releases Page](../../releases/latest).

**Some data may be corrupted or missing due to different reasons. There will be no any updates, fixes, optimizations, etc.**

<hr/>

## Download tracks

Follow to the [Releases Page](../../releases/latest) page.

<hr/>

## File structure

GPSies.com had a 16 lowercase letter track identifier `id`. Each track is presented as two files: `{id}.gpx` file and `{id}.html`. 

Tracks are split into 2-letter folders (`aa`, `ab`, .. `az`, `ba`, `bb`, .. `zz`) named by first two letters of `{id}`, and track files nemed by `{id}` are contained within. Track file names contain full `{id}` in its' names, including two letters of folder name. 

Each folder is archived into separate 7z archive file to fit GitHub's space requirements. 

Each 52 folders (`aa`..`bz`, `ca`..`dz`, ...) are additionally packed into archives by first letter of folders. Archive with `a*` and `b*` tracks is named `gpsies-2019-08-AB.7z`

<hr>

## Space and size requirements

* Total data size is about **20 Gbytes packed**, **20 Gbytes temporary** and **500 GBytes unpacked**.
* **Sample data** is also available [Releases Page](../../releases/latest).
* There are 676 folders, each packed to it's own archive and contains one folder with about **4250 files** (2 files per track).
* Those 676 archives are combined into 13 archives of **1.5 Gbytes** each and available on [Releases Page](../../releases/latest).
* Each of folder size is about **30 Mbytes packed** and **670 Mbytes unpacked**.

<hr>

### Extraction

You will need [![7-Zip logo](https://www.7-zip.org/favicon.ico) 7-Zip](https://www.7-zip.org/) installed about 1 Gb of RAM to extract those archives.

Follow instructions on [Releases Page](../../releases/latest) page.
<hr>

This repository is archived and can be used only as data source.

*Klaus Bechtold, you are great man. GPSies, you were the best. Goodnight, sweet prince.*
