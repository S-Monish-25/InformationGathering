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
<img width="1919" height="1079" alt="Screenshot 2026-01-30 234236" src="https://github.com/user-attachments/assets/b492d197-f3f8-4a8d-9c66-3cc822b467f1" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output
<img width="1211" height="463" alt="Screenshot 2026-01-31 01104222" src="https://github.com/user-attachments/assets/ab3603c3-7d08-40e5-aed9-e6f1ebb39ee5" />



## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="1919" height="1079" alt="Screenshot 2026-01-31 011236" src="https://github.com/user-attachments/assets/67038ba8-eb33-4bdf-bbdc-e021569944dd" />



## History of the website:
## output
https://web.archive.org/details/https://letterboxd.com/
<img width="1919" height="1054" alt="Screenshot 2026-01-31 011434" src="https://github.com/user-attachments/assets/875f191e-7e33-4802-af4d-458d1fad0158" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output
<img width="965" height="295" alt="Screenshot 2026-01-31 013621" src="https://github.com/user-attachments/assets/47d535f0-8440-4c8b-b212-0250dd0c5e30" />



## nmap:
## output
<img width="975" height="248" alt="image" src="https://github.com/user-attachments/assets/d95bbaef-ed63-4f28-a1a8-776c09a98376" />


## Whatweb
### output
<img width="1342" height="212" alt="image" src="https://github.com/user-attachments/assets/083829d6-9135-4afe-9f58-f0537099bfaa" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T letterboxd.com
## output
<img width="1258" height="354" alt="image" src="https://github.com/user-attachments/assets/96bad051-d5f9-4cdd-81c8-1ba3faa10cb0" />


## UDP Traceroute:
sudo traceroute -U letterboxd.com
## output
<img width="1235" height="545" alt="image" src="https://github.com/user-attachments/assets/a2a2db9a-010d-43c0-a7d0-76e33baa6ab1" />



## ICMP Traceroute:
sudo traceroute letterboxd.com
## output
<img width="1265" height="271" alt="Screenshot 2026-01-31 014536" src="https://github.com/user-attachments/assets/8f7553c5-78fc-4fd7-915e-5274f1c2c6ae" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
