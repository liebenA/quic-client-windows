# quic-client-windows

A lightweight Windows client designed to automatically run QUIC performance tests against **emes.bj:4447**.

---

## Installation

- Download and extract **quic-client-windows.zip**
- Right-click **install-quic-client-windows.bat** and **Run as Administrator**
- Windows will display a security prompt related to copying files and creating scheduled tasks


---

## How it works

- The client runs **3 QUIC tests** sequentially every **1 hour**
- Execution is completely silent (no visible window)
- Logs are stored in : `C:\quic-client\logs\`
- Each test generates a timestamped log file with start time, stop time and exit status.

---

## Checking the scheduled task

Open **Task Scheduler**
Look for the task : QuicClientTests1h

---



