## 0x01 信息收集

```shell
Nmap scan report for 10.10.10.114
Host is up (0.0071s latency).
Not shown: 65528 closed ports
PORT     STATE    SERVICE      VERSION
80/tcp   open     http         Boa HTTPd 0.94.14rc21
| http-methods: 
|_  Supported Methods: GET HEAD POST
|_http-server-header: Boa/0.94.14rc21
|_http-title: Site doesn't have a title (text/html).
135/tcp  filtered msrpc
137/tcp  filtered netbios-ns
138/tcp  filtered netbios-dgm
139/tcp  filtered netbios-ssn
445/tcp  filtered microsoft-ds
5038/tcp open     asterisk     Asterisk Call Manager 1.1

NSE: Script Post-scanning.
Initiating NSE at 23:19
Completed NSE at 23:19, 0.00s elapsed
Initiating NSE at 23:19
Completed NSE at 23:19, 0.00s elapsed
Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 28.89 seconds
           Raw packets sent: 66128 (2.910MB) | Rcvd: 66085 (2.643MB)
```

