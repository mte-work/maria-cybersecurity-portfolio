# **Networking Command Practice**

This file documents basic networking commands and explains their relevance to cybersecurity.


## Command 1:_ ip addr_

<img width="1227" height="462" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/dbbbc17c-cb10-493b-a9be-b2d65ac92293" />

### _Purpose_
The `ip addr` command displays network interfaces and their assigned IP addresses.

### _Why This Matters in Cybersecurity_
Understanding network interfaces and IP addressing is essential for:
- Identifying system exposure
- Troubleshooting connectivity issues
- Analyzing network-based attacks

### Command
```bash
ip addr
```

## Command 2: _ip route_

<img width="864" height="80" alt="image" style="width:50%; height:auto;" src="https://github.com/user-attachments/assets/423e4627-16ce-4a14-9a45-11f08bb7e954" />


### _Purpose_
Displays the routing table used by the system to determine where network traffic is sent.

### Why This Matters in Cybersecurity
The routing table reveals how data exits the system, including default gateways,
which is essential when analyzing network access and potential data leakage paths.

### _Command_
```bash
ip route
```


