#   CTF Challanges
##  17th June,2023
##  Challange:  BSides Indore CTF

>   Walkthrough
>   By Shaswata Saha
>   Kali-Linux
>   shaswata.ssaha@gmail.com
>   Github: https://github.com/subhro1530/BSides-Indore-CTF-June-17.git

[Link to Challange](http://ctf.bsidesindore.in/challenges)

#   1.  WEB

Machine: http://34.29.242.60:1111/
IP  :   34.29.242.60:1111

##  Nmap Scan:
```bash
# Nmap 7.92 scan initiated Fri Jun 16 22:48:39 2023 as: nmap -oN nmap.txt -oC -sC -Pn 34.29.242.60
Nmap scan report for 60.242.29.34.bc.googleusercontent.com (34.29.242.60)
Host is up (0.35s latency).
Not shown: 997 filtered tcp ports (no-response)
PORT     STATE SERVICE
22/tcp   open  ssh
| ssh-hostkey: 
|   3072 6f:3b:43:e2:fd:86:56:21:fb:35:7e:cc:b1:ff:f0:81 (RSA)
|   256 e9:fe:53:8d:55:cc:1a:fb:ce:1b:6b:0d:a0:02:7a:9f (ECDSA)
|_  256 5a:57:dd:80:f3:8a:8b:fe:8b:97:e2:3e:6f:61:e1:f7 (ED25519)
1111/tcp open  lmsocialserver
2222/tcp open  EtherNetIP-1
|_ssh-hostkey: ERROR: Script execution failed (use -d to debug)

# Nmap done at Fri Jun 16 22:50:15 2023 -- 1 IP address (1 host up) scanned in 96.42 seconds

```
