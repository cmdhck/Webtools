# Webtools
This is a tool to convert web to ip and ip to web recode and update by @comradehacker 
To use one of the tools, you need either a domain / url or an IP list.
  
  If you have a domain / url list with the format :
  
  ```https://xxx.xxx/```
  
  Then use the ```formatter.py``` and format the domains. 
  
  Outcome = ```domains-formatted.txt```
  
  After the ```formatter.py``` start ```domain-ip.py``` and convert the domains to IPs.
  
  This tool requires a domain list, for example google.com, then it will get the IP and saves it to a text file

  
  #Installation

  <h3>Linux</h3>
  
  ```
  $ git clone https://github.com/rebl0x3r/iptools.git
  
  $ cd domain2ip

  $ chmod +x domain-ip.py
  $ chmod +x ip-domain.py
  ```
  To remove http and https via bash through ```sed```:
  ```
  $ sed -i 's/https\?:\/\///g' file.txt 
  $ python3 domain-ip.py
  $ python3 ip-domain.py
  ```
  Or just run :
  ```
  $ python3 formatter.py
   
  
  
