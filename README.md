# Folder Compressor & Archive Inspector

A PyQt5-based GUI application for compressing folders, inspecting archive contents, and decompressing archives.


![Image](https://github.com/user-attachments/assets/e05d1dab-dd8d-41e0-8f43-630318882f4a)

## Features

- **Compress a folder**: Choose a folder and save it as a `.zip`, `.tar`, `.tar.gz`, `.tar.bz2`, or `.tar.xz` archive.
- **View archive contents**: Inspect the contents of `.zip` and `.tar`-based archives without extracting them.
- **Decompress archives**: Extract archives to a selected folder.
- **Supports hidden files**: Includes hidden files in both compression and extraction.
- **Dark mode UI**: Sleek and modern appearance.

---

###  Dependencies

On **Debian-based** systems (Ubuntu, Linux Mint, etc.), install the required packages:

```bash
sudo apt update
sudo apt install python3-pyqt5
```
## Usage

```bash
chmod +x archiver.py
python3 archiver.py
```
	
    Compress Folder
        Click "Compress Folder".
        Select a folder to compress.
        Choose a compression format.
        The archive will be created at the chosen destination.

    View Archive Contents
        Click "View Archive Contents".
        Select an existing archive.
        A window will display the file list inside the archive.

    Decompress Archive
        Click "Decompress Archive".
        Select an archive to extract.
        Choose a destination folder.
        The archive will be extracted.	
