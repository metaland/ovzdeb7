Auto Script Debian 7 KVM
=======
Deskripsi

Service
-------

OpenSSH port 22, 80, 143
Dropbear port 109, 110, 443
OpenVPN port TCP 1194 (client config – http://[ip]/client.tar)
Squid port 8080 (limit to IP VPS)
badvpn-udpgw port 7300

Fitur
-----

Webmin http(s)://[ip]:10000/
vnstat http://[ip]:81/vnstat/
MRTG http://[ip]:81/mrtg/
Timezone : Asia/Jakarta
Fail2Ban : [on]
IPv6 : [off]
Tools

axel
bmon
htop
iftop
mtr
nethogs

Script
------

screenfetch (https://github.com/KittyKatt/screenFetch)
ps_mem.py (https://github.com/pixelb/ps_mem/)
speedtest-cli (https://github.com/sivel/speedtest-cli)
bench-network.sh
user-login.sh
user-limit.sh (non aktif)
user-expired.sh
