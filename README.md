<p align="center">
  <img src="assets/app_logo.png" alt="Steam Clips Exporter logo" width="130" />
</p>

<h1 align="center">Steam Clips Exporter</h1>

<p align="center">
  <strong>Automatically export your Steam Game Recording clips to MP4.</strong><br>
  Simple setup. Original quality. Organized clips.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4" alt="Windows" />
  <img src="https://img.shields.io/badge/Version-v1-2563EB" alt="Version v1" />
  <img src="https://img.shields.io/badge/Output-MP4-16A34A" alt="MP4 output" />
</p>

<p align="center">
  <a href="https://github.com/Islaiy/Steam-Clips-Exporter/releases"><strong>Download Steam Clips Exporter</strong></a>
</p>

---

Steam Clips Exporter is a lightweight Windows app that watches your Steam Game Recording folder and automatically saves new clips as easy to watch and share MP4 files.

## ✨ Features

- 🎬 **Automatic MP4 exporting** — Detects and exports new Steam clips for you.
- 🎥 **Original video and audio quality** — Retain original quality video and audio of the clip without re-encoding.
- 📁 **Organized by game** — Optionally saves clips into folders named after their games, including non-Steam games added to your Steam Library.
- 🗑️ **Optional storage cleanup** — Deletes individual original clips after successful exports when enabled.
- 🖥️ **Background monitoring** — Minimize to the system tray and start with Windows.
- ⚙️ **Flexible settings** — Choose your folders and how frequently new clips are checked.
- 📋 **Activity Log** — See what has been exported, skipped, or deleted or any other activity that is performed

## 🚀 Getting started

1. Go to the **[Releases page](https://github.com/Islaiy/Steam-Clips-Exporter/releases)** and download `Steam.Clip.Auto.Exporter.rar` from the latest release.
2. Extract the .rar file
3. Run Steam Clips Exporter.
4. Under **Steam clips folder**, select the recording location configured in **Steam → Settings → Game Recording**. The app automatically searches its subfolders for `clips`.
5. Under **Where MP4 files are saved**, choose where you want the exported videos to go.
6. Click **Start monitoring**. New clips will be exported automatically.

You can also use **Recheck existing clips** to review clips the app has already processed.

## 📂 Example output

With **Create a subfolder for each game** enabled:

```text
 Clips/
├── Game 1/
│   └── Game 1 2026-10-20 18-42-10.mp4
└──  Non-Steam Game/
    └──  Non-Steam Game 2026-10-20 19-05-22.mp4
```

With that option disabled, MP4 files are saved directly inside your selected output folder.

## ⚠️ Good to know

- **Delete clip after successful export** is optional. When enabled, it permanently removes original Steam clip data after a successful export. Test your exports before turning it on.
- If Steam splits a recording into segments with different settings, the app may export multiple MP4 parts rather than risk losing footage.
- Existing exported MP4s are not overwritten or deleted by normal monitoring.


---

<p align="center">
  Made for players who want their Steam clips saved automatically, without the hassle.
</p>

<sub>Steam Clips Exporter is an independent project and is not affiliated with or endorsed by Valve or Steam. Bundled third-party components are subject to their respective licences.</sub>
