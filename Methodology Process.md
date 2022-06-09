## 1. Reconaissance
	###Passive Reconaissance (OSINT)
☐ Lookup WHOIS Record
☐ Lookup DNS A records
☐ Lookup DNS MX records at DNS Server
☐ Lookup DNS TXT records
☐ Lookup DNS A records
☐ Lookup DNS MX records at DNS Server
☐ Lookup DNS TXT Records
☐ Check DNSdumpster.com (secret servers)
☐ Check Shodan.io

### Active Reconaissance

####Network Scanning

☐  nmap -sn 10.11.1.*
☐  nmap -sL 10.11.1.*
☐  nbtscan -r 10.11.1.0/24
☐  smbtree

####Individual Host Scanning

☐  nmap  --top-ports 20 --open -iL iplist.txt
☐  nmap -sS -A -sV -O -p- ipaddress
☐  nmap -sU ipaddress
☐ nmap -Pn -n -vv --open -p- -T4 --host-timeout 201 --max-retries 0 --min-rate=1000 -T4 <scanme.nmap.org>

##2. Enumeration/Service Scanning

####WebApp
☐   Nikto
☐   dirb
☐   dirbuster
☐   wpscan
☐   dotdotpwn
☐   view source 
☐   davtest\cadevar
☐   droopscan
☐   joomscan
☐   LFI\RFI Test
  
####Linux\Windows
☐   snmpwalk -c public -v1 ipaddress 1
☐   smbclient -L //ipaddress
☐   showmount -e ipaddress port
☐   rpcinfo
☐   Enum4Linux
		
####Anything Else
☐   nmap scripts (locate *nse* | grep servicename)
☐   hydra
☐   MSF Aux Modules
☐   Download the software

##3.Exploitation
☐   Gather Version Numbers
☐   Searchsploit
☐   Default Creds
☐   Creds Previously Gathered
☐   Download the software

##4.Post Exploitation

###Linux
☐   linux-local-enum.sh
☐   linuxprivchecker.py
☐   linux-exploit-suggestor.sh
☐   unix-privesc-check.py

###Windows
☐   wpc.exe
☐   windows-exploit-suggestor.py
☐   windows_privesc_check.py
☐  	windows-privesc-check2.exe

##5.Priv Escalation
☐  acesss internal services (portfwd)
☐  add account

###Windows
☐  List of exploits

###Linux
☐  sudo su 
☐  KernelDB
☐  Searchsploit

##6. Final/Covering Tracks
☐  Screenshot of IPConfig\WhoamI
☐  Copy proof.txt
☐  Dump hashes 
☐  Dump SSH Keys
☐  Delete files
   
##Citations
   
1. https://medium.com/@0xP/oscp-2022-tips-to-help-you-pass-dddd3563967e
2. https://oscpnotes.infosecsanyam.in/My_OSCP_Preparation_Notes--Scanning--Recon.html
3. https://guide.offsecnewbie.com/cherrytree-oscp-template#cherrytree
