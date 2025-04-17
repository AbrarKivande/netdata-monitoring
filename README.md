# Netdata Monitoring - Task 7 (DevOps Internship)

This project is part of Task 7 for the DevOps Internship. The objective is to monitor system resources using Netdata, a lightweight real-time monitoring tool, via Docker on a Windows system.

## 🛠 Tools Used

- Docker Desktop (Windows)
- Netdata (official Docker image)

## 📌 Task Overview

Netdata was installed and run inside a Docker container to visualize system performance metrics like:

- CPU usage
- Memory consumption
- Disk I/O
- Network activity
- Docker container performance

## ⚙️ Installation & Setup

To run Netdata locally using Docker:

```bash
docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
```

Once the container is up and running, visit:

http://localhost:19999

This opens the Netdata dashboard where you can view real-time metrics and system performance charts.

📷 Output

A screenshot of the Netdata dashboard displaying system metrics has been included in this repository as proof of successful setup and monitoring.

📁 Repository Contents

. netdata-dashboard.png – Screenshot of the running Netdata dashboard
. README.md – Documentation of task execution and setup steps

✅ Outcome

Successfully deployed Netdata using Docker on Windows, monitored various system metrics in real-time, and submitted the task with the required artifacts.
