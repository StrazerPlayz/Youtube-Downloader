# 🎬 StreamFetch

> Fetch your media. Fast.

StreamFetch is a powerful and easy-to-use media downloader built with **yt-dlp**.
Download videos, audio, playlists, and more — all in one clean desktop interface.

> Formerly known as *YouTube Downloader*

---

![Version](https://img.shields.io/badge/version-1.1.11-blue)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Powered by](https://img.shields.io/badge/powered%20by-yt--dlp-red)

---

## 🚀 Features

* 🎬 Download videos in multiple qualities (up to best available)
* 🎵 Extract audio (MP3, WAV, etc.)
* 📋 Queue multiple URLs
* 📊 Real-time download progress
* 📁 Automatic file organization
* 🎨 Clean and modern user interface
* 🌓 Light / Dark / System theme support
* 🔐 Member-only content support (with authentication)
* 📂 Bulk import support
* 🖼️ Queue thumbnails + metadata previews
* 📈 Queue ETA + download history
* 🍪 Cookies.txt importing for authentication support

---

## 🆕 Version 1.1.11 — Download Fix

### 🛠️ Fixes

* Fixed downloads failing after the **v1.1.10 codec compatibility update**

* Resolved an issue where H.264 video could be paired with **Opus audio**, which cannot be muxed into MP4 output

* StreamFetch now correctly prefers **AAC (`mp4a`) audio alongside H.264 (`avc1`)** for reliable MP4 downloads

* Added safe fallback behavior when preferred codec combinations aren’t available

---

## 🆕 Version 1.1.10 — Codec Compatibility Fix

### 🛠️ Fixes

* Improved compatibility with standard media players

* StreamFetch now prioritizes **H.264 (AVC) + AAC** for downloads where available

* Better playback support for:

  * Windows Media Player
  * VLC
  * Standard video players

* Graceful fallback when preferred codecs aren’t available

---

## 🔐 Member-Only Content

StreamFetch supports restricted or member-only videos **only if you have access**.

To use this feature:

* You must be a member of the channel
* Authentication (cookies/login) is required

---

## 📥 Download

Download the latest version from the **Releases** tab.

---

## ⚙️ Built With

* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* Python

---

## ⚠️ Disclaimer

This tool is intended for personal use only.
Please respect platform terms of service and support content creators.
