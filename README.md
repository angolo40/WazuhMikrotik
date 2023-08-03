# WazuhMikrotik
Script for monitoring Wireguard peers login/logout and send data to wazuh syslog server


## Steps
- Configure Wazuh manager to receive Syslog messages:
https://wazuh.com/blog/how-to-configure-rsyslog-client-to-send-events-to-wazuh/

- Copy 1001-mikrotik_decoders.xml in /var/ossec/etc/decoders/1001-mikrotik_decoders.xml
- Copy local_rules.xml in /var/ossec/etc/rules/local_rules.xml
- Restart Wazuh
- Configure Mikrotik to send logs to syslog server (Wazuh)
- Create script on mikrotik to monitoring wireguard peers activity and schedule it for running every 30sec

## Author

👤 **Giuseppe Trifilio**

* Website: https://github.com/angolo40/WazuhMikrotik
* Github: [@angolo40](https://github.com/angolo40)
  
## 🤝 Contributing

- Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/angolo40/mikrocata2selks).
## Show your support

- Give a ⭐️ if this project helped you!
- BTC: bc1qga68pwf49sfhdd9nj96m8e2s65ypjegtx8lafj
- BNB: 0x720b2b3e4436ec7064d54598BAd113e5293fF691
***
