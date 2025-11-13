# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:

![img](image/a.png)



Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## OUTPUT:

![img](image/pingfacebook.png)

Finding Hosting Company
get further detail by using ip2location.com website.

## OUTPUT:

![img](image/ip2location.png)

History of the website:

## OUTPUT:

![img](image/facebooksummary.png)


## Webserver Fingerprinting:
## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

## OUTPUT:

![img](image/sudoncexample.png)
 
## nmap:
```
nmap -p 21 -sV --script=banner ftp.nluug.nl
```
## OUTPUT:

![img](<image/nmap p 21 sV scriptbannerftpnluugnl.png>)

## Whatweb

## OUTPUT:

![img](image/whatwebgoogle.png)

![img](image/metasploit2.png)

## httprint
```
httprint  -h 192.168.43.133 -s /usr/share/httprint/signatures.txt -P0 |more

```
## OUTPUT:

![img](image/httprint.png)

## Tracing the Location

TCP Traceroute:
```
sudo traceroute -T www.google.com
```

## OUTPUT:

![img](image/sudotraceroute.png)

UDP Traceroute:
```
sudo traceroute -U www.google.com
```

## OUTPUT:

![img](<image/sudo traceroute Uwwwgooglecom.png>)


ICMP Traceroute:
```
sudo traceroute  www.google.com
```

## OUTPUT:

![img](<image/sudo traceroute  wwwgooglecom.png>)

## OUTPUT:


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
