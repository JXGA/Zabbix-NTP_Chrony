# Zabbix-NTP_Chrony
ntp / chrony monitoring on linux

Monitors chrony for both remote servers (^ indicated on chronyc command) or locally connected ref clocks (# indicated)

Chrony Offset & Jitter measurements require 'GAWK'
```
sudo apt install gawk 
```

![](/ntp_items.png)
![](/ntp_triggers.png)
