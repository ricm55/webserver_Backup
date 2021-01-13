# This is my web server backup

I have a homemade server to experiment many projects like web 
development or hosting app that must run 24h/24. This repo is 
only a reminder for me to know what I did on my server and allow
me to keep a backup. 

My server is running: Ubuntu 20.04.1 LTS

## Config

### apache

This is my apache config file for my website

linux path:

```bash
/etc/apache2/sites-available/000-default.conf
```

### netplan

This file allow me to have static ip address at home. It's a lot easier
for me to connect with putty.

linux path:

```bash
 /etc/netplan/00-installer-config.yaml
```

note for me:
use crontab for automatic updates
