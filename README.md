
# Byteway

The Byteway virtual machine (VM) is a custom OSINT toolset built for efficient Open-Source Intelligence activities. Hosted on Kali Linux, it offers a collection of pre-installed tools, Firefox extensions, and online resources. Byteway ensures a comprehensive OSINT approach, combining local and external tools for effective website analysis during investigations. To elevate its capabilities, Byteway incorporates supplementary tools, providing an all-encompassing approach to website reconnaissance.
## Kali Linux Built-in Tools

### Nmap

#### Description:

Nmap, a powerful network scanning tool, enables users to discover hosts and services on a computer network. In Kali Linux, Nmap is a go-to utility for network reconnaissance, providing comprehensive insights into open ports, services, and system information. Effortlessly uncovering potential vulnerabilities, Nmap is an indispensable asset for security assessments and penetration testing.

#### Information Gathered:

- Bullet Point 1
- Bullet Point 2
- Bullet Point 3

#### Command to execute: 
nmap `<target domain>`, nmap `<target IP>`

#### Access Instructions:

Nmap comes pre-installed in Kali Linux, and you can utilize it through the terminal by executing the command "nmap" followed by the target IP or hostname. For instance, you can run "nmap target.com" to initiate a scan
## Other External Tools

### Sublist3r

#### Description:

Sublist3r is a versatile subdomain enumeration tool written in Python. It leverages multiple search engines to discover and enumerate subdomains associated with a target domain. Its ability to aggregate results from various sources makes it a valuable asset in reconnaissance and penetration testing, aiding security professionals in understanding the scope of a target's online presence.

#### Information Gathered:
- It identifies and lists subdomains related to the target domain, providing a comprehensive overview of its online footprint.
-  The tool associates discovered subdomains with their corresponding IP addresses, aiding in network mapping and analysis.
- Sublist3r leverages search engines to gather subdomains, utilizing their vast databases to enhance the accuracy and coverage of the enumeration process.


### WHOIS Lookup

#### Description:

WHOIS Lookup serves as a valuable tool for querying domain registration databases, offering insights into a domain's ownership, registration date, and contact information. In Kali Linux, the tool is readily available, empowering users to gather essential details about domain entities seamlessly for investigative purposes.


### haveibeenpwned.com 

#### Description:

Have I Been Pwned (HIBP) serves as a valuable resource for individuals and organizations to assess the security of their online accounts and take necessary actions to secure their digital presence. Users can input their email address to see if it appears in known breaches, enabling proactive measures against potential security threats. 

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