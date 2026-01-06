# Process and Port Visibility Practice

This file documents commands used to identify running processes and listening network ports.

## Command 1: ![_ps aux_](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/03-processes-and-ports/screenshots/03-processes-and-ports-screenshots.md#command-1-ps-aux)

### _Purpose_
Displays all running processes on the system along with ownership and resource usage.

### _Why This Matters in Cybersecurity_
Identifying running processes helps detect:
- Unauthorized software
- Malicious processes
- Abnormal resource usage

### Command
```bash
ps aux
```

## Command 2: ![ss -tuln](https://github.com/mte-work/maria-cybersecurity-portfolio/blob/Portfolio/03-processes-and-ports/screenshots/03-processes-and-ports-screenshots.md#command-2-ss--tuln)

### Purpose
Displays all listening network sockets (TCP/UDP) along with their ports. Ports types:
- `-t` → TCP connections
- `-u` → UDP connections
- `-l` → only listening ports
- `-n` → numeric addresses (no DNS resolution)

### _Why This Matters in Cybersecurity_
Open ports are potential attack vectors. Monitoring and understanding them is crucial to:
- Identify unauthorized services
- Detect potential entry points
- Audit system exposure

### Command
```bash
ss -tuln
```


