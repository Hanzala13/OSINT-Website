# OSINT Project
<img src="https://reconshell.com/wp-content/uploads/2021/11/osin-1024x467.png" width="750" height="380">

## Table of Contents
- Introduction
- Features
- Usage
- Project Structure
- OSINT tools
- License
- Contact
## Introduction
This OSINT project is designed to gather and analyze publicly available information from various online sources. The goal is to provide insights and intelligence that can be used for investigative purposes, research, or security assessments.

## Features
- Data Collection: Gather data from various open-source platforms such as social media, websites, and public records.
- Data Analysis: Analyze the collected data to uncover patterns, connections, and insights.
- Reporting: Generate detailed reports based on the analysis.
- Visualization: Visualize the data with charts, graphs, and network diagrams.

## Usage

For penetration testers and security teams, OSINT aims to reveal public information about internal assets and other information accessible outside the organization. Metadata accidentally published by your organization may contain sensitive information.

For example, useful information that can be revealed through OSINT includes open ports; unpatched software with known vulnerabilities; publicly available IT information such as device names, IP addresses and configurations; and other leaked information belonging to the organization.

Websites outside of your organization, especially social media, contain huge amounts of relevant information, especially information about employees. Vendors and partners may also be sharing specific details about an organization’s IT environment. When a company acquires other companies, their publicly available information becomes relevant as well.

## Project Structure
### OSINT Gathering Techniques
Here are three methods commonly used to gain open intelligence data.

- Passive Collection
  This is the most commonly used way to gather OSINT intelligence. It involves scraping publicly available websites, retrieving data from open APIs such as the Twitter API, or pulling data from deep web information sources. The data is then parsed and organized for consumption.

- Semi-Passive
  This type of collection requires more expertise. It directs traffic to a target server to obtain information about the server. Scanner traffic must be similar to normal Internet traffic to avoid detection.

- Active Collection
  This type of information collection interacts directly with a system to gather information about it. Active collection systems use advanced technologies to access open ports, and scan servers or web applications for vulnerabilities.

This type of data collection can be detected by the target and reveals the reconnaissance process. It leaves a trail in the target’s firewall, Intrusion Detection System (IDS), or Intrusion Prevention System (IPS). Social engineering attacks on targets are also considered a form of active intelligence gathering.

## OSINT tools
Here are some of the most popular OSINT tools

### Maltego
Maltego is part of the Kali Linux operating system, commonly used by network penetration testers and hackers. It is open source, but requires registration with Paterva, the solution vendor. Users can run a “machine”, a type of scripting mechanism, against a target, configuring it according to the information they want to collect.

### Main features include:

- Built-in data transformations.
- Ability to write custom transformations.
- Built-in footprints that can collect information from sources and create a visualization of data about a target.

### Spiderfoot
Spiderfoot is a free OSINT tool available on Github. It integrates with multiple data sources, and can be used to gather information about an organization including network addresses, contact details, and credentials.

### Main features include:

- Gathers and analyzes network data including IP addresses, classless inter-domain routing (CIDR) ranges, domains and subdomains.
- Gathers email addresses, phone numbers, and other contact details.
- Collects usernames for accounts operated by an organization.
- Collects Bitcoin addresses.

### Spyse
Spyse is an “Internet assets search engine”, designed for security professionals. It collects data from publicly available sources, analyzes them, and identifies security risks.

### Main features include:

- Collects data from websites, website owners, and the infrastructure they are running on
- Collects data from publicly exposed IoT devices
- Identifies connections between entities
- Reports on publicly exposed data that represents a security risk

### Intelligence X
Intelligence X is an archival service that preserves historical versions of web pages that were removed for legal reasons or due to content censorship. It preserves any type of content, no matter how dark or controversial. This includes not only data censored from the public Internet but also data from the dark web, wikileaks, government sites of nations known to engage in cyber attacks, and many other data leaks.

### Main features include:

- Search on email addresses or other contact details.
- Advanced search on domains and URLs.
- Search for IPs and CIDR ranges, with support for IPv4 and IPv6.
- Search for MAC addresses and IPFS Hashes.
- Search for financial data such as account numbers and credit card numbers
- Search for personally identifiable information
- Darknet: Tor and I2P
- Wikileaks & Cryptome
- Government sites of North Korea and Russia
- Public and Private Data Leaks
- Whois Data

### Dumpster: Everything else
- Public Web
- BuiltWith
BuiltWith maintains a large database of websites, which includes information on the technology stacks used by each site. You can combine BuiltWith with security scanners to identify specific vulnerabilities affecting a website.

### Main features include:

- Reporting on the content management system (CMS) in use by a website, its version, and plugins currently in use.
- Reporting on other infrastructure components used by a website, such as a CDN.
- Providing a list of JavaScript and CSS libraries used by the website.
- Providing information about the web server running the website.
- Providing details of analytics and tracking tools deployed by a website.

### Shodan
Shodan is a security monitoring solution that makes it possible to search the deep web and IoT networks. It makes it possible to discover any type of device connected to a network, including servers, smart electronics devices, and webcams.

Main features include:

- Easy to use search engine interface.
- Provides information on devices operating on protocols like HTTP, SSH, FTP, SNMP, Telnet, RTSP, and IMAP.
- Results can be filtered and ordered by protocol, network ports, region, and operating system.
- Access to a huge range of connected devices, including home appliances and public utilities such as traffic lights and water control systems.

### HaveIbeenPwned
HaveIbeenPwned is a service that can be used directly by consumers who were impacted by data breaches. It was developed by security researcher Troy Hunt.

### Main features include:

- Identifying if an individual email address was compromised in any historical breach.
- Checking accounts on popular services like LastFM, Kickstarter, WordPress.com, and LinkedIn for exposure to past data breaches.

### Google Dorking
Google dorking is not exactly a tool – it is a technique commonly used by security professionals and hackers to identify exposed private data or security vulnerabilities via the Google search engine.

Google has the world’s largest database of Internet content, and it provides a range of advanced search operators. Using these search operators it is possible to identify content that can be useful to attackers.

### Here are operators commonly used to perform Google Dorking:

- Filetype – enables finding exposed files with a file type that can be exploited
- Ext – similarly, finds exposed files with specific extensions that can be useful in attack (for example .log)
- Intitle/inurl – looks for sensitive information in a document title or URL. For example, any URL containing the term “admin” could be useful to an attacker.
- Quotes – the quote operator enables searching for a specific string. Attackers can search for a variety of strings that indicate common server issues or other vulnerabilities.

## License
This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.

## Contact
For any inquiries, please contact:

Name: Hanzala13

Email: hanzalaansari674@gmail.com

