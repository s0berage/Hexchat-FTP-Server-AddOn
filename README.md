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
