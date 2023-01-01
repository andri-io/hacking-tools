## Information Gathering
* [whois](https://www.tecmint.com/whois-command-get-domain-and-ip-address-information/)&nbsp;
``` 
whois google.com
whois 216.58.206.46
```
* [nbtscan](https://www.darknet.org.uk/2017/09/nbtscan-download-netbios-scanner-for-windows-linux/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/scallywag/nbtscan)&nbsp;&nbsp;
``` 
nbtstat -A 192.168.1.99
nbtscan -f addresses.txt
```
* [fping](https://fping.org/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://github.com/schweikert/fping)&nbsp;
``` 
fping 50.116.66.139 173.194.35.35 98.139.183.24
fping -s -g 192.168.0.1 192.168.0.9
fping -g -r 1 192.168.0.0/24
```
* [tcptraceroute](https://linux.die.net/man/1/tcptraceroute)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/mct/tcptraceroute)&nbsp;&nbsp;&nbsp;
``` 
tcptraceroute api.opendns.com 443
tcptraceroute -T domainname
```
* [traceroute](https://linux.die.net/man/8/traceroute)&nbsp;&nbsp;&nbsp;
``` 
traceroute example.com
```
* [xprobe2](https://linux.die.net/man/1/xprobe2)&nbsp;&nbsp;&nbsp;
``` 
xprobe2 google.com
xprobe2 -D 11 google.com
```
* [sslyze](https://tools.kali.org/information-gathering/sslyze)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/nabla-c0d3/sslyze)&nbsp;&nbsp;&nbsp;
``` 
sslyze --regular bugcrowd.com
```
* [tcpdump](https://opensource.com/article/18/10/introduction-tcpdump)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/the-tcpdump-group/tcpdump)&nbsp;&nbsp;&nbsp;
``` 
tcpdump host 1.1.1.1
tcpdump -i eth0
```
* [tshark](https://www.wireshark.org/docs/man-pages/tshark.html)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/wireshark/wireshark)&nbsp;
``` 
tshark -i wlan0 -w capture-output.pcap
tshark -r capture-output.pcap
```
* [wireshark](https://www.wireshark.org/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/wireshark/wireshark)&nbsp;
``` 
wireshark
```
* [subbrute](https://github.com/TheRook/subbrute)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/TheRook/subbrute)&nbsp;
``` 
./subbrute.py target.com
```
* [dnsenum](https://tools.kali.org/information-gathering/dnsenum)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dnsenum)&nbsp;
``` 
dnsenum --enum hackthissite.org
dnsenum hackthissite.org
```
* [dnsrecon](https://tools.kali.org/information-gathering/dnsrecon)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dnsrecon)&nbsp;
``` 
./dnsrecon.py -d <domain>
./dnsrecon.py -d <domain> -t axfr
```
* [dnstracer](https://tools.kali.org/information-gathering/dnstracer)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dnstracer)&nbsp;
``` 
dnstracer www.mavetju.org
```
* [enum4linux](https://tools.kali.org/information-gathering/enum4linux)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/enum4linux)&nbsp;
``` 
enum4linux -v 172.168.0.6
enum4linux -u 192.168.2.55
```
* [hping3](https://tools.kali.org/information-gathering/hping3)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/hping3)&nbsp;
``` 
hping3 -S 192.168.1.10 -p 80
hping3 –traceroute -S {target ip}
```
* [dotdotpwn](https://tools.kali.org/information-gathering/dotdotpwn)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dotdotpwn)&nbsp;
``` 
dotdotpwn.pl -m http -h 192.168.1.1 -M GET
```
* [golismero](https://tools.kali.org/information-gathering/golismero)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/golismero)&nbsp;
``` 
golismero scan http://www.0x00sec.org 
golismero scan http://www.0x00sec.org -o /root/scan.txt 
```
* [netmask](https://chousensha.github.io/blog/2017/07/07/netmask-kali-linux-tools/)&nbsp;&nbsp;
``` 
netmask -c google.com
netmask -r 192.168.217.0/24
```
* [knock](https://kalilinuxtutorials.com/knock-enumerate-subdomains/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/guelfoweb/knock)&nbsp;&nbsp;
```
knockpy domain.com
knockpy domain.com -w wordlist.txt
```
* [lbd](https://tools.kali.org/information-gathering/lbd)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](http://gitlab.com/kalilinux/packages/lbd)&nbsp;
``` 
lbd example.com
```
* [angryFuzzer](http://www.techtrick.in/description/3542-angryfuzzer-tool-for-information-gathering-on-kali-linux)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/ihebski/angryFuzzer)&nbsp;&nbsp;&nbsp; 
``` 
python angryFuzzer.py -u http://www.techtrick.in
```
* [miranda](https://tools.kali.org/information-gathering/miranda)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/miranda)&nbsp;&nbsp;&nbsp;
``` 
miranda -i eth0 -v
```
* [ncat](http://knoxd3.blogspot.com/2013/07/how-to-use-ncat-in-kali-linux.html)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/nmap/nmap/tree/master/ncat)&nbsp;&nbsp;&nbsp;
``` 
ncat 192.168.1.100 80
```
* [wafw00f](https://null-byte.wonderhowto.com/how-to/identify-web-application-firewalls-with-wafw00f-nmap-0198145/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/EnableSecurity/wafw00f)&nbsp;&nbsp;&nbsp; 
``` 
wafw00f https://equifaxsecurity2017.com
```
* [inforfinder](https://devhub.io/repos/ggusoft-inforfinder)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/ggusoft/inforfinder)&nbsp;&nbsp;&nbsp;
``` 
python inforfinder.py --help
```
* [masscan](https://tools.kali.org/information-gathering/masscan)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/masscan)&nbsp;&nbsp;&nbsp; 
```
masscan -p22,80,445 192.168.1.0/24
masscan 10.0.0.0/8 192.168.0.0/16 172.16.0.0/12 -p80
```
* [faraday](https://tools.kali.org/information-gathering/faraday)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/python-faraday)&nbsp;&nbsp;&nbsp; 
``` 
python-faraday -h
```
* [tlssled](https://tools.kali.org/information-gathering/tlssled)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/tlssled)&nbsp;&nbsp;&nbsp; 
``` 
tlssled 192.168.1.1 443
```
* [sslsplit](https://tools.kali.org/information-gathering/sslsplit)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/sslsplit)&nbsp;&nbsp;&nbsp; 
``` 
sslsplit -D -l connections.log -j /tmp/sslsplit/ -S /tmp/ -k ca.key -c ca.crt ssl 0.0.0.0 8443 tcp 0.0.0.0 8080
```
* [dmitry](https://tools.kali.org/information-gathering/dmitry)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dmitry)&nbsp;&nbsp;&nbsp; 
``` 
dmitry -winsepo example.txt example.com
dmitry -wise -o Comrade.txt scanme.nmap.org
```
* [urlcrazy](https://tools.kali.org/information-gathering/urlcrazy)&nbsp;&nbsp;&nbsp;
``` 
urlcrazy -k dvorak -r example.com
```
* admin-panel-finder &nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/bdblackhat/admin-panel-finder)&nbsp;&nbsp;&nbsp;

* [dnsmap](https://tools.kali.org/information-gathering/dnsmap)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/dnsmap)&nbsp;&nbsp;&nbsp; 
``` 
./dnsmap google.com
```
* [dnmap_client](#)&nbsp;&nbsp;&nbsp;
``` 
dnmap_client -s <server-ip> -a <alias></alias></server-ip>
```
* [dnswalk](https://tools.kali.org/information-gathering/dnswalk)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/davebarr/dnswalk)&nbsp;&nbsp;&nbsp; 
``` 
dnswalk -r -d example.com.
dnswalk example.com.
```
* [fierce](https://tools.kali.org/information-gathering/fierce)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/fierce)&nbsp;&nbsp;&nbsp;
``` 
fierce -dns example.com -threads 10
```
* [fragrouter](https://tools.kali.org/information-gathering/fragrouter)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/fragrouter)&nbsp;&nbsp;&nbsp;
``` 
fragrouter -i eth0 -F1
```
* ftest &nbsp;&nbsp;&nbsp;
``` 
./ftest -f ftest.conf
```
* [arping](https://kalilinuxtutorials.com/arping/)&nbsp;
``` 
arping  192.168.122.1
arping -s aa:bb:cc:dd:ee:ff  192.168.122.1
arping -c 2 192.168.122.1
```
* [cdpsnarf](https://tools.kali.org/information-gathering/cdpsnarf)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/cdpsnarf)&nbsp;&nbsp;&nbsp; 
``` 
cdpsnarf -i eth0 -w cdpsnarf.pcap
```
* [unicornscan](https://tools.kali.org/information-gathering/unicornscan)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/unicornscan)&nbsp;&nbsp;&nbsp; 
``` 
unicornscan -v -I -mT [IP ADDRESS]
unicornscan -mTsf -Iv -r 1000 192.168.0.102:a

```
* [nmap](https://tools.kali.org/information-gathering/nmap)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/nmap)&nbsp;&nbsp;&nbsp
``` 
nmap cloudflare.com
nmap --top-ports 20 192.168.1.106
nmap -oX output.xml securitytrails.com
```
* [theHarvester](https://tools.kali.org/information-gathering/theharvester)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/laramies/theHarvester)&nbsp;&nbsp;&nbsp; 
``` 
theHarvester -d sixthstartech.com -l 300 -b all
theHarvester.py -d wonderhowto.com -b all -l 200
```
* [twofi](https://tools.kali.org/information-gathering/twofi)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/digininja/twofi)&nbsp;&nbsp;&nbsp; 
``` 
twofi -h
```
* [maltego](https://www.maltego.com/?utm_source=paterva.com&utm_medium=referral&utm_campaign=301)&nbsp;

* [0trace](https://www.aldeid.com/wiki/0trace)&nbsp;
``` 
./0trace.sh wlan0 69.63.181.12
```
* [intrace](https://tools.kali.org/information-gathering/intrace)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/robertswiecki/intrace)&nbsp;&nbsp;&nbsp; 
``` 
intrace -h hostname.com -p port -s sizeofpacket
intrace -h www.example.com -p 80 -s 4
```
* irpas-ass &nbsp;&nbsp;&nbsp;

* irpas-cdp &nbsp;&nbsp;&nbsp;

* [netdiscover](https://kalilinuxtutorials.com/netdiscover-scan-live-hosts-network/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/netdiscover-scanner/netdiscover)&nbsp;&nbsp;&nbsp;
``` 
netdiscover -i eth0 -r 192.168.43.0/24
```
* [smbmap](https://tools.kali.org/information-gathering/smbmap)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/ShawnDEvans/smbmap)&nbsp;&nbsp;&nbsp; 
``` 
smbmap -u victim -p s3cr3t -H 192.168.86.61
smbmap -H 192.168.1.102
```
* [snmp-check](https://tools.kali.org/information-gathering/snmp-check)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/snmpcheck)&nbsp;&nbsp;&nbsp; 
``` 
snmp-check 192.168.1.2 -c public
```
* [swaks](https://installlion.com/kali/kali/main/s/swaks/install/index.html)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://github.com/jetmore/swaks)&nbsp;&nbsp;&nbsp; 
``` 
swaks --to user@example.com
swaks --to user@example.com --server smtp.example.com
```
* [gobsuter](https://github.com/OJ/gobuster)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://github.com/OJ/gobuster)&nbsp;&nbsp;&nbsp; 
``` 
gobuster dir -u https://buffered.io -w ~/wordlists/shortlist.txt
```

* [smtp-user-enum](https://tools.kali.org/information-gathering/smtp-user-enum)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/smtp-user-enum)&nbsp;&nbsp;&nbsp; 
``` 
smtp-user-enum -M VRFY -U /root/Desktop/user.txt -t 192.168.1.107
smtp-user-enum -M VRFY -u root -t 192.168.1.25
```
* [braa](https://tools.kali.org/information-gathering/braa)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/braa)&nbsp;&nbsp;&nbsp; 
``` 
braa 10.253.101.1-10.253.101.254:.1.3.6.1.2.1.1.6.0
braa public@192.168.1.215:.1.3.6.*
```

* [onesixtyone](https://null-byte.wonderhowto.com/how-to/hack-like-pro-crack-private-public-snmp-passwords-using-onesixtyone-0150332/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/trailofbits/onesixtyone)&nbsp;&nbsp;&nbsp;
``` 
onesixtyone -c dict.txt 192.168.1.119
```
* [ssldump](https://www.systutorials.com/docs/linux/man/1-ssldump/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/adulau/ssldump)&nbsp;&nbsp;&nbsp; 
``` 
ssldump -i le0 port 443
```
* [sslh](https://www.ostechnix.com/sslh-share-port-https-ssh/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/yrutschle/sslh)
``` 
ssh -p 443 sk@192.168.225.50
```
* [sslscan](https://chousensha.github.io/blog/2017/06/24/sslscan-kali-linux-tools/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/rbsec/sslscan)&nbsp;&nbsp;&nbsp; 
``` 
sslscan sail.co.in
sslscan https://www.cylance.com
```
* ike-scan &nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/royhills/ike-scan)&nbsp;&nbsp;&nbsp; 
``` 
ike-scan 192.168.49.2
```
* [legion](https://kalilinuxtutorials.com/legion-penetration-testing/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/carlospolop/legion)&nbsp;&nbsp;&nbsp; 

* [recon-ng](https://tools.kali.org/information-gathering/recon-ng)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/lanmaster53/recon-ng)&nbsp;&nbsp;&nbsp;
``` 
recon-ng
```
* [p0f](https://tools.kali.org/information-gathering/p0f)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/p0f/p0f)&nbsp;&nbsp;&nbsp; 
```
 
p0f -i eth0 -p -o /tmp/p0f.log
```
* [acccheck](https://www.kalitut.com/2016/01/acccheck-kali-tools.html)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/qashqao/acccheck)&nbsp;&nbsp;&nbsp; 
``` 
acccheck -t IP ADDRESS
acccheck -t 10.0.2.15 -U mynames.txt -P mypasswords.txt
```
* [THC-IPV6 Package](https://tools.kali.org/information-gathering/thc-ipv6)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/thc-ipv6)&nbsp;&nbsp;&nbsp;
```
address6
alive6
covert_send6
covert_send6d
denial6
detect-new-ip6
detect_sniffer6
dnsdict6
dnsrevenum6
dos-new-ip6
dump_router6
exploit6
.
.
.
.

```
* [casefile](https://tools.kali.org/information-gathering/casefile)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/casefile)&nbsp;&nbsp;&nbsp;
``` 
casefile
```
* [creepy](https://www.geocreepy.com/)&nbsp;

* [jigsaw](http://knoxd3.blogspot.com/2013/07/how-to-use-jigsaw-in-kali-linux.html)&nbsp;
``` 
jigsaw –s company name
```
* [metagoofil](https://tools.kali.org/information-gathering/metagoofil)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/metagoofil)&nbsp;&nbsp;&nbsp; 
``` 
metagoofil -d kali.org -t pdf -l 100 -n 25 -o kalipdf -f kalipdf.html
```

* [sslcaudit](https://tools.kali.org/information-gathering/sslcaudit)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/sslcaudit)&nbsp;&nbsp;&nbsp; 
``` 
sslcaudit -l 0.0.0.0:443 -v 1 
```
* [stunnel4](http://man.he.net/man8/stunnel4)
``` 
stunnel4
```

* [tcpflow](https://kalilinuxtutorials.com/tcpflow/)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/simsong/tcpflow)&nbsp;&nbsp;&nbsp; 
``` 
tcpflow -ce host 192.168.0.100
```
* [ace-voip](https://tools.kali.org/information-gathering/ace-voip)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/ace-voip)&nbsp;&nbsp;&nbsp; 
``` 
ace -i eth0 -m 00:1E:F7:28:9C:8e
ace -r eth0.96
```

* [Amap](https://tools.kali.org/information-gathering/amap)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/vanhauser-thc/THC-Archive/tree/master/Tools)&nbsp;&nbsp;&nbsp;
``` 
amap -bqv 192.168.1.15 80
```
* [APT2](https://tools.kali.org/information-gathering/apt2)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/apt2)&nbsp;&nbsp;&nbsp; 
``` 
apt2 -h
```

* [bing-ip2hosts](https://tools.kali.org/information-gathering/bing-ip2hosts)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/bing-ip2hosts)&nbsp;&nbsp;&nbsp;
``` 
bing-ip2hosts -p microsoft.com
bing-ip2hosts -p 173.194.33.80
```
* [automater](https://tools.kali.org/information-gathering/automater)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/automater)&nbsp;&nbsp;&nbsp; 
``` 
automater 185.62.190.110
automater corefitness.info
automater b9318a66fa7f50f2f3ecaca02a96268ad2c63db7554ea3acbde43bf517328d06
```

* [cisco-torch](https://tools.kali.org/information-gathering/cisco-torch)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/foreni-packages/cisco-torch)&nbsp;&nbsp;&nbsp; 
``` 
cisco-torch -A 10.1.1.0/24
```
* [enumIAX](https://tools.kali.org/information-gathering/enumiax)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/enumiax)&nbsp;&nbsp;&nbsp; [
``` 
enumiax -d /usr/share/wordlists/metasploit/unix_users.txt 192.168.1.1
```

* [EyeWitness](https://tools.kali.org/information-gathering/eyewitness)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/FortyNorthSecurity/EyeWitness)&nbsp;&nbsp;&nbsp; 
``` 
eyewitness -f /root/urls.txt -d screens --headless
```
* [goofile](https://tools.kali.org/information-gathering/goofile)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/goofile)&nbsp;&nbsp;&nbsp; 
``` 
goofile -d kali.org -f pdf
```

* [ident-user-enum](https://tools.kali.org/information-gathering/ident-user-enum)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/ident-user-enum)&nbsp;&nbsp;&nbsp;
``` 
ident-user-enum 192.168.1.13 22 139 445
```
* [inSpy](https://tools.kali.org/information-gathering/inspy)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/leapsecurity/InSpy)&nbsp;&nbsp;&nbsp; 
``` 
inspy -h
```

* [iSMTP](https://tools.kali.org/information-gathering/ismtp)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/ismtp)
``` 
ismtp
```

* [Nikto](https://tools.kali.org/information-gathering/nikto)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://gitlab.com/kalilinux/packages/nikto)&nbsp;&nbsp;&nbsp;
 
``` 
nikto -Help
```
* [ntop](https://tools.kali.org/information-gathering/ntop)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/gitlab.png?token=AKLVDP5MB6RCSXS423WWIA26WYYWM)](https://github.com/ntop/ntopng)
``` 
ntop -B "src host 192.168.1.1"
```

* [Parsero](https://tools.kali.org/information-gathering/parsero)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/behindthefirewalls/Parsero)&nbsp;&nbsp;&nbsp; 
``` 
parsero -u www.bing.com -sb
```
* [OSRFramework](https://tools.kali.org/information-gathering/osrframework)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/i3visio/osrframework)&nbsp;&nbsp;&nbsp;
``` 
usufy.py -h
mailfy.py -h
searchfy.py -h
domainfy.py -h
phonefy.py -h
entify.py -h
osrfconsole.py
```
* [sublist3r](https://tools.kali.org/information-gathering/sublist3r)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/aboul3la/Sublist3r)&nbsp;&nbsp;&nbsp;
``` 
sublist3r -d kali.org -t 3 -e bing
sublist3r -d google.com -b -t 100
```
* [ffuf]()&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/ffuf/ffuf)&nbsp;&nbsp;&nbsp; 
``` 
ffuf -w /path/to/wordlist -u https://target/FUZZ
````

* [Amass]()&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/OWASP/Amass)&nbsp;&nbsp;&nbsp; 
``` 
amass enum -d example.com
````

* [AQUATONE]()&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/michenriksen/aquatone)&nbsp;&nbsp;&nbsp; 
``` 
 cat targets.txt | aquatone
````
* [netscanner](https://github.com/R4yGM/netscanner)&nbsp;&nbsp;&nbsp;[![](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/R4yGM/netscanner)
``` 
netscanner sp tcp 127.0.0.1 80
```
* [webshag](https://github.com/wereallfeds/webshag)&nbsp;&nbsp;&nbsp;
``` 
sudo apt-get install python-wxgtk2.8 git nmap
git clone https://github.com/wereallfeds/webshag
cd webshag/
./setup.linux.py
./webshag_gui.py
```
* [PimEyes](https://pimeyes.com/en)&nbsp;&nbsp;&nbsp;

* [TinEye](https://tineye.com/)&nbsp;&nbsp;&nbsp;

* [OSINT Framework](https://osintframework.com/)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/lockfale/osint-framework)&nbsp;&nbsp;&nbsp;

* [Depix](https://www.linkedin.com/pulse/recovering-passwords-from-pixelized-screenshots-sipke-mellema/)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/beurtschipper/Depix)&nbsp;&nbsp;&nbsp;
```
git clone https://github.com/beurtschipper/Depix.git
cd Depix

python -m pip install -r requirements.txt

python depix.py -p /path/to/your/input/image.png -s images/searchimages/debruinseq_notepad_Windows10_closeAndSpaced.png -o /path/to/your/output.png
```
* [Osintgram](https://github.com/Datalux/Osintgram)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/Datalux/Osintgram)&nbsp;&nbsp;&nbsp;
```
python3 main.py <target username> --command <command>
```
* [Sherlock](https://null-byte.wonderhowto.com/how-to/hunt-down-social-media-accounts-by-usernames-with-sherlock-0196138/)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/sherlock-project/sherlock)&nbsp;&nbsp;&nbsp;
```
# clone the repo
$ git clone https://github.com/sherlock-project/sherlock.git

# change the working directory to sherlock
$ cd sherlock

# install the requirements
$ python3 -m pip install -r requirements.txt

# search user name
python3 sherlock [user_name]
```
* [PhoneInfoga](https://null-byte.wonderhowto.com/how-to/find-identifying-information-from-phone-number-using-osint-tools-0195472/)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/sundowndev/phoneinfoga)&nbsp;&nbsp;&nbsp;

* [GHunt](https://kalilinuxtutorials.com/ghunt/)&nbsp;&nbsp;&nbsp;[![github](https://raw.githubusercontent.com/hhhrrrttt222111/Ethical-Hacking-Tools/master/0/github.png?token=AKLVDP4M2RTUFTJVE5QLRV26WYYCE)](https://github.com/mxrch/GHunt)