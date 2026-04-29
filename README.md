<img width="622" height="428" alt="Screenshot 2026-04-29 132636" src="https://github.com/user-attachments/assets/8cf41a5d-1746-4e92-b5d0-b6fdc9eafd7a" /># InformationGathering
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


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="622" height="428" alt="Screenshot 2026-04-29 132636" src="https://github.com/user-attachments/assets/119f5d22-0d46-4bd4-8fa3-350ceeaa19f3" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1916" height="1010" alt="Screenshot 2026-04-29 095240" src="https://github.com/user-attachments/assets/c4c69f82-0965-4963-b08a-31e5d33eb04d" />



## History of the website:
## output
https://web.archive.org/

<img width="1919" height="1144" alt="Screenshot 2026-04-29 093439" src="https://github.com/user-attachments/assets/0b4503a5-4d18-419c-bc0b-1d325fe30a70" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com



## nmap:
###output

<img width="622" height="342" alt="Screenshot 2026-04-29 133446" src="https://github.com/user-attachments/assets/d8d50273-0a16-4efc-b014-d6ee6a85f5ec" />

## Whatweb
### output

<img width="631" height="240" alt="Screenshot 2026-04-29 133723" src="https://github.com/user-attachments/assets/ebebab12-45ab-4699-be95-91233dca0907" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

<img width="645" height="357" alt="Screenshot 2026-04-29 133613" src="https://github.com/user-attachments/assets/195cb149-67a9-4ce1-8d87-42f18259e4a9" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="628" height="408" alt="Screenshot 2026-04-29 134033" src="https://github.com/user-attachments/assets/fc6a4b75-edd2-499d-a232-7eb0bf95c5c3" />


## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
