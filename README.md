---
title: Background Audio
description: Control whether or not your app allows background audio, dynamically.
---

## Installation

1. `cordova plugin add https://github.com/thessler27/background-audio-plugin.git`

## Utilization

1. To enable background audio mixing with other audio tracks: `window.plugins.backgroundaudio.enableBackgroundMusic()`

2. To disable: `window.plugins.backgroundaudio.disableBackgroundMusic()`

3. To duck: `window.plugins.backgroundaudio.quietBackgroundMusic()`



Supported Platforms
-------------------

- iOS
- Android
