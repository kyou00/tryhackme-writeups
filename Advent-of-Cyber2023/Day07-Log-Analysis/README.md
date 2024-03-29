# Advent of Cyber 2023

[Day 7] Log analysis ‘Tis the season for log chopping!

-------------------------------------


- How many unique IP addresses are connected to the proxy server?
	- `9`

```
cut -d ' ' -f2 access.log | sort | uniq -c
```

- How many unique domains were accessed by all workstations?
	- `111`

```
cut -d ' ' -f3 access.log | cut -d ':' -f1 | sort | uniq -c > try.txt
wc try.txt
```

- What status code is generated by the HTTP requests to the least accessed domain?
	- `503`

```
grep "partnerservices.getmicrosoftkey.com" access.log | cut -d ' ' -f6 | sort | uniq -c 
```

- Based on the high count of connection attempts, what is the name of the suspicious domain?
	- `frostlings.bigbadstash.thm`

```	
cut -d ' ' -f3 access.log | cut -d ':' -f1 | sort | uniq -c | sort -n | tail -n 10
```

- What is the source IP of the workstation that accessed the malicious domain?
	- `10.10.185.225`


```
grep "frostlings.bigbadstash.thm" access.log | cut -d ' ' -f2 | sort | uniq -c | sort -n
```

- How many requests were made on the malicious domain in total?
	- `1581`
```
grep "frostlings.bigbadstash.thm" access.log | cut -d ' ' -f2 | sort | uniq -c | sort -n
```

- Having retrieved the exfiltrated data, what is the hidden flag?
	- `THM`

```	
grep "frostlings.bigbadstash.thm" access.log | cut -d ' ' -f5 | cut -d '=' -f2 | base64 -d | grep "THM"
```