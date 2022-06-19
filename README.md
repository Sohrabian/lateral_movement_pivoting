# letralmovment and poviting
in summery by this repo we relize how dll injection works using Kiwi module in Powershell Empire this project is no longer supported or mimikatz in Metasploit for credential steal.
### Install LAB 
The list of Vulen machines are using in this tutorial there are in [vulen-machine.txt](https://github.com/Sohrabian/letralmovment_poviting/blob/main/vulen-machines.txt).
1. Win-Server-2016
1. Exchange server 2019-CU1/MU these are RTM release (CVE-ecp-web-veiw-state) this post-exploitation module is Embedded using [RAPID-m7](https://www.rapid7.com/db/modules/exploit/windows/http/exchange_ecp_viewstate/).
2. Win-7
3. Win-10 
### Introduction
By those of tools I'm listing in this repo we can run tcp-reverse, credential steal on the other using Powershell Empire we generate agent for first pivoting then lateral movement using msfconsole in kali linux. All machines are working on a Domain using DNS for more knowing how active directory is working like this scenario. 
