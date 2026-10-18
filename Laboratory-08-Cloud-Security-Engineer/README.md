# Laboratory 08 — The Cloud Security Engineer

## Mission Overview
This mission explores Linux server security through network auditing, firewall configuration, and the principle of least privilege.

## Objectives
- Understand the Principle of Least Privilege and attack surface.
- Audit network ports and services.
- Configure UFW with a default-deny incoming policy.
- Allow SSH and the required application port.
- Document security procedures and lessons learned.

## Commands Executed
- `docker ps -a`
- `docker run -d --name secure-web-app -p 8080:80 nginx`
- `curl http://localhost:8080`
- `ufw allow ssh`
- `ufw default deny incoming`
- `ufw default allow outgoing`
- `ufw enable`
- `ufw status verbose`
- `ufw allow 8080/tcp`
- `ufw status numbered`

## Skills Learned
This mission practices container verification, firewall rule configuration, network exposure reduction, security documentation, and GitHub portfolio management.
