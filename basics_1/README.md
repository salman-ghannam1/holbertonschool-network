# Networking Basics #1

This project focuses on basic networking concepts in Linux and network configuration using Bash scripts.

## Learning Objectives

By the end of this project, you should be able to explain:

- What localhost (127.0.0.1) is
- What 0.0.0.0 means
- What the `/etc/hosts` file is used for
- How hostname resolution works
- How to display active network interfaces
- How to listen on a TCP port using Netcat
- Basic network troubleshooting techniques

## Requirements

- Ubuntu 22.04 LTS
- Bash scripts must be executable
- Scripts must pass ShellCheck without errors
- All files must end with a new line
- The first line of every script must be:

```bash
#!/usr/bin/env bash
```

- The second line must contain a comment describing the script

## Project Files

| File                          | Description                                       |
| ----------------------------- | ------------------------------------------------- |
| 0-change_your_home_IP         | Configures hostname resolution using `/etc/hosts` |
| 1-show_attached_IPs           | Displays all active IPv4 addresses on the machine |
| 2-port_listening_on_localhost | Listens on port 98 on localhost using Netcat      |

## Concepts Covered

### Localhost

`localhost` refers to the local machine and commonly resolves to:

```text
127.0.0.1
```

### 0.0.0.0

Represents all available network interfaces on a machine.

### /etc/hosts

A local file used to map hostnames to IP addresses before DNS lookups are performed.

### Netcat (nc)

A networking utility used for reading from and writing to network connections.

## Author

Salman Almutairi
