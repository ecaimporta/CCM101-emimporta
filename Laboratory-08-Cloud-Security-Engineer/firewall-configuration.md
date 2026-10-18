# Firewall Configuration

## Allow SSH
The following command allows SSH connections: `ufw allow ssh`

## Configure the Default Deny Policy
The following commands block incoming connections by default while allowing outgoing connections:
- `ufw default deny incoming`
- `ufw default allow outgoing`
- `ufw enable`

## Allow the Web Application Port
The following command allows TCP traffic on port 8080: `ufw allow 8080/tcp`

## Why SSH Must Be Allowed First
If the firewall is enabled before allowing SSH, remote SSH access may be blocked, preventing an administrator from managing the server remotely.
