# User, Group, and Permission

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

## Command 3: ![groups](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/04-users-groups-permissions/screenshots/04-users-groups-permissions-screenshots.md#command-3-groups)

### Purpose
Displays the groups the current user is a member of.

### Why This Matters in Cybersecurity
Group membership determines access to shared resources and administrative privileges. Using groups instead of individual user permissions reduces the risk of excessive access.

### Command
```bash
groups
```

## Command 4: ![ls -l](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/04-users-groups-permissions/screenshots/04-users-groups-permissions-screenshots.md#command-4-ls--l) (ownership/permissions)

### Purpose
Displays file ownership, group ownership, and permission settings.

### Why This Matters in Cybersecurity
File permissions determine which users and groups can access or modify files. Improper ownership or group permissions can allow unauthorized access to sensitive data. Each digit represents permissions for one role. You add the values together:

| Permission  | Value |
| ----------- | ----- |
| read (r)    | 4     |
| write (w)   | 2     |
| execute (x) | 1     |


```bash
- rw- --- ---
  ^    ^   ^
  |    |   |
Owner Group Others
```


### Command
```bash
ls -l
```

## Command 5: ![stat]()

### Purpose
Displays detailed file information including permissions, ownership, and timestamps.

### Why This Matters in Cybersecurity
Detailed file metadata helps verify permission settings and investigate unauthorized file access or modification. Linux uses group-based access control to limit permissions based on roles rather than individual users. This approach reduces privilege sprawl and improves security by ensuring users only have access to resources required for their role.

### Command
```bash
stat filename
```

The `stat` command was used to verify file ownership, permissions, and metadata. The file was restricted to owner-only access (`0600`), demonstrating least-privilege configuration. Metadata timestamps showed permission changes without content modification.
