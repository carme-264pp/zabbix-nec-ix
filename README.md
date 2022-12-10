# zabbix-nec-ix

This repository is a zabbix template for monitoring NEC IX series routers with Zabbix.

For monitoring, SNMP settings are required on the IX router.

## composition

- nec-ix-environment.yaml  
  This template monitors CPU usage, memory usage, device temperature, and power supply voltage.

- nec-ix-sessions.yaml  
  This template monitors NAT session count, IPv4 and IPv6 session count.
