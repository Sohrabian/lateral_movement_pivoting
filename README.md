# lateral_movement_pivoting
in summery by this repo we relize how dll injection works using Kiwi module in Powershell Empire ([this project is no longer supported](https://github.com/EmpireProject/Empire)) and mimikatz in Metasploit for credential steal.
### Install LAB 
The list of Vulen machines are using in this tutorial there are in [vulen-machine.txt](https://github.com/Sohrabian/letralmovment_poviting/blob/main/vulen-machines.txt).
1. Win-Server-2016
1. Exchange server 2019-CU1/MU these are RTM release (CVE-ecp-web-veiw-state) this post-exploitation module is Embedded using [RAPID-m7](https://www.rapid7.com/db/modules/exploit/windows/http/exchange_ecp_viewstate/).
2. Win-7
3. Win-10 
### Introduction
By those of tools I'm listing in this repo we can run tcp-reverse, credential steal on the other using Powershell Empire we generate agent for first pivoting then lateral movement in msfconsole. All machines are working on a Domain using DNS for more knowing how active directory is working like this scenario. The End of this Attack I try to forward These log to SPLUNK and ELK for more analysis, using HTTP/HTTPS Event collectore (HEC) or Splunk App Stream if I can show dll injection log using sysmon have received on splunk Enterprise as single instans/search head. 
### Config our machine as we want in this scenario
1. as soon as complete
