# 🎬 StreamFetch

> Fetch your media. Fast.

StreamFetch is a powerful and easy-to-use media downloader built with **yt-dlp**.
Download videos, audio, playlists, and more — all in one clean desktop interface.

> Formerly known as *YouTube Downloader*

---

![Version](https://img.shields.io/badge/version-1.1.10-blue)
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

---

## 🆕 Version 1.1.10 — Codec Compatibility Fix

### 🛠️ Fixes

* Fixed downloads producing files that weren’t compatible with standard media players

* StreamFetch now prioritizes **H.264 (AVC) + AAC** for maximum compatibility

* Falls back to VP9 / AV1 when H.264 isn’t available

---

## 🆕 Version 1.1.9 (Hotfix)

### 🛠️ Fixes

* Clean rebuild after PyInstaller cache packaged an older executable

* Correctly includes all intended v1.1.8 features

---

### ✨ Included Features

* YouTube channel filters:

  * All Videos
  * Videos Only
  * Shorts Only
  * Live Streams Only
  * Podcasts Only

* Installer destination selection with Browse support

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

---
