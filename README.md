Network Traffic Analyzer

Two implementations of a real-time network traffic analyzer built in Python and C++. Both versions capture packets directly from the network interface, analyze protocol information, and provide live traffic statistics.

Features
Real-time packet capture
Protocol header parsing
Network traffic monitoring
Live statistics and analysis
Packet filtering support
Traffic visualization and reporting

## Implementations

| Implementation | Technology Stack | Highlights |
|---|---|---|
| C++ Version | C++20, libpcap, FTXUI | High-performance packet capture, interactive terminal interface, thread-safe statistics |
| Python Version | Python, Scapy, Rich, Matplotlib | Packet analysis, filtering, multi-threading, traffic visualization |

## Quick Start

### C++ Version

```bash
cd cpp
./install.sh
just run -i eth0
```

### Python Version

```bash
cd python
uv sync
sudo netanal capture -i eth0
```
