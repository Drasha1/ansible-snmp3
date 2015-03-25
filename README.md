Overview
-------------------
Very simple setup for snmp3 for centos tested on 5, 6, and 7.

Requirements
--------------------
- Centos
- firewall allowing outgoing snmpd tcp on port 161
- firewall allowing in coming tcp to snmpd on port 199

Ansible Variables
--------------------
- snmp3user=testuser       || must be set for a host for this role to work
- snmp3password=testpasswd || must be set for a host for this role to work
