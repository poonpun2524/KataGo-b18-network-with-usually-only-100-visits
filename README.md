# KataGo + gtp2ogs Auto Installer

This project is a fully automated script to download, configure, and run [KataGo](https://github.com/lightvector/KataGo) with [gtp2ogs](https://github.com/online-go/gtp2ogs) on Linux. It installs dependencies, downloads binaries, configures settings, and starts the bot—all in one go.

> ⚠️ For **Ubuntu-based systems** only. Root privileges are not required.  
> 🧠 This is perfect for setting up an **OGS (Online Go Server)** bot.

---

## Features

- ✅ Automatically downloads and extracts required libraries (`libzip5`, `libssl1.1`)
- ✅ Downloads and unzips the **KataGo Eigen version**
- ✅ Fetches a strong KataGo neural net model
- ✅ Downloads the latest stable `gtp2ogs` binary
- ✅ Auto-updates the `default_gtp.cfg` with recommended settings
- ✅ Creates `kata_speed.json5` configuration for OGS bot
- ✅ One-line run with API key for gtp2ogs

---
