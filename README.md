# weberp
Weberp 4.15 Blind SQL Injection Exploit


Original Exploit: https://www.exploit-db.com/exploits/47013

**Description:**

This exploit is a port to python3. The exploit simply confirms Blind SQL Injection. You may need to modify to recon the number of databases and start revealing the names of each database. I suggest you start with ID 0 and work your way up to confirm Blind sqli. 

**General Usage**

```
python3 47013.py 192.168.162.227 "weberp/" admin weberp 0
```
