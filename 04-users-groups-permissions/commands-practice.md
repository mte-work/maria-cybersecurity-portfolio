# User, Group, and Permission Practice

This file documents Linux commands related to access control and authorization.

## Command 1: ![whoami](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/04-users-groups-permissions/screenshots/03-processes-and-ports-screenshots.md#command-1-whoami)

### Purpose
Displays the username of the currently logged-in user.

### Why This Matters in Cybersecurity
Identifying the current user helps verify privilege levels and ensures commands are being executed under the expected account.

### Command
```bash
whoami
```

## Command 2: ![id](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/04-users-groups-permissions/screenshots/03-processes-and-ports-screenshots.md#command-2-id)

### Purpose
Displays the user’s UID, primary group, and supplementary group memberships.

### Why This Matters in Cybersecurity
Group membership determines what resources a user can access. Understanding user and group IDs helps identify privilege levels and potential avenues for unauthorized access or privilege escalation. You’ll see:
- User ID (UID)
- Group ID (GID)
- Supplementary groups

### Command
```bash
id
```


