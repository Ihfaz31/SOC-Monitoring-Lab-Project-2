# Project 2: SOC-Monitoring-Lab

## Description
This project is designed to analyze the purpose of SEIM tool with Wazuh to know the purpose of the system. It demonstrate wazuh manager running on ubuntu, agent kali linux is active in the wazuh dashboard or not, login alert, ssh failed login report, system auth alert and a final alert of the dashboard in wazuh SEIM tool

## Features
- Wazuh manager running on ubuntu: This is the 1st step of making ubuntu as the defender and using it to form wazuh SEIM tool.
- Agent connected to Wazuh: Here kali is used as an agent to use as an attacking medium and on ubuntu it is showing whether kali agent is active or not
- Log alert: With kali linus, we have used it to login so that log alert can be seen on wazuh dashboard alert system
- ssh failed login: These prompt helps to know whether any multiple failed login is happening or not and to notify the observer
- system auth alert: With these one can identify whether wazuh is collecting logs, the SEIM is parsing authentication events and alerts are being generated and indexed

## Installation
These whole lab project is done on a oracle virtualbox with all virtual os
