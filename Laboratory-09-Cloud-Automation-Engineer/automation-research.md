# Automation Research

## 1. Bash Script and Shebang

A Bash script is a file containing commands that a Linux system can execute in sequence to automate tasks. The line `#!/bin/bash` is called the shebang. It tells the system to use the Bash interpreter to run the script.

## 2. Variables

Variables store values that a script can reuse. For example, `$BACKUP_DIR` stores the name or path of the backup directory. Using a variable makes the script easier to maintain because the directory can be changed in one place instead of editing the same path in several commands.

## 3. Cron Job

A cron job is a scheduled task in Linux that runs automatically at a specified time or interval. It is useful in cloud operations because administrators can schedule recurring tasks, such as backups and maintenance, without manually running each command.
