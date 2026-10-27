**English** · [Français](README.fr.md)

# Umbra Engine: downloads

A retro horror game engine and editor for Windows (Direct3D 11).

This repository only contains the **published releases** of Umbra Engine.

## Install

1. Open the [latest release](../../releases/latest).
2. Download **`UmbraEngine-Setup.exe`** and run it.
3. That's it: the installer downloads the latest version, checks its
   SHA-256 hash and installs it in your user profile
   (`%LOCALAPPDATA%\Programs\Umbra Engine`), without admin rights.

The installer is not signed: Windows SmartScreen may show
"Windows protected your PC". Click **More info**, then **Run anyway**.

### Without the installer

Download `UmbraEngine-<version>-win64.zip`, extract it anywhere and run
`umbra_editor.exe`. The folder updates itself the same way.

## Updates

On launch, the editor checks whether a newer version exists. It shows up
as a notification; one click downloads it, and it is installed on the next
restart. Your content (`content/`) is never overwritten.

## Uninstall

Windows Settings > Apps > Installed apps > Umbra Engine > Uninstall.
Your content and settings stay on disk, unless you tick the box to delete everything.

## Verify a download

Each package comes with a `.sha256` file:

```powershell
Get-FileHash UmbraEngine-1.0.0-win64.zip -Algorithm SHA256
```

---

Umbra Engine is proprietary software; its source code is not public.
