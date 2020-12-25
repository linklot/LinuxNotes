# LinuxNotes

========
Docker

------
Run Docker Commands as Non-root

1. Add the docker group if it does not exist
```
$ sudo groupadd docker
```
2. Add the connected user $USER to the docker group
```
$ sudo gpasswd -a $USER docker
```
3. Restart the docker daemon
```
$ sudo service docker restart
$ sudo service docker stop
$ sudo service docker start
```

```
docker info
```
