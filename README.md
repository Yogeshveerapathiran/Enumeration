# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:YOGESH V S
Register no:212222040185
```
# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 
  
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
## site:

![image](https://github.com/user-attachments/assets/cb05407e-8e12-4e4a-af6e-d65679f2a908)



## filetype:
![image](https://github.com/user-attachments/assets/e8ed7c9c-7e39-49f6-b80e-aff46c0db26b)





## intext:
![image](https://github.com/user-attachments/assets/d73dfd70-8958-4e39-a2a6-2054de273da5)





## inurl:

![image](https://github.com/user-attachments/assets/26e5fcbf-5bc2-4bcf-8db4-d0da6c656c7d)



## intitle:
![image](https://github.com/user-attachments/assets/4f7e23ac-4e68-4349-a055-e3a50a4fb062)





## link:
![image](https://github.com/user-attachments/assets/8ffcea18-71e8-4101-a4c7-46f27f3c8eea)



## cache:
![image](https://github.com/user-attachments/assets/23a39aa9-0477-4d0f-a554-79bd76da5096)


## DNS Enumeration:
## DNS Recon:
![image](https://github.com/user-attachments/assets/7d724afe-5093-47e2-b840-31c5a235e765)


## dnsenum:
![image](https://github.com/user-attachments/assets/39e0374f-615d-4ae3-93e4-73477c519f60)
![image](https://github.com/user-attachments/assets/87f76f96-1b14-4a27-8e47-3823d1e2efc0)
![image](https://github.com/user-attachments/assets/69926af0-b738-4e3b-9e72-c06b59109d6d)


## smtp-user-enum:

![image](https://github.com/user-attachments/assets/45acfd32-1259-472e-9805-faa92dd6403b)
![image](https://github.com/user-attachments/assets/25a65f14-52da-466d-b712-d42816b7db87)


## telnet:
![image](https://github.com/user-attachments/assets/7faa6b44-fc22-4ace-b08b-1d60b845d832)


## nmap –script smtp-enum-users.nse :

![image](https://github.com/user-attachments/assets/9b986304-21b1-4397-b6be-c844ff3a4b04)



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

