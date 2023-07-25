# ping2 - IP Address Ping Utility

![Ping2 Logo](path/to/your/ping2_logo.png)

## Description

`ping2` is a Python-based command-line utility that allows users to perform ping tests on one or multiple IP addresses. It sends ICMP echo requests to the specified IP addresses and displays detailed information about packet loss, round-trip times (RTT), and time-to-live (TTL). The ping results are presented in a well-organized table format, making it easy to analyze the network health of various destinations at a glance.

## Features

- Perform ping tests on one or multiple IP addresses.
- Display packet loss, RTT times, and TTL information for each address.
- Output ping results in a tabular format for easy analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Issues](#issues)
- [Acknowledgments](#acknowledgments)

## Installation

1. Clone this repository.

```bash
git clone https://github.com/rezabojnordi/ping2.git
```

### Change directory to the ping2 folder.
```bash
chmod +x ping2.py
```
### Usage
To run the ping2 command, open a terminal and navigate to the ping2 directory. Then use the following syntax:
``` bash
./ping2.py <ip1> <ip2> ...

```
Replace <ip1>, <ip2>, etc., with the IP addresses you want to ping.


### Example
To ping Google's public DNS server (8.8.8.8) and Cloudflare's public DNS server (1.1.1.1), use the following command:
```
./ping2.py 8.8.8.8 1.1.1.1

```
### How to install Package
```
sudo dpkg -i ping2.deb
```
