# Backup Script Guide

## Purpose

The backup script automates the creation of a compressed backup of the app-data directory. It creates a backups directory when needed and names each archive using the current date and time.

## Bash Script

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

mkdir -p $BACKUP_DIR

tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"
```

## Making the Script Executable

The command `chmod +x backup.sh` adds execute permission to the script. This allows the user to run it with `./backup.sh`.

## Running the Script

Run `./backup.sh` from the directory containing `app-data`. The script creates a timestamped `.tar.gz` archive inside `backups/`. Use `ls -l backups/` to verify the archive.

## Cron Job Schedule

The scheduled command is:

`0 2 * * * /root/backup.sh`

The five cron fields mean:

- Minute: `0` — at minute zero
- Hour: `2` — at 2 AM
- Day of Month: `*` — every day of the month
- Month: `*` — every month
- Day of Week: `*` — every day of the week

This schedule runs the script every day at 2:00 AM.

## Important Note

Backups should be verified regularly. Administrators should also test restoring files and store another copy of important backups in a separate location.
