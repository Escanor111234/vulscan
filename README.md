# vulscan# VulScanner

VulScanner is a lightweight, containerized vulnerability scanner that combines OpenVAS and Nmap for security assessments.

## Features
- **OpenVAS**: Comprehensive vulnerability scanning with a web UI.
- **Nmap**: Fast and flexible network scanning.
- **Docker-based**: Easy deployment and management.

## Installation
Follow the steps in `vulscanner_setup.md` to set up the scanner on your AWS instance or local machine.

## Usage
- Access OpenVAS UI at `http://localhost:9392`
- Run Nmap scans using provided commands in `vulscanner_commands.sh`

## Cleanup
To stop and remove VulScanner:
```bash
docker stop vulscanner && docker rm vulscanner
```
