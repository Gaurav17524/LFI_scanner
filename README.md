# Simple LFI (Local File Inclusion) Vulnerability Scanner

This is a simple Local File Inclusion (LFI) vulnerability scanner written in Python. It can be used to identify potential LFI vulnerabilities in a target system by testing various payloads.

## Usage

### Prerequisites

- Python 3.x
- Required Python packages: `requests`, `argparse`, `colorama`

Install the required packages using:

```bash
pip install requests argparse colorama

```
Running the Scanner:
====================

python lfi_scanner.py -u <target_url>


Example:
  python lfi_scanner.py -u http://example.com




Author
-Gaurav Khaitan

Disclaimer:
=============
This tool is provided for educational and informational purposes only. The author is not responsible for any misuse or damage caused by this tool.


