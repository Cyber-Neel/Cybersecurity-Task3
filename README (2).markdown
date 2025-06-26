# Cybersecurity Internship Task 3: Vulnerability Scan

**Author**: Neel Bhatt  
**Date**: June 26, 2025  
**Repository**: Cybersecurity-Task3

## Objective
Perform a basic vulnerability scan on my PC to identify common security issues.

## Tools Used
- **Nmap**: Used as a fallback due to OpenVAS setup failures.

## Steps Performed
1. Attempted to set up OpenVAS but faced `openvas-scanner.service not found` error.
2. Ran a quick Nmap scan on localhost (127.0.0.1).
3. Reviewed results showing all ports closed and took a screenshot.
4. Documented findings in `vulnerability_report.txt`.

## Files Included
- `vulnerability_report.txt`: Report of vulnerabilities and mitigations.
- `scan_results.txt`: Nmap scan output.
- `scan_results.png`: Screenshot of the scan process.

## Key Learnings
- Learned to troubleshoot OpenVAS installation issues.
- Understood that closed ports indicate a secure network perimeter.
- Recognized limitations of external scans for internal vulnerabilities.

## Challenges
- `openvas-scanner.service` failed to start; resolved by using Nmap.
- Scan showed no vulnerabilities, possibly due to firewall.

## Acknowledgments
- Elevate Cybersecurity Internship for the task.
- Neel Bhatt for completing the task.

This repository represents my work for Task 3, submitted with permission.