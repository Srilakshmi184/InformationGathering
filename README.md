# InformationGathering
Information Gathering Techiques
# NAME-SRILAKSHMI BH
# REG.NO-212224100035

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

## OUTPUT

<img width="1912" height="1131" alt="Screenshot 2026-04-29 093220" src="https://github.com/user-attachments/assets/39b46b33-7054-4bb1-a34d-d8d27403b37d" />

This image shows the domain details of edurussia.ru from WHOIS.
It includes registration date, expiry date, and name servers.
The domain is registered and verified under a Russian registrar.

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="622" height="428" alt="Screenshot 2026-04-29 132636" src="https://github.com/user-attachments/assets/119f5d22-0d46-4bd4-8fa3-350ceeaa19f3" />

This shows the ping results to the domain from a Kali Linux terminal.
It confirms that the server is active and responding to requests.
The response times vary, showing network latency between systems.

## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1916" height="1010" alt="Screenshot 2026-04-29 095240" src="https://github.com/user-attachments/assets/c4c69f82-0965-4963-b08a-31e5d33eb04d" />

This image shows the geolocation details of the IP address.
The server is located in Russia, specifically in Rostov-na-Donu.
It also indicates the use of a data center and DDoS protection service.


## History of the website:
## output
https://web.archive.org/

<img width="1919" height="1144" alt="Screenshot 2026-04-29 093439" src="https://github.com/user-attachments/assets/0b4503a5-4d18-419c-bc0b-1d325fe30a70" />

This shows archived records of the website from the Wayback Machine.
It displays how many times the site was saved and the types of files captured.
Most of the content is in HTML format, indicating regular web pages.

# Webserver Fingerprinting:

## nmap:
###output

<img width="622" height="342" alt="Screenshot 2026-04-29 133446" src="https://github.com/user-attachments/assets/d8d50273-0a16-4efc-b014-d6ee6a85f5ec" />

This is an Nmap network scan performed on the domain edurussia.ru using a Kali Linux terminal. The output lists several open ports, including 21 (FTP), 22 (SSH), and standard web ports like 80 and 443, indicating the services currently reachable on that server.

## Whatweb
### output

<img width="631" height="240" alt="Screenshot 2026-04-29 133723" src="https://github.com/user-attachments/assets/ebebab12-45ab-4699-be95-91233dca0907" />

This image shows the output of the WhatWeb tool, which identifies the various technologies powering the website edurussia.ru. It reveals that the site uses the Bitrix Site Manager CMS, runs on an nginx web server, and includes components like jQuery and Google Tag Manager.

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

<img width="645" height="357" alt="Screenshot 2026-04-29 133613" src="https://github.com/user-attachments/assets/195cb149-67a9-4ce1-8d87-42f18259e4a9" />

This image shows a traceroute command being run in Kali Linux to map the path data takes to reach edurussia.ru. The output displays the initial hop, but the subsequent asterisks indicate that the intermediate routers are likely blocking ICMP packets or timed out.

## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="628" height="408" alt="Screenshot 2026-04-29 134033" src="https://github.com/user-attachments/assets/fc6a4b75-edd2-499d-a232-7eb0bf95c5c3" />

This image shows a traceroute command using the -U flag, which specifically instructs the tool to use UDP packets for probing the network path. Despite switching protocols, the results remain the same: the intermediate routers are blocking the requests, leading to the repeated timeouts seen as asterisks.

## ICMP Traceroute:
sudo traceroute  www.google.com


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
