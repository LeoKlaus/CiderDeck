
# Changes in this fork

I just added a play/pause action to the "Album Art" button. To install this version, download the compiled file from [Releases](github.com/leoklaus/CiderDeck/releases) and double click to install it.
I bumped the version number, so the Stream Deck software _should_ replace the original plugin. If it doesn't just uninstall the official plugin and install this one again.

## Building this

Open a terminal/command prompt, head to the `src` folder and use the following command to build the plugin:
```cmd
DistributionTool.exe -b -i sh.cider.streamdeck.sdPlugin -o <MyOutputFolder>
```
make sure to replace `<MyOutputFolder>` with a folder that actually exists,


# CiderDeck

CiderDeck is a plugin for the Elgato Stream Deck that allows you to control your music and show what your currently listening to at a click of a button.

## Description

Using CiderDeck you can do the following

- Show currently playing song's album art.
- Show currently playing song's name.
- Skip/Rewind
- Play/Pause
- Change Volume
- Like/Dislike
- Add to Library

## Features
- Written in JavaScript
- Cross-Platform (macOS, Windows)

## Requirements
- [Cider 2.3+ (Sabiiro)](https://cider.sh)
- Stream Deck (MK.1, MK.2, SD+, XL)
- Computer running Windows or macOS

## Installation Guide

Go into the [Releases](github.com/leoklaus/CiderDeck/releases) and download the latest compiled plugin file, double click to open it in the Stream Deck software for installation.

Done!
