# port-scanner-# Async Port Scanner (educational)

Simple asynchronous TCP port scanner (Python 3.8+). Intended for authorized testing and lab use only.

Usage:
  python3 port_scanner.py --host 127.0.0.1 --start 1 --end 1024 --banner --json results.json

Example:
  # Start a local HTTP server on 8080
  python3 -m http.server 8080
  # Scan localhost
  python3 port_scanner.py --host 127.0.0.1 --ports 22,80,8080 --banner

Warning:
  Use only on systems you own or have written permission to test.
