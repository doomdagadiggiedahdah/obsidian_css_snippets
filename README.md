# Obsidian Setup 

Simple script to create symbolic links for Obsidian configuration files.

## Quick Setup

- To setup your own obsidian setup folder

1. Update paths in `setup_symlink.sh`:
   ```bash
   DIR_LOCATION=$HOME/Documents/obsidian_setup  # Where you've cloned this repo on your computer
   OBS_LOCATION=$HOME/.Obsidian                 # Your Obsidian root folder
   ```

2. Run the script:
   ```bash
   chmod +x setup_symlink.sh
   ./setup_symlink.sh
   ```

## Why?

- if you want to backup files across many different folders, you're gonna have a bad time.
- instead, put them in a single folder, back that thing up, setup symlinks to where they would go.
