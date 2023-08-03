# WazuhMikrotik
Script for monitoring Wireguard peers login/logout and send data to wazuh syslog server


1 - Configure Wazuh manager to receive Syslog messages:
https://wazuh.com/blog/how-to-configure-rsyslog-client-to-send-events-to-wazuh/

2 - Copy 1001-mikrotik_decoders.xml in /var/ossec/etc/decoders/1001-mikrotik_decoders.xml
3 - Copy local_rules.xml in /var/ossec/etc/rules/local_rules.xml
4 - Restart Wazuh
5 - Configure Mikrotik to send logs to syslog server (Wazuh)
6 - Create script on mikrotik to monitoring wireguard peers activity and schedule it for running every 30sec

