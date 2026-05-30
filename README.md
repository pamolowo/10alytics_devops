# Linux Networking Commands Cheat Sheet

| Command | Description |
|----------|-------------|
| `ip` | View and configure network interfaces, routes, and IP addresses. |
| `ping` | Test connectivity to a host. |
| `traceroute` | Trace the path packets take to a destination. |
| `ss` | Display active network connections and listening ports. |
| `netstat` | View network connections, routing tables, and statistics. |
| `nslookup` | Query DNS records. |
| `dig` | Advanced DNS lookup and troubleshooting. |
| `tcpdump` | Capture and analyze network packets. |
| `curl` | Transfer data to or from servers using various protocols. |
| `wget` | Download files from the web. |
| `hostname` | Display or set the system hostname. |
| `arp` / `ip neigh` | View and manage ARP cache entries. |
| `route` / `ip route` | View and modify routing tables. |
| `nmap` | Network discovery and port scanning. |
| `iftop` | Monitor network bandwidth usage in real time. |

## Example Usage

```bash
# Show IP addresses
ip addr show

# Test connectivity
ping google.com

# Trace network path
traceroute google.com

# View listening ports
ss -tuln

# DNS lookup
nslookup google.com

# Advanced DNS query
dig google.com

# Capture packets
sudo tcpdump -i eth0

# Download a file
wget https://example.com/file.zip

# Scan open ports
nmap 192.168.1.1

# Monitor bandwidth
sudo iftop
```