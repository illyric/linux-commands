# General commands

|Command|Meaning|Example|
|:----- |:----- |:----- |
| ls | lists files in current directory |`$ ls` |
| ps aux | shows all running processes for all users | `$ ps aux | grep java` will show all java running processes |
| lsof | I use it to find which services/processes use which port | `$ lsof -i tcp:9200` will display the current process that is using port 9200. Since the PID is also displayed, I can easily kill that process via `kill -9 <PID>` command to free that port
| scp | Secure Copy: copy files from one host to another. Like a a `cp` command throughout a network. | `$ scp username@host:foo.bar /some/local/dir` copies foo.bar from a remote host to local, `scp foo.bar username@remotehost:/some/remote/dir` copies the file foo.bar from the local machine to a remote host. To copy a dir: `$ scp -r foo_dir username@remote_host:/some/remote/dir`|
|whoami|prints the current user|`$ whoami` will display ilirk on my laptop|
