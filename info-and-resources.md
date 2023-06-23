# Info\&Resources



&#x20;يرجى الملاحظة هذا ليس cheat sheet  ، وإنما  خريطة عامة قد لا تشمل بعض التفاصيل وذكرت الـTools وأهم Services مع بعض المصادر للتدرب مثل TryHackMe ,HackTheBox  وبعض الـMachines وروابط لمحتويات عربية ,ولا يعني أنه يجب عليكم تجربة المصادر كاملة  ، ولا يعني أيضا أنه لا يوجد أكثر من تحدي في  المنصات المذكورة  التي قد تساعدك في الممارسة فانصح بالبحث عن اسم الموضوع الذي تريد الممارسة فيه إن كنت تريد التدرب أكثر &#x20;

{% hint style="warning" %}
يوجد كثير من الأدوات وأداة تشبه أدةً أخرى ، تذكر أن في الاختبار ليس عليك استخدام جميعها ولا داعي للفزع ، استخدم ما تحتاجه
{% endhint %}

## Videos

* [https://www.youtube.com/@HackerSploit](https://www.youtube.com/@HackerSploit)
* [https://www.youtube.com/watch?v=qaNZKH5NohQ\&t=11291s](https://www.youtube.com/watch?v=qaNZKH5NohQ\&t=11291s)
* [https://www.youtube.com/watch?v=uThOnvh1zJw\&t=1850s](https://www.youtube.com/watch?v=uThOnvh1zJw\&t=1850s)



## TryHackMe&#x20;

<details>

<summary>Rooms </summary>

Useful Path&#x20;

* [https://tryhackme.com/paths](https://tryhackme.com/paths)(check command injection)

SQLmap:

&#x20;[https://tryhackme.com/room/sqlmap](https://tryhackme.com/room/sqlmap)

Rooms&#x20;

* [https://tryhackme.com/room/ice](https://tryhackme.com/room/ice)
* [https://tryhackme.com/room/blue](https://tryhackme.com/room/blue)
* [https://tryhackme.com/room/tomghost](https://tryhackme.com/room/tomghost)
* [https://tryhackme.com/room/gamezone](https://tryhackme.com/room/gamezone)
* [https://tryhackme.com/room/ra](https://tryhackme.com/room/ra)
* [https://tryhackme.com/room/anonymous](https://tryhackme.com/room/anonymous)





</details>

## HackTheBox&#x20;

<details>

<summary>rooms </summary>

*   ## Armageddon&#x20;

    my goal is to know what is Drupal&#x20;





</details>

## Machines&#x20;

* [https://www.vulnhub.com/entry/dc-1,292/](https://www.vulnhub.com/entry/dc-1,292/)
* Metasploitable 2 or Metasploitable 3&#x20;

## Wordlists

```
/usr/share/metasploit-framework/data/wordlists/unix_passwords.txt
/usr/share/metasploit-framework/data/wordlists/unix_users.txt
/usr/share/wordlists/metasploit/root_userpass.txt 
/usr/share/commix/src/txt/usernames.txt
/usr/share/wordlists/rockyou.txt
usr/share/metasploit-framework/data/wordlists/directory.txt
/usr/share/metasploit-framework/data/wordlists/sensitive_files.txt

```

## 1- Assessment Methodologies

{% tabs %}
{% tab title="Technology Lookup" %}
//this is an online tool or extension&#x20;

* BuiltWith
* Wapplyzer&#x20;
* Netcraft

#### Google Dorks

https://tryhackme.com/room/googledorking

google hacking database
{% endtab %}

{% tab title="commands" %}
```javascript
//Windows Recon 
Zenmap

// Linux commadns
fping
arp-scan
theHarvester //forEmails
dig 
dnsenum 
nslookup
whatweb 
HTTrack 
Whois 
dnsrecon  
dnsrecon 
Sublist3r
Masscan
Rustscan
Autorecon
wafw00f 


```
{% endtab %}
{% endtabs %}

## Labs in TryHAckme

[https://tryhackme.com/room/passiverecon](https://tryhackme.com/room/passiverecon)

[https://tryhackme.com/room/redteamrecon](https://tryhackme.com/room/redteamrecon)

[https://tryhackme.com/room/activerecon](https://tryhackme.com/room/activerecon)





## 2- Host & Network Penetration Testing

### Network-bead Attack Topics:&#x20;

`Wireshark`&#x20;

`Tshark`&#x20;

`Arp poisoning`

&#x20;`--` [`https://tryhackme.com/room/layer2`](https://tryhackme.com/room/layer2)

`--` [`https://www.javatpoint.com/arp-spoofing-using-arpspoof`](https://www.javatpoint.com/arp-spoofing-using-arpspoof)

`--` [`https://techyrick.com/arpspoof-full-tutorial/`](https://techyrick.com/arpspoof-full-tutorial/)

{% tabs %}
{% tab title="Summary of Important Services" %}


* SMB&#x20;
* Samba &#x20;
* FTP&#x20;
* SSH&#x20;
* HTTP
* MYSQL
* &#x20;SMTP
* &#x20;RDP
* apache PHP-CGI
* WordPress&#x20;
* Microsoft IIS
{% endtab %}

{% tab title="Summary of tool and commands" %}
```javascript
msfvenom 
searchsploit 
nmap 
Metasploit framework 
Netcat 
Hydra 
hashdump
John


smbmap 
smbclient

//webdav 
davtest
cadaver 
//winRM 
crackmapexec 
evil-winrm //getting shell 



 

```
{% endtab %}
{% endtabs %}

###

### Windows

<details>

<summary><strong>Frequently Exploited Windows Services</strong></summary>

* WebDAV&#x20;

<!---->

* WinRM

<!---->

* SMB With PsExec&#x20;

<!---->

* Windows MS17-010 SMB (EternalBlue)

<!---->

* Exploiting RDP

<!---->

* CVE-2019-0708 - BlueKeep

</details>



#### Windows Privilege Escalation

* [PrivescCheck](https://github.com/itm4n/PrivescCheck) - script aims to enumerate common Windows ( [example](https://attackdefense.com/challengedetailsnoauth?cid=2404))
* Bypassing UAC
* Token Impersonation With Incognito



&#x20;&#x20;

### Linux&#x20;

<details>

<summary><strong>Frequently Exploited Linux Services</strong></summary>



* Bash CVE-2014-6271 Vulnerability (Shellshock)-->PHP-cgi&#x20;

<!---->

* Exploiting SSH

<!---->

* Exploiting SAMBA

<!---->

* Exploiting FTP&#x20;

</details>



#### Linux Privilege Escalation

[LinEnum ](https://github.com/rebootuser/LinEnum)-  bash script to enum and  identify privilege escalation

* Linux Kernel Exploits
* Misconfigured Cron Jobs
* SUID Binaries
* Weak Permissions



## Dumping & Cracking

* Dumping & Cracking NTLM Hashes -->Windows
* Mimikatz
* Hashcat
* John The Ripper
* Pass-the-Hash attack: is a technique where an attacker captures a password hash



## Pivoting

* Port Forwarding: is like when you say (_I want you to redirect the traffic from the specific port on a Target system that you would like to compromise and I want you to forward the traffic to a local port on my system so that we can access that system_)

## Bind & Reverse Shells

* you should know how to do both.&#x20;

### Reverse shell

[cheatsheet](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md)

[reverse shell generator](https://www.revshells.com/)





## 3- Web&#x20;

### important Topics&#x20;

* HTTP Login using Hydra&#x20;
* SQL Injection
* XSS&#x20;

### Tools&#x20;

```javascript
// Softwares
Burp Suite 
ZAProxy
//commands  
Nikto 
Drib 
Gobuster
XSSer 
sqlmap
```















## &#x20;









