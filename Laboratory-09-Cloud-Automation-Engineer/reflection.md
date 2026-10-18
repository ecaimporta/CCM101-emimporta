cat > reflection.md <<'EOF'
# Reflection — The Cloud Automation Engineer

Cloud automation is important because cloud environments can contain hundreds or even thousands of servers. Performing every task manually takes time and may lead to inconsistent results. Scripts and scheduled jobs help administrators repeat tasks such as backups and maintenance more efficiently. Automation also allows engineers to focus on tasks that require careful investigation.

However, automation can be dangerous when a script contains an error. For example, a destructive command with an incorrect path could affect many servers if it were deployed without proper checks. Engineers should review scripts, test them in a safe environment, limit permissions, and verify results before using them widely. Backups and recovery plans are also important.

A Bash script and Docker Compose YAML serve different purposes. A Bash script contains commands that the operating system executes in sequence, such as creating directories and compressing files. Docker Compose uses a YAML configuration file to describe application services, networks, and storage for containers. Both reduce manual work, but they automate different parts of system administration.

From Laboratory 1 to Laboratory 9, my understanding of cloud computing has developed through practical activities involving Linux commands, containers, monitoring, security, and automation. I have learned that cloud operations requires more than starting an application. Engineers must also monitor systems, protect services, document changes, and plan reliable maintenance.

The role I find interesting is Cloud Operations Engineer because it combines troubleshooting, automation, monitoring, and security. I want to improve my Linux and scripting skills so I can manage systems more efficiently. This laboratory showed me how a small script and a scheduled task can support consistent operations when they are tested, documented, and used responsibly.
EOF
