# command-cheatsheet

####  May 18, 2020 
- Give firewall access to port 80 using cmd in CENTOS
```
firewall-cmd --permanent --add-port-80/tcp
```
- Check nginx.conf file you have written is okay
```
nginx -t -c {path to nginx.conf}
```
- Delete all `.DS_store` from specific folder 
```
find . -name '.DS_Store' -type f -delete
```
