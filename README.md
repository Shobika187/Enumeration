# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

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

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/27433fae-f4df-4d9c-bd8d-3952ed2ce9f4)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/c82498d0-59b1-4919-9e08-bc6d3258e1d0)



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/cedf80f4-607e-4623-b68e-b9cebd4ad56a)


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/b87f5125-303e-4f9b-b5d1-272fbf3c61b4)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/61fb2577-c77c-4099-b375-ee1ad7285034)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/7a8ddfda-c253-4bbb-8618-6bdf1983d6cc)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 ### Output
 ![image](https://github.com/Shobika187/Enumeration/assets/94508142/8b85cebd-4111-4786-816b-d33977f3da2a)

## DNS Enumeration


### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![image](https://github.com/Shobika187/Enumeration/assets/94508142/7f36a31a-05ba-4361-9f05-513f610bf9ed)
![image](https://github.com/Shobika187/Enumeration/assets/94508142/74ddc486-7306-47fe-9745-e71216fc88bb)











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
### Output
![image](https://github.com/Shobika187/Enumeration/assets/94508142/0ed23145-13d3-4b72-a317-4856a6f648d0)


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

![image](https://github.com/Shobika187/Enumeration/assets/94508142/7a42e561-3626-4aec-8fd5-4a076e934ab7)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
![image](https://github.com/Shobika187/Enumeration/assets/94508142/9e82fce8-8e06-4578-8362-8f80fc26b9f4)

select any username in the first column of the above file and check the same
![image](https://github.com/Shobika187/Enumeration/assets/94508142/c9e70141-e0a2-438b-be60-e592abc9d965)


## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output
 ![image](https://github.com/Shobika187/Enumeration/assets/94508142/a8a242d1-3956-4321-9129-dc85832f1868)

  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![image](https://github.com/Shobika187/Enumeration/assets/94508142/1402716f-f5db-4dd7-917c-56d3d461e506)



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

