# Automated System Monitoring Tool

**Course:** OPS262 - Operating Systems II  
**Grade:** 84% (Distinction)  
**Date:** August 2025

---

## Project Overview

A PowerShell-based system monitoring and reporting tool designed to help system administrators:
- Track CPU usage and identify resource-heavy processes
- Manage system services (start/stop/restart)
- Generate professional HTML and CSV reports
- Log errors for troubleshooting

---

## Key Features

- **CPU Monitoring** - Detects processes using excessive CPU time
- **Service Management** - Lists running/stopped services with error handling
- **System Information** - Retrieves OS, BIOS, and hardware details
- **Reporting** - Auto-generates HTML reports and CSV exports
- **Module Packaging** - Reusable PowerShell module with 3 core functions

---

## Technologies Used

- PowerShell
- Microsoft.PowerShell.Management module
- HTML/CSV reporting
- Error logging with try/catch/finally

---

## Sample Code

```powershell
# Import the monitoring module
Import-Module SystemMonitoring

# Check system info
Get-SystemInfo

# View service status
Get-ServiceStatus

# Find top CPU processes
Get-TopProcesses
