# hosts
##ipv4
### Newest Version http://go.netsh.org/link/gethosts
##ipv6
###Newest Version http://go.netsh.org/link/getipv6hosts
---
####Win:ipconfig /flushdns
####Ubuntu:sudo /etc/init.d/networking restart 
####MAC: sudo dscacheutil -flushcache;sudo killall -HUP mDNSResponder;say DNS cache flushed
---
