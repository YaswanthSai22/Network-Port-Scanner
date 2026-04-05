# Network Port Scanner

## Overview

This is a simple yet powerful network port scanner implemented in Python. It is designed to help users identify open ports on servers within a specified IP range. 

## Features
- Scans specified ports to check if they are open or closed.
- Supports both individual IP scanning and a range of IP addresses.
- Provides options to specify ports to scan or use a default range.
- Results are displayed in real-time, showing which ports are open or closed.

## Requirements
- Python 3.x
- The following libraries:
  - `socket`
  - `threading`

You can install the required libraries using `pip`:
```bash
pip install socket threading
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/YaswanthSai22/Network-Port-Scanner.git
   cd Network-Port-Scanner
   ```
2. Run the script:
   ```bash
   python port_scanner.py <target_ip> <start_port> <end_port>
   ```
   Example:
   ```bash
   python port_scanner.py 192.168.1.1 20 100
   ```

## Parameters
- `<target_ip>`: The IP address of the target host.
- `<start_port>`: The starting port number for the scan.
- `<end_port>`: The ending port number for the scan.

## Contributions
Contributions are welcome! Please create an issue or submit a pull request if you would like to contribute to the project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.