# Python Port Scanner

A simple Python-based port scanner that allows you to:
- Choose between custom port ranges or predefined ranges
- Display progress using `tqdm` progress bar
- Gracefully handle `Ctrl+C` (KeyboardInterrupt) to stop scanning
- Save scan results to a text file
- Highlight common service ports (HTTP, HTTPS, SSH, FTP, DNS, SMTP)

## Features
-  Custom or default port range selection
-  Shows progress with `tqdm`
-  Open ports highlighted in green with service name if known
-  Result saved as `scan_results.txt`
-  Clean and beginner-friendly code

## Requirements
- Python 3.x
- Modules:
  - `tqdm`
  - `colorama`

Install dependencies:
```bash
pip install tqdm colorama

Usage

Run the script:

python port_scanner.py

👉 Follow on-screen prompts to select the port range.
Example output

Scanning target: 127.0.0.1
Port range: 20-1024
----------------------------------------
Port 80 is open (HTTP)
Port 443 is open (HTTPS)
```
Scan complete...

License

This project is licensed under the MIT License.