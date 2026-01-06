## Command 1: ![_whoami_](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/01-linux-fundamentals/screenshots/01-linux-fundamentals-screenshots.md#command-1-whoami)

<!--<img width="395" height="56" alt="image" src="https://github.com/user-attachments/assets/1cebec89-a36e-4ba9-b36e-86a6b772d42f" /> -->

### _Purpose_:
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

## Command 2: ![_ls /_](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/01-linux-fundamentals/screenshots/01-linux-fundamentals-screenshots.md#command-2-ls-)

<!-- <img width="906" height="159" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/29e7dae9-e2ca-426b-8752-05d12dc4a06a" /> -->

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

## Command 5: _ls -l_

<img width="717" height="294" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/bf64cdfc-e0e4-4739-a267-caec75c2181b"  />

### Purpose
The `ls -l` command lists files and directories in long format, including permissions and ownership.

### _Why This Matters in Cybersecurity:_
File permissions help determine:
- Who can read, write, or execute a file
- Whether a file could be abused or misconfigured
- Potential privilege escalation risks

### Command
```bash
ls -l
```

## Command 6: _chmod_

<img width="827" height="128" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/388f2f26-16f3-4dc7-81d1-54a1b7ae06e8" />

### _Purpose_:
The `chmod` command changes file permissions.

### _Why This Matters in Cybersecurity:_
Incorrect file permissions can:
- Expose sensitive data
- Allow unauthorized modification
- Lead to privilege escalation

Understanding and correcting permissions is a core security responsibility.

### Commands
```bash
ls -l permission-test.txt
chmod 600 permission-test.txt
ls -l permission-test.txt
```

## Command 7: _Viewing system logs_

<img width="949" height="295" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/459c6f93-6f8a-4bff-af40-eb85f61dca2e" />

### _Purpose:_
System logs record events related to authentication, system behavior, and application activity.

### _Why This Matters in Cybersecurity:_
Logs are essential for:
- Detecting unauthorized access
- Investigating incidents
- Understanding system behavior over time

Security analysts rely heavily on logs during investigations.

### Command
```bash
ls /var/log
```




