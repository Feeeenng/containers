

# nfs v4 server
this is nfs server for v4

# origin containers 
https://hub.docker.com/r/gists/nfs-server


# run 
```
docker-compose up -d
```

# use
```
mount -v -t nfs -o vers=4,port=2049 192.168.4.132:/ /share
```
