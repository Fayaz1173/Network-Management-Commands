# Network management commands

### 1`ifconfig`

**Purpose:**

Used to display network interface configuration.

**Command Used:**

```bash
ifconfig
```

**Observation:**

The command displays available network interfaces, their IP addresses, netmask, and operational status.

**Result:**

Network interface details were successfully retrieved.

---

### 2 `ip`

**Purpose:**

Modern tool for managing IP addresses and routing tables.

**Commands Used:**

```bash
ip addr
ip route
```

**Observation:**

The output showed active interfaces, assigned IP addresses, and the default gateway.

**Result:**

IP configuration and routing information were verified.

---

### 3 `ping`

**Purpose:**

Used to test connectivity between the local system and a remote host.

**Command Used:**

```bash
ping google.com
```

**Observation:**

Successful ICMP replies indicated network reachability and acceptable latency.

**Result:**

Connectivity to the remote host was confirmed.

---

### 4 `netstat`

**Purpose:**

Displays active network connections and listening ports.

**Command Used:**

```bash
netstat -tuln
```

**Observation:**

The command listed services listening on various TCP and UDP ports.

**Result:**

Active network services were identified.

---

### 5 `ss`

**Purpose:**

A faster alternative to `netstat` for inspecting socket information.

**Command Used:**

```bash
ss -tuln
```

**Observation:**

Displayed socket statistics with improved speed and clarity.

**Result:**

Socket-level network information was successfully analyzed.

---

### 6 `traceroute`

**Purpose:**

Traces the route taken by packets to reach a destination host.

**Command Used:**

```bash
traceroute google.com
```

**Observation:**

Each hop along the network path was displayed, showing intermediate routers.

**Result:**

The packet route to the destination was successfully traced.

---

### 7 `nmap`

**Purpose:**

Used for network discovery and service enumeration.

**Commands Used:**

```bash
nmap 192.168.1.1
nmap -sn 192.168.1.0/24
```

**Observation:**

Open ports and running services were identified on the target host, and live hosts were detected on the local network.

**Result:**

Network scanning and host discovery were successfully performed.

---
