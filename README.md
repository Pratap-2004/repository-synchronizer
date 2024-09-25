# Repository/Directory Synchronizer

This Python project allows automatic synchronization between a local directory and a remote directory via SFTP, using `paramiko` and `watchdog` libraries.

## Features:
- Two-way synchronization between local and remote directories.
- Detects file changes, creation, deletion, and movement.
- Updates files based on their modification time and size.

## Requirements:
Install the required libraries using:
```bash
pip install -r requirements.txt
