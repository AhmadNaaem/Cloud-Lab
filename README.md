# Cloud-Lab
Lab 11


Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.14.5-1.msi -OutFile $env:tmp\wazuh-agent; msiexec.exe /i $env:tmp\wazuh-agent /q WAZUH_MANAGER='172.20.40.1' WAZUH_AGENT_NAME='ANS-Laptop' 
