# Tools - Portable Utilities for Windows

This repository contains portable utilities that can run on Windows systems without requiring full installation.

## Objective

The goal of this repository is to facilitate the integration of these tools with desktop applications, allowing them to remain portable and function correctly across different Windows versions: Home, Pro, and Server.

These tools follow best development practices, including the recommendation to **use a separate D drive apart from the Windows C drive** for storing data. This approach allows:  
- Easier data restoration.  
- Avoiding interference with operating system performance.  
- Keeping your work or test PC/laptop stable.

## Structure

- `GAWK/` : Contains the portable version of `gawk.exe` along with the required `.dll` files.

## Usage

1. Copy the relevant folder to your portable application's directory, preferably on a separate data drive (e.g., `D:\Tools`).  
2. Run the utility directly from the folder without installation.  
3. Integrate with your desktop application as needed.

## Contributions

If you want to add more portable tools, please create a **pull request** and make sure to maintain the folder structure consistently.
