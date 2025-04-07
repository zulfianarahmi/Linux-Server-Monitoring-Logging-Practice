# Linux Server Monitoring & Logging Practice

This is a beginner-friendly walkthrough of how I practiced setting up **monitoring, logging, and basic server security** on a Linux server. Just me learning the basics, step by step.

## What I did

- Monitored server usage (CPU, RAM, Disk) with `htop` and `netdata`
- Checked system logs with `journalctl`, `dmesg`, and `syslog`
- Installed `fail2ban` to block brute-force login attempts
- (Optional) Planning to try Prometheus + Grafana later

## Tools I used

| Tool       | What it's for                      |
| ---------- | ---------------------------------- |
| htop       | See live CPU, RAM, process info    |
| netdata    | Web-based real-time server monitor |
| fail2ban   | Stops SSH brute-force attacks      |
| journalctl | System logs viewer (modern way)    |
| dmesg      | Kernel logs (boot/hardware issues) |
| syslog     | Old but gold general logs          |
