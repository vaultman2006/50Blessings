# 50Blessings

Hotline Miami-themed fork of [Sherlock](https://github.com/sherlock-project/sherlock).

Find usernames across social networks and check digital footprints.

## Features

- Username search across hundreds of sites
- Headless browser mode for Cloudflare-protected sites
- Wayback Machine and archive checks for deleted accounts
- `--disable-archive` flag for faster scans
- Multiple scanning profiles (Jacket Modes)

## Requirements

- Python 3.9+
- Git

## Installation (Windows)

1. Install Python and Git
2. Open PowerShell and run:

```powershell
git clone https://github.com/YOUR_USERNAME/50Blessings.git
cd 50Blessings
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -e .
