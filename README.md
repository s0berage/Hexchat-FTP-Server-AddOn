# Hexchat-FTP-Server-AddOn
Hexchat-FTP-Server-AddOn - Working FTP/SFTP advertise script for hexchat written in python - tested on Windows 11 and Debian Linux 12! Its idea is to act as a FTP/SFTP Server script written in python for Hexchat IRC client, but working solely in python natively on the irc client, like MIRC Invision basically. Drop it in your addons folder for hexchat, close and reopen hexchat, and use the commands below:

works with /ftpserver set with the below commands:

**ip "127.0.0.1"**

**username "anonymous"** (free-form string, put whatever)

**password "anonymous"** (free-form string, put whatever)

**port "21"** (free-form string, put whatever)

**encryption "None"** (free-form string, put whatever)

**message "Welcome to FTP server!"** (free-form string, put whatever)

**message_interval 60000** (in ms, so 60000ms = 1 minute)

**line_delay 2** (in ms, so 60000ms = 1 minute)

**channels "#default_channel1,#default_channel2"** (free-form string, put whatever, seperate channels with a , and no space)

to start type **/ftpserver start**

to stop type **/ftpserver stop**

It's HIGHLY recommended to use a enterprise grade FTP/SFTP server software like Cerberus FTP Enterprise server 12.7.3+ with TLS 1.2 or higher, no SSL as it is deprecated. Use the below config methods:

Configuring FTP/SFTP properly:
------------------------------

https://support.cerberusftp.com/hc/en-us/articles/360000499020-Securing-Cerberus-FTP-Server-Best-Practices-for-Enhanced-Security

https://support.cerberusftp.com/hc/en-us/articles/360001686939-Security-Settings

https://en.wikipedia.org/wiki/Transport_Layer_Security#History_and_development

https://aws.amazon.com/compare/the-difference-between-ssl-and-tls/

Dynamic DNS providers:
----------------------

www.noip.com

https://account.dyn.com/

https://www.cloudflare.com/learning/dns/glossary/dynamic-dns/

