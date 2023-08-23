# PATH Management Scripts

This repository contains two simple scripts, `addpath` and `removepath`, which make it easier to manage the directories in your `PATH`.

- `addpath`: Add a directory to your PATH.
- `removepath`: Remove a directory from your PATH.

## Usage

```bash
addpath /path/to/directory
removepath /path/to/directory
```
The scripts will update the PATH for your shell (bash, zsh, or fish) and remove any duplicates. 
After running the scripts, restart your terminal or re-source your shell configuration for the changes to take effect.

## Installation
To install the scripts and make them available system-wide, run:

```bash
    chmod +x install.sh
    sudo ./install.sh
```
License
MIT