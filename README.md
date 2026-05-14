<hr>

<div align="center">

# yt-dlp PWSH Wrapper

A wrapper for the somewhat confusing and oft overcomplicated yt-dlp binary. Assumes that you have [yt-dlp](https://github.com/yt-dlp/yt-dlp), [ffmpeg](https://ffmpeg.org/), and [node](https://nodejs.org) already installed.

### Description

`yt-dlp` is extremely powerful, but its command syntax can be...a little much for routine use, to say the least.

This wrapper provides a simpler, PowerShell-based interface for common download tasks while still exposing the flexibility of the underlying binary.

The script handles argument construction, playlist organization, audio/video mode selection, logging, binary updates, retry handling, and external dependency configuration automatically.  The goal is to reduce repetitive command usage and simplify per-execution configuration rather than repeatedly passing long CLI arguments manually.

### Features

</div>

* Simple video or audio-only downloads
* MP4 video output by default
* MP3 extraction support with `-audio`
* Automatic playlist folder organization
* Configurable yt-dlp, ffmpeg, and Node.js binary paths
* JSON-based configuration file
* Automatic yt-dlp update and retry handling
* PowerShell transcript logging
* Debug output support
* Automatic destination directory creation
* Wrapper-based execution to avoid memorizing long yt-dlp commands

<div align="center">

### Shell Command

Can be placed anywhere you need to run it from.  Adjust paths for yt-dlp, ffmpeg, and node binaries using `yt-dl-config.json`.

</div>

<hr>
