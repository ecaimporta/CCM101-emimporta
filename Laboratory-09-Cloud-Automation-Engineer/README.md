# Mission 9 — The Cloud Automation Engineer

## Mission Overview

This laboratory explores Bash scripting and cron jobs to automate routine Linux administration tasks. A Bash script is used to compress sample application data into a timestamped backup archive.

## Objectives

- Understand Bash scripts, shebangs, and variables.
- Create a backup script using nano.
- Apply execute permission using `chmod +x`.
- Run the script and verify the backup archive.
- Schedule an automated task using cron.
- Document the process and reflect on cloud automation.

## Commands Executed

- `mkdir -p app-data` — create the sample data directory.
- `echo "This is critical client data." > app-data/data.txt` — create a sample data file.
- `nano backup.sh` — create or edit the Bash script.
- `chmod +x backup.sh` — make the script executable.
- `./backup.sh` — run the backup script.
- `ls -l backups/` — verify the archive.
- `crontab -l` — display scheduled cron jobs.
- `env EDITOR=nano crontab -e` — edit the cron schedule.
- `git add`, `git commit`, and `git push` — save and upload the work.

## Skills Learned

This mission developed skills in Bash scripting, Linux file permissions, compressed backups, cron scheduling, Markdown documentation, and Git-based portfolio management.

## Screenshots

- `screenshots/script-execution.png` — successful backup execution and archive verification.
- `screenshots/cron-schedule.png` — installed cron schedule.
