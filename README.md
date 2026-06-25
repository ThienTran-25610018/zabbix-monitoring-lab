# Zabbix Infrastructure Monitoring Lab

## Overview
Triển khai hệ thống monitoring Zabbix 7.0 trên môi trường VMware, 
mô phỏng hạ tầng IT thực tế trong môi trường ngân hàng.

## Lab Architecture
- **Zabbix Server**: Rocky Linux 9 - Zabbix 7.0 LTS
- **Windows Server**: Windows Server 2019 (giả lập máy nhân viên)
- **Platform**: VMware Workstation

## Features
- Monitor 3 hosts realtime (CPU, RAM, Disk, Network)
- 3 custom triggers: CPU >80%, RAM <20%, Disk >90%
- Automated alert via Telegram Bot
- Custom dashboard with graphs and problem tracking
- SNMP monitoring ready

## Technologies
- Zabbix 7.0 LTS
- Rocky Linux 9
- Windows Server 2019
- MariaDB
- Nginx + PHP-FPM
- VMware Workstation

## Results
- Phát hiện và xử lý sự cố CPU 100% thành công
- Alert Telegram tự động khi có problem và resolved
- Uptime monitoring 3 hosts liên tục
