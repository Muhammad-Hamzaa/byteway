
# Byteway

The Byteway virtual machine (VM) is a tailored OSINT toolset designed for streamlined Open-Source Intelligence operations. Operating on Kali Linux, it features a curated set of pre-installed tools, browser extensions, and online resources. Byteway adopts a holistic OSINT strategy, merging both local and external tools for in-depth website analysis in investigative scenarios. To enhance its functionalities, supplementary tools are integrated, offering a comprehensive approach to website reconnaissance.
## Kali Linux Built-in Tools

### Nmap

#### Description:

Nmap, a powerful network scanning tool, enables users to discover hosts and services on a computer network. In Kali Linux, Nmap is a go-to utility for network reconnaissance, providing comprehensive insights into open ports, services, and system information. Effortlessly uncovering potential vulnerabilities, Nmap is an indispensable asset for security assessments and penetration testing.

#### Information Gathered:

- Nmap facilitates the discovery of active hosts and open ports on a network, providing a foundational understanding of its structure.
- The tool offers detailed information about services running on open ports, aiding in the identification of potential vulnerabilities.
- It supports various scan types, including SYN, UDP, and comprehensive scripting, allowing users to customize scans based on their specific reconnaissance needs.

#### Command to execute: 
nmap `<target domain>`, nmap `<target IP>`

#### Access Instructions:

Nmap comes pre-installed in Kali Linux, and you can utilize it through the terminal by executing the command "nmap" followed by the target IP or hostname. For instance, you can run "nmap target.com" to initiate a scan

### WHOIS Lookup

#### Description:

WHOIS Lookup serves as a valuable tool for querying domain registration databases, offering insights into a domain's ownership, registration date, and contact information. In Kali Linux, the tool is readily available, empowering users to gather essential details about domain entities seamlessly for investigative purposes.

#### Information Gathered:

- Domain registration details, including owner's name and contact information.
- Information about the domain registrar and registration and expiration dates.
- Name server details indicating the servers responsible for hosting the domain.

#### Command to execute: 
whois `<domain name>`

#### Access Instructions:

Open a terminal in Kali Linux.
Execute the whois command followed by the target domain or IP address.
## Other External Tools

### Sublist3r

#### Description:

Sublist3r is a versatile subdomain enumeration tool written in Python. It leverages multiple search engines to discover and enumerate subdomains associated with a target domain. Its ability to aggregate results from various sources makes it a valuable asset in reconnaissance and penetration testing, aiding security professionals in understanding the scope of a target's online presence.

#### Information Gathered:
- It identifies and lists subdomains related to the target domain, providing a comprehensive overview of its online footprint.
-  The tool associates discovered subdomains with their corresponding IP addresses, aiding in network mapping and analysis.
- Sublist3r leverages search engines to gather subdomains, utilizing their vast databases to enhance the accuracy and coverage of the enumeration process.

#### Command to execute: 
Sublist3r -d `<target domain>`

#### Access Instructions:

Open a terminal in your system. Execute the Sublist3r command, specifying the target domain with the -d option.

### Curl

#### Description:

Curl, short for "Client for URLs," is a command-line tool and library for transferring data with URLs. It supports a wide range of protocols, including HTTP, HTTPS, FTP, FTPS, SCP, SFTP, LDAP, and more. Curl's versatility and simplicity make it a powerful tool for making network requests, testing APIs, and performing various data transfer operations directly from the command line.

#### Information Gathered:
- It identifies and lists subdomains related to the target domain, providing a comprehensive overview of its online footprint.
-  The tool associates discovered subdomains with their corresponding IP addresses, aiding in network mapping and analysis.
- Sublist3r leverages search engines to gather subdomains, utilizing their vast databases to enhance the accuracy and coverage of the enumeration process.

#### Command to execute: 
curl -I  `<domain name>`

### theHarvester

#### Description:

theHarvester is a versatile OSINT tool designed for reconnaissance and information gathering. It facilitates the collection of data from diverse sources, including search engines, PGP key servers, and public resources. With a focus on email addresses, subdomains, and other essential information, theHarvester aids cybersecurity professionals and researchers in conducting comprehensive reconnaissance during investigations.

#### Information Gathered:
- Enumeration of email addresses associated with the target domain.
-  Identification of related subdomains for expanded reconnaissance.
- Retrieval of additional information from public sources and search engines to enhance OSINT efforts.

#### Command to execute: 
theHarvester -d `domain name` -l 500 -b `search engine name`

#### Access Instructions:

Open a terminal in your system. Execute theHarvester commands, specifying target details and options as needed.

### Spiderfoot

#### Description:

SpiderFoot is an open-source OSINT automation tool designed for reconnaissance and footprinting. It streamlines the process of collecting information from diverse sources, including DNS, WHOIS, social media, and more. With its modular architecture and extensive plugin support, SpiderFoot assists cybersecurity professionals, analysts, and researchers in efficiently mapping and analyzing a target's digital footprint during investigations.

#### Information Gathered:
- Comprehensive data from WHOIS and DNS records, aiding in domain intelligence.
-  Social media footprint, aggregating information from various platforms.
- Enumeration of network infrastructure and services, enhancing overall reconnaissance.

### haveibeenpwned.com 

#### Description:

Have I Been Pwned (HIBP) serves as a valuable resource for individuals and organizations to assess the security of their online accounts and take necessary actions to secure their digital presence. Users can input their email address to see if it appears in known breaches, enabling proactive measures against potential security threats. 

#### Information Gathered:
- Detection of compromised email addresses associated with data breaches.
- Notification of breached accounts to enhance user awareness.
- Integration with breached password lists, improving overall cybersecurity awareness.

### Leak-Lookup

#### Description:

Leak Lookup is an online cybersecurity tool designed to identify and notify users about potential data breaches. By searching through extensive databases, it detects compromised email addresses or usernames, providing timely alerts to enhance user awareness. Leak Lookup empowers individuals and organizations to assess and fortify their online security by identifying and addressing potential vulnerabilities associated with leaked credentials.

#### Information Gathered:
- Identification of leaked email addresses or usernames.
-  Alerts users about potential compromise in various data breaches.
- Aids in assessing and strengthening online security by identifying compromised credentials.


## Extensions

### Clearbit connect

#### Description:

Clearbit Connect is a web extension designed to enhance email communication by providing additional information about your contacts directly within your email interface. With Clearbit Connect, you can access enriched details about your email contacts, including company information, social profiles, and job titles. This extension streamlines the process of gathering insights about your contacts, helping you make more informed and context-aware communication decisions.

#### Information Gathered:

- Gather enriched details about email contacts, providing insights into their professional profiles.
- Access comprehensive information, including company details and social profiles, directly within your email interface
- Enhance communication by utilizing context-aware data from Clearbit Connect for more informed interactions.

### Shodan

#### Description:

Shodan functions as an internet-connected device search engine, enabling users to identify and investigate devices linked to the internet, such as servers, routers, webcams, and various others. Offering details about open ports, the services operating on those ports, and occasionally specific vulnerabilities, Shodan is a valuable tool extensively employed for security research and reconnaissance purposes.

#### Information Gathered:

- Uncover active ports and running services on the targeted server
- Retrieve information about connected devices, including their types and manufacturers.
- Identify potential vulnerabilities and misconfigurations during the assessment.
## Disclaimer

These tools are meant for educational purposes and lawful utilization exclusively. The creators and contributors disclaim any responsibility for misuse, harm, or legal repercussions resulting from the tool's use. Please exercise responsible usage.