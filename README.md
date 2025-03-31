# Webtools
This is a tool to convert web to ip and ip to web with auto filter dead ip or domain.. recode and update by @comradehacker 
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
  $ git clone https://github.com/cmdhck/Webtools
  
  $ cd Webtools

  $ chmod +x domain-ip.py
  $ chmod +x ip-domain.py
  Or just run :
  $ python3 formatter.py
  $ python3 ip-domain.py
  $ python3 domain-ip.py
   ```
  For Termux and kali users
  
  <h3>Termux</h3>
  
```

git clone https://github.com/cmdhck/Webtools

cd Webtools
```
For converting bulk or single ips to domain kindly run

```python ip-domain.py```

For converting bulk or single domain to ips kindly run
```python domain-ip.py```

For removing or http or https from single or bulk domain kindly run
```python formatter.py```
