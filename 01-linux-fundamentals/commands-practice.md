
## Command 1: _whoami_
<img width="395" height="56" alt="image" src="https://github.com/user-attachments/assets/70fab8a4-411a-45d3-9d1d-fad0ab19f911" />

### _Purpose_
The `whoami` command displays the username of the currently logged-in user.

### _Why This Matters in Cybersecurity_:
Knowing which user account is active is important when:
- Investigating suspicious activity
- Verifying privilege levels
- Confirming access context during incident response

### Command
```bash
whoami
```

## Command 2: _ls /_
<img width="906" height="159" alt="image" src="https://github.com/user-attachments/assets/29e7dae9-e2ca-426b-8752-05d12dc4a06a" />

### _Purpose_:
The `ls /` command lists the contents of the root directory.

### _Why This Matters in Cybersecurity_:
Understanding the Linux filesystem structure is essential for:
- Locating configuration files
- Reviewing logs
- Navigating systems during forensic analysis

### Command
```bash
ls /
```

## Command 3: _pwd_

<img width="342" height="52" alt="image" src="https://github.com/user-attachments/assets/b0c40136-008a-4769-892d-6cdd083eea43" />

### _Purpose_:
The `pwd` command displays the current working directory.

### _Why This Matters in Cybersecurity_:
Knowing your current location is critical when:
- Investigating files
- Running commands that affect the system
- Avoiding accidental changes in sensitive directories

### Command
```bash
pwd
```

## Command 4: _cd_

<img width="380" height="214" alt="image" src="https://github.com/user-attachments/assets/d5f0784d-a201-4012-bfe0-17da163bbe42" />

### _Purpose:_
The `cd` command is used to change directories.

### _Why This Matters in Cybersecurity:_
Navigating directories safely is essential when:
- Inspecting logs
- Reviewing configuration files
- Performing forensic analysis without altering data

### Commands
```bash
cd /
pwd
cd ~
```

## Command 5: ls -l

<img width="717" height="294" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/bf64cdfc-e0e4-4739-a267-caec75c2181b"  />

### Purpose
The `ls -l` command lists files and directories in long format, including permissions and ownership.

### Why This Matters in Cybersecurity
File permissions help determine:
- Who can read, write, or execute a file
- Whether a file could be abused or misconfigured
- Potential privilege escalation risks

### Command
```bash
ls -l
```


