# Minecraft server

## Installation

1. Install minecraft in /opt
1. Copy *minecraft.service* file in */etc/systemd/system* directory.
1. Test server using ```sudo systemctl start minecraft.service```
1. Enable server at startup using ```sudo systemctl enable minecraft```

## Usefull commands

* View logs using command ```journalctl -u minecraft.service``` or ```view_logs.sh``` script
* Stop server using comand ```journalctl stop minecraft.service```
