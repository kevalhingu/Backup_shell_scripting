# Shell Script Backup System

This shell script provides a simple and effective backup solution for a specified directory. The script creates timestamped backup folders and allows for rotation to keep the most recent backups, ensuring efficient storage management.

## Usage

To use the script, provide the path to the source directory as a command-line argument:

```bash
./backup_script.sh /path/to/source_directory
```

## Example
```bash
./backup_script.sh ~/Documents/my_project
```

# Functionality

## 1. Creating Backups

The script generates a timestamped backup folder in the specified source directory. Each backup is named in the format `backup_YYYY-MM-DD_HH-MM-SS`.

## 2. Rotation Policy

To prevent excessive storage usage, the script performs rotation by keeping only the last 3 backups. Older backups are automatically removed.

# Requirements

- Bash environment
- Valid directory path as a command-line argument

# How to Contribute

Feel free to contribute to the improvement of this script by:

1. Identifying and fixing bugs.
2. Enhancing script functionality.
3. Improving documentation.
