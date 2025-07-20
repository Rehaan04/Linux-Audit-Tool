# Linux-Audit-Tool
This is a simple Python-based tool that audits a Linux system for basic security hygiene. It's designed for beginners in cybersecurity and cloud security to learn how to identify misconfigurations and harden a system.

# What It Checks
1) Is the UFW firewall enabled?
2) Is SSH root login allowed?
3) Is password authentication for SSH enabled?
4) Are file permissions secure on `/etc/passwd` and `/etc/shadow`?

# Sample Output
- Checking if UFW firewall is active...
- UFW firewall is active

- Checking SSH configuration...
- Root login is allowed over SSH!
- Password authentication is disabled

- Checking file permissions...
- /etc/passwd permissions are correct
- /etc/shadow permissions are too open: -rw-r--r--
- Suggestion: Run 'sudo chmod 600 /etc/shadow'

- Final Security Score: 20/30

 # Built with
 - Python 3
 - `os` and `datetime` modules (standard)



