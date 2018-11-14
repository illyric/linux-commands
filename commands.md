# General commands

|Command|Meaning|Example|
|:----- |:----- |:----- |
| ls | lists files in current directory |`$ ls` |
| ps aux | shows all running processes for all users | `$ ps aux | grep java` will show all java running processes |
| lsof | I use it to find which services/processes use which port | `$ lsof -i tcp:9200` will display the current process that is using port 9200. Since the PID is also displayed, I can easily kill that process via `kill -9 <PID>` command to free that port
