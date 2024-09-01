# perf-grabber
Terminal based performance data collector for R36S consoles

> Required: `openpyxl`

> Optional: `pysftp`

**For standalone use:** comment out the sftp upload part in the code.

**For SFTP upload:** server IP and absolute path are requierd.

## For ease of use

1. Connect WiFi dongle/USB Tether and establish connection
2. Enable remote services in options
3. SSH into your console (Default username: `ark` Default password: `ark`)
4. Install libraries with `pip install openpyxl` and  `pip install pysftp`
5. Edit perf_grabber.py with nano
6. Comment out SFTP part or provide ``IPADDRESS`` and ``SERVERPATH``
7. Run program with `python3 perf_grabber.py` 
   
>Tip: use ``tmux`` with 2 panes for grabbing and testing with sysbench
