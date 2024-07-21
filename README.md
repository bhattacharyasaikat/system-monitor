# System Monitoring Script

A shell script for monitoring system metrics including CPU usage, memory usage, disk space, and network activity. The script logs the results to a file and sends email alerts if any of the metrics exceed predefined thresholds.

## Features

- Monitor CPU usage
- Monitor memory usage
- Monitor disk space
- Monitor network activity
- Log monitoring results
- Send email alerts for high usage

## Requirements

- POSIX-compliant `sh` shell
- `mailutils` (for sending email alerts)
- Access to `/sys/class/net/` for network statistics

