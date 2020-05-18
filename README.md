# command-cheatsheet

####  May 18, 2020 
- Give firewall access to port 80 using cmd in CENTOS
```
firewall-cmd --permanent --add-port-80/tcp
```
- check nginx.conf file you have written is okay
```
nginx -t -c {path to nginx.conf}
```
