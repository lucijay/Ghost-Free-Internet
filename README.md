# ðð Installation

```
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/lizsvr/cfnfree/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

-------------------------------------------------------------------------------



# ðSSH Script [ Mod By ð§¿ â²â±§Ãâ´â® â¦Éâ®â©Ãâ±¤â­ âµâ±¤Éâ© ð§¿ ]

â¢ SSH & OpenVPN

â¢ SSH Websocket TLS & No TLS ( CloudFlare & CloudFront )

â¢ OHP SSH & OHP Dropbear & OHP OpenVPN

â¢ Backup Data ALL Service

â¢ Restore Data ALL Service

### Os Supported

â¢ Debian 10 Only

â¢ Ubuntu 18.04 & 20.04 (Recommended)

# Service & Port

â¢ OpenSSH                 : 443, 22

â¢ OpenVPN                 : TCP 1194, UDP 2200, SSL 990

â¢ Stunnel5                : 443, 445, 777

â¢ Dropbear                : 443, 109, 143

â¢ Squid Proxy             : 3128, 8080 (OFF)

â¢ Badvpn                  : 7100, 7200, 7300

â¢ Nginx                   : 89

â¢ Websocket TLS           : 443

â¢ Websocket None TLS      : 8880

â¢ Websocket Ovpn          : 2086

â¢ OHP SSH                 : 8181

â¢ OHP Dropbear            : 8282

â¢ OHP OpenVPN             : 8383

 ## ðServer Information & Other Features

â¢ Timezone                : Asia/Jakarta (GMT +7)

â¢ Fail2Ban                : [ON]

â¢ Dflate                  : [ON]

â¢ IPtables                : [ON]

â¢ Auto-Reboot             : [ON]

â¢ IPv6                    : [OFF]

â¢ Feature Delete Expired Account

â¢ Autoreboot On 05.00 GMT +7

-------------------------------------------------------------------------------

# ð¥ðð â²â±§Ãâ´â® â¦Éâ®â©Ãâ±¤â­ âµâ±¤Éâ© ððð¥

-------------------------------------------------------------------------------

# ð Credits

1. @lizsvr - Developer of ssh Manager

