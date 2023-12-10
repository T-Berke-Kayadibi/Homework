# Network Security Strategies and Applications

## 1- Network Security Applications and Tools:

    Network security applications are critical for securing network and preventing threats to the system and network. It aids in network monitoring and data security. I'll continue with mentioning those applications one by one as:

#### 1. Wireshark

    Wireshark is a network packet analyzer. A network packet analyzer presents captured packet data in as much detail as possible. it is free and open-source, this makes it available for more user and allow more people to recognize this tools capabilities.

Key features of this app:

- *Capture* live packet data from a network interface.
- *Open* files containing packet data captured with tcpdump/WinDump, Wireshark, and many other packet capture programs.
- *Import* packets from text files containing hex dumps of packet data.
- Display packets with *very detailed protocol information*.
- *Save* packet data captured.
- *Export* some or all packets in a number of capture file formats.
- *Filter packets* on many criteria.
- *Search* for packets on many criteria.
- *Colorize* packet display based on filters.
- Create various *statistics*

Interface of **Wireshark** is given below.

![ws main](https://www.wireshark.org/docs/wsug_html_chunked/images/ws-main.png)

**Figure 1.1. Wireshark captures packets and lets you examine their contents.**

#### 2- Aircrack-ng

Aircrack-ng is a complete suite of tools to assess WiFi network security, It focuses on different areas of WiFi security:

- Monitoring: Packet capture and export of data to text files for further processing by third party tools
- Attacking: Replay attacks, deauthentication, fake access points and others via packet injection
- Testing: Checking WiFi cards and driver capabilities (capture and injection)
- Cracking: WEP and WPA PSK (WPA 1 and 2).

It is also another very functional tool with capabilities given below:

* Packet capture: Save captured traffic to files for offline analysis or further processing with other tools.

* WEP/WPA/WPA2-PSK cracking: Crack weak passwords used in WEP, WPA, and WPA2-PSK networks.

* WLAN card management: Manage the settings of your wireless network card, including putting it into monitor mode.

* Extensive protocol support: Supports a wide range of wireless network protocols, including 802.11a, 802.11b, 802.11g, 802.11n, and 802.11ac.

* Command-line interface: Provides a powerful and flexible command-line interface for advanced users.

* Script support: Can be used with scripts for automating tasks.

Since it works on terminal rather than GUI, the image for this apps interface is little bit hard to share.

#### 3- Snort

Another app for analyzing and understanding network is snort. Snort is the foremost Open Source Intrusion Prevention System (IPS) in the world. Snort IPS uses a series of rules that help define malicious network activity and uses those rules to find packets that match against them and generates alerts for users.

Snort can be deployed inline to stop these packets, as well. Snort has three primary uses: As a packet sniffer like tcpdump, as a packet logger — which is useful for network traffic debugging, or it can be used as a full-blown network intrusion prevention system. Snort can be downloaded and configured for personal and business use alike.

Snort screenshot view given below.

![](https://3.bp.blogspot.com/-9_L1M1xjRgQ/Wfx0Cdj9VII/AAAAAAAAACE/gz65mHDadZ0r2MphWT0xfxnD7yPc8o9MACEwYBhgL/s1600/Screen%2BShot%2B2017-11-03%2Bat%2B9.49.37%2BAM.png)

#### 4- pfSense

    The pfSense project is a free and open-source network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. pfSense software, with the help of the package system, is able to provide the same functionality or more of common commercial firewalls, without any of the artificial limitations. It's a powerful and versatile tool used by individuals, businesses, and organizations of all sizes to manage their networks and ensure security.

**Key features of pfSense:**

1- Advanced Firewall:

* Stateful packet inspection for deep traffic analysis and control.

* Flexible rules and policies for granular network access control.

* Support for various protocols and services, including VPNs, DHCP, DNS, and more.

* Intrusion Detection/Prevention (IDS/IPS) for advanced threat protection.

* Captive portal for guest access and network management.

2- High Availability and Redundancy:

* CARP (Common Address Redundancy Protocol) for automatic failover in case of hardware or software failure.

* Multi-WAN support for load balancing and failover across multiple internet connections.

* Snapshot and restore functionality for quick recovery from configuration errors or incidents.

3- Open-Source and Community Driven:

* Free and open-source software with a large and active community.

* Regular updates and security patches ensure long-term stability and reliability.

* Extensive documentation and tutorials available online.

* Flexible platform for customization and development.

4- Hardware Compatibility:

* Runs on a wide range of hardware platforms, including x86, ARM, and PowerPC.

* Can be installed on bare-metal systems or virtualized environments.

* Supports various network adapters and devices.

5- Easy to Use and Manage:

* Web-based graphical user interface for easy configuration and management.

* Package manager for installing and managing additional features.

* Command-line interface for advanced users.



App interface in dark mode.

![pfSense - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/3/38/Dashboard_der_pfSense_2.6.0.jpg)

#### 5- OpenVAS

    OpenVAS, a free and open-source vulnerability scanner, identifies security weaknesses in computers and networks. Its large database of over 95,000 test plugins allows scanning for vulnerabilities in diverse systems and applications across various protocols like TCP, UDP, HTTP, and FTP. This flexible tool scans single systems, networks, or entire organizations, targeting specific or all vulnerabilities affecting a particular system or application. 

**Key features of OpenVAS:**

* Vulnerability scanning: OpenVAS can scan for vulnerabilities in a wide range of systems and applications, including operating systems, web applications, and databases.

* Flexibility: OpenVAS can be used in a variety of ways, including scanning for vulnerabilities on a single system, a network of systems, or even an entire organization.

* Compliance: OpenVAS can help you to meet compliance requirements, such as those imposed by regulations such as PCI DSS and HIPAA.

App interface is given below.

![In the dashboard for the result of vulnerability scans, Greenbone Community Edition also allows interactive filtering via scan reports of detected vulnerabilities, here sorted by vulnerability severity.](https://www.bsi.bund.de/SharedDocs/Bilder/EN/BSI/Themen/OpenVAS/openvas_interaktives_filtern-bei-Scanberichten.jpg?__blob=normal&v=4)

### A- The importance of basic security applications such as firewalls, IDS/IPS, and antivirus software.

Basic security applications such as firewalls, intrusion detection and prevention systems (IDS/IPS), and antivirus software are critical in protecting your systems and networks from an constantly evolving threat landscape. They serve as multiple layers of protection, providing a comprehensive approach to cybersecurity.

#### Firewalls:

    A firewall<sup> 25</sup> is a blockade between a secure internal network and an untrusted network such as the Internet. Firewalls have been a first line of defense in network security. A firewall<sup> 26</sup> can be hardware, software, software-as-a service (SaaS), public cloud, or private cloud (virtual).

* Act as the first line of defense, filtering incoming and outgoing traffic based on predefined rules and policies.

* Block unauthorized access to your network and prevent malicious actors from infiltrating your systems.

* Control access to specific applications and services, minimizing the risk of data breaches and unauthorized activity.

##### **Hardware**

    Firewall hardware typically consists of a separate computer or device dedicated to running the firewall software functions.

##### **Software**

Firewall software provides a variety of applications. In terms of network security, a firewall provides these security controls through a variety of technologies:

* Internet Protocol (IP) packet filtering

* Network address translation (NAT) services

* SOCKS server

* Proxy servers for a variety of services such as HTTP, Telnet, FTP, and so forth

* Mail relay services

* Split Domain Name System (DNS)

* Logging

* Real-time monitoring

#### Intrusion Detection and Prevention (IDS/IPS)

    Intrusion Detection Systems (IDS) and Intrusion Prevention Systems (IPS) are two essential security tools that work in tandem with firewalls to protect networks from malicious activity. They offer an additional layer of defense against unauthorized access, data breaches, and other cyber threats.

##### Intrusion Detection System (IDS):

* Monitors network traffic for suspicious activity: analyzes traffic patterns and compares them to known attack signatures.

* Alerts administrators to potential threats: sends notifications when it detects suspicious activity, allowing for investigation and response.

* Passive defense: primarily detects and identifies threats, but does not actively prevent them.

##### Intrusion Prevention System (IPS):

* Extends the capabilities of an IDS: not only detects suspicious traffic but also takes action to block it.

* Proactive defense: can automatically drop malicious packets, close ports, or block traffic from suspicious IP addresses.

* Real-time protection: acts immediately after detecting threats, mitigating their potential impact before they can cause damage.

Together, IDS and IPS provide a comprehensive network security solution by enhanced security: since combining detection and prevention, they offer a stronger defense against various attacks. Improved threat response: IDS alerts allow for timely investigation and mitigation, while IPS provides automatic defense against immediate threats. Reduced downtime: Proactively blocking attacks minimizes the risk of network disruptions and data breaches.

![](https://purplesec.us/wp-content/uploads/2019/11/Intrusion-Detection-IDS-VS-Intrusion-Prevention-IPS-What%E2%80%99s-The-Difference.png)

### B- The use and importance of cryptography and encryption tools.

    Cryptography and encryption<sup> 27</sup> tools play a fundamental role in securing information and communication in the modern digital world. They provide a critical layer of protection for data confidentiality, integrity, and authenticity, ensuring that information remains safe from unauthorized access, manipulation, and forgery.

![Common Uses of Cryptography](https://www.fortinet.com/content/fortinet-com/en_us/resources/cyberglossary/what-is-cryptography/_jcr_content/par/c05_container_copy_c/par/c28_image_copy_copy.img.jpg/1614781468034.jpg)

## 2- Network Security Strategies:

### **Introduction**

    Network security is the process of preventing unwanted access, use, disclosure, disruption, modification, or destruction of computer networks and the data contained within them. Network security strategies are the plans and actions that businesses or individuals take to secure their networks.

### **A- Importance of Physical, Software, and Network Security Strategies**

    Network security is very important for businesses and individuals. If a network is not secure, it can be a target for malicious actions such as stealing important data, disrupting/destruction operations, cause financial losses and more. So, there are three important layers of strategies to prevent or at least reduce this risk to be occur as physical, software and network security strategies.

#### a. Physical Security:

    Physical security is the process of preventing unauthorized access, use, disclosure, disruption, alteration, or destruction of your physical assets and information. It consists of a number of procedures and controls designed to protect the physical integrity of your property, equipment, and data.

* **Controls physical access to network components:** This includes servers, routers, switches, and other critical infrastructure.

* Maintaining separate storage facilities with appropriate access restrictions and environmental precautions to protect sensitive equipment and data.

* **Restricted access points:** Implementing access control systems, such as key cards, biometric scanners, or security guards, to limit entry to authorized personnel only.

    These are all counter measures to prevents unauthorized physical access that could compromise hardware or steal sensitive data.

#### b. Software Security:

    The processes and strategies used to secure software applications and systems against malicious assaults, vulnerabilities, and unauthorized access. It covers a wide range of solutions for securing software throughout its development lifetime, from design and coding to deployment and maintenance. This can be achieved in many ways:

* **Secure coding practices:** To reduce vulnerabilities in software code, developers should follow secure coding principles such as input validation, error handling, and memory management.

* **Vulnerability scanning and penetration testing:** Scanning your software for vulnerabilities and doing penetration tests on a regular basis to detect and patch flaws before bad actors exploit them.

* Implementing a specific S-ALCM framework to integrate security considerations into every stage of the software development process is known as secure application lifecycle management (S-ALCM)<sup> 1-2</sup>.

* **Application security controls:** Deploying firewalls, intrusion detection and prevention systems (IDS/IPS), and other security controls to protect your software applications from external threats.

* Application whitelisting: Limiting the execution of authorized applications only, preventing the installation and running of potentially malicious software.
  
  The Council on CyberSecurity Critical Security Controls<sup> 3</sup> list provides very little detail on specific measures we can implement in software. 
  
  1. Patching
  2. Implement a Web Application Firewall (WAF)
  3. Error checking all input
  4. Use an automated scanner to look for security weaknesses
  5. Output sanitization of error messages
  6. Segregation development and production environments
  7. Secure code analysis, manual and automated
  8. Verify vendor security processes
  9. Database configuration hardening
  10. Train developers on writing secure code
  11. Remove development artifacts from production code
  
  Of these 11, it is interesting to note that two relate to infrastructure architecture, four are operational, two are part of testing processes, and only three are things that are done as part of coding.

Overall, Software security is critical for safeguarding your firm against a variety of risks, including:

* Data breaches<sup> 4</sup>: Malicious actors can exploit software vulnerabilities to gain access to sensitive data, leading to data breaches and reputational damage.

* Malware infections<sup> 5</sup>: Viruses, worms, and other malware can exploit software vulnerabilities to infect your systems, steal data, disrupt operations, and cause significant financial losses.

* Denial-of-service (DoS) attacks<sup> 6</sup>: Attackers can exploit vulnerabilities to overwhelm your software applications with traffic, making them unavailable to legitimate users.

* Intellectual property theft<sup> 7-8</sup>: Cybercriminals can steal valuable intellectual property buried within your software, causing serious financial and competitive loss.

#### c. Network Security:

    The techniques and technology used to secure computer networks from unwanted access, use, disclosure, disruption, alteration, or destruction of data are referred to as network security. It refers to a set of safeguards and controls applied at the network layer to ensure the integrity, confidentiality, and availability of data flowing via the network. Network security implementation involves various technical controls, including:

* Firewalls: Filtering incoming and outgoing network traffic based on predefined rules and access controls, preventing unauthorized access to your network resources.

* Intrusion detection and prevention systems (IDS/IPS): Monitoring network traffic for suspicious activity and automatically blocking potential threats before they can cause harm.

* VPNs (Virtual Private Networks)<sup> 9-10</sup>: Creating secure tunnels for encrypted data transmission over public networks, ensuring confidentiality and privacy of information.

* Network segmentation: Dividing your network into logical segments to limit the impact of a security breach and isolate critical resources.

* Access control lists (ACLs)<sup> 11-12</sup>: Defining specific rules to control and restrict access to network resources based on user identity, role, and device type.

* Data encryption: Encrypting data in transit and at rest to protect against unauthorized access even if intercepted.

* Network monitoring and logging: Continuously monitoring network activity and logging events for security analysis and incident investigation.

* Security awareness and training: Educating users about network security best practices and potential threats, such as phishing attacks and social engineering tactics.

### **Overall:**

    The importance of physical, software, and network security strategies cannot be exaggerated. These three security pillars are intertwined and work together to defend your organization or individual network against a constantly evolving landscape of cyber threats.

* Physical security safeguards your physical assets, including hardware, data storage devices, and personnel. Robust access controls, surveillance systems, and perimeter security are fundamental to deterring physical intrusion attempts and protecting sensitive information stored on physical devices.

* Software security focuses on securing the software applications and systems that drive your organization's operations. Secure coding practices, vulnerability management, application whitelisting, and regular security audits are essential to prevent malicious actors from exploiting software vulnerabilities and compromising your data and systems.

* Network security shields your network infrastructure and the data flowing through it. Firewalls, IDS/IPS<sup> 13-14</sup>, VPNs, and network segmentation play crucial roles in controlling network access, preventing unauthorized traffic, and ensuring data confidentiality and integrity.

These three security domains are not isolated entities. They are interconnected and rely on each other to form a holistic security posture. A weakness in one area leaves your organization vulnerable to attacks that can exploit interconnected vulnerabilities and compromise your entire security ecosystem.

### **B- Strategic Approaches to Data Security and Confidentiality**

    In today's digital landscape, data holds immense significance for organizations, serving as a cornerstone of their operations. Safeguarding the security and confidentiality of this invaluable asset is of utmost importance. 

    This section dives into strategic methodologies aimed at ensuring data security and upholding confidentiality. It dives deeply into critical elements such as data categorization, controlling access, encryption techniques, creating backups, disaster recovery plans, preventing data leaks, training employees, and managing incidents. Employing these strategies enables organizations to protect their sensitive data and reduce the likelihood of breaches and unauthorized access.

#### a. Data Classification and Access Control:

    Data classification<sup> 15-17</sup> is the process of categorizing data based on its sensitivity and importance. This helps organizations prioritize their security efforts and allocate resources effectively.

    Access control<sup> 15-17</sup>prevents unauthorized access, reduces data losses, and enhances data integrity, thus ensuring the security and reliability of organization's data.

Together, data classification and access control play a crucial role in protecting sensitive data and maintaining confidentiality. Methods can be summarized as:

* Classifies data based on its sensitivity and assigns appropriate access controls.

* Implements the principle of least privilege, granting users only the access they need to perform their job duties.

* Enforces strong password policies and multi-factor authentication for access control.

#### b. Data Encryption:

Data encryption is the process of transforming data into an unreadable format using a mathematical algorithm and a key. This encrypted data, also known as ciphertext, can only be decrypted back into its original form, or plaintext, with the correct key.

* Encrypts sensitive data at rest and in transit to prevent unauthorized access even if intercepted. Two ways of doing this are Asymmetric encryption methods<sup> 18</sup> and Symmetric encryption methods<sup> 18</sup>.

* Utilizes strong encryption algorithms and regularly updates encryption keys to maintain security.

* Encryption at the file, database and application levels for on-premise and cloud data

#### c. Data Backups and Disaster Recovery:

Data backups are copies of critical data stored in a separate location, typically offsite. These backups serve as a safety net in case of data loss due to hardware failures, cyberattacks, natural disasters, or other unforeseen events.

* Regularly backs up critical data to ensure availability in case of a security incident or system failure.

* Implements a disaster recovery plan to restore operations quickly and minimize disruption.

* Tests the disaster recovery plan regularly to ensure its effectiveness.

#### d. Data Leakage Prevention (DLP):

Data loss prevention (DLP)<sup> 19</sup> refers to the strategies, processes, and technologies cybersecurity teams use to protect sensitive data from theft, loss, and misuse. 

    Data leakage<sup> 19</sup> is the accidental exposure of sensitive data or confidential information to the public. Data exfiltration<sup> 19</sup> is actual data theft—when an attacker moves or copies someone else’s data to a device under the attacker’s control.

* Implements DLP solutions to prevent sensitive data from being exfiltrated from the network.

* Monitors network activity for suspicious data transfers and blocks unauthorized attempts.

* Provides data loss prevention training and awareness programs for employees.

#### e. Employee Security Awareness and Training:

* Educates employees about cybersecurity threats, best practices, and reporting procedures.

* Provides training on phishing awareness, social engineering tactics, and password security.

* Regularly tests and reinforces security awareness knowledge through training programs.

#### f. Security Incident and Event Management (SIEM):

SIEM<sup> 20</sup>, or security information and event management, is a security solution that assists organizations in identifying and addressing potential security threats and vulnerabilities before they disrupt business operations. SIEM systems assist enterprise security teams in detecting anomalous user behavior and using artificial intelligence (AI) to automate many of the manual processes associated with threat detection and incident response.

* Implements a SIEM solution<sup> 21-22</sup> to collect and analyze security logs (Log Management<sup> 21</sup>) and events from various sources.

* Enables real-time monitoring and detection of security incidents.

* Facilitates incident response and investigation to minimize damage and prevent future occurrences.

By implementing these strategic approaches and maintaining a layered security strategy, organizations can significantly enhance their data security and confidentiality posture.

### Conclusion

    Both physical, software, and network security strategies are essential for protecting an organization's critical assets and information. These strategies work together to create a layered defense against cyber threats, ensuring the confidentiality, integrity, and availability of data.

    In addition to these fundamental security measures, implementing strategic approaches to data security and confidentiality further strengthens the organization's security posture. Data classification<sup> 23</sup>, access control<sup> 24</sup>, encryption<sup> 18</sup>, data backups and disaster recovery, data leakage prevention<sup> 19</sup>, security awareness training, and Security Information and Event Management (SIEM)<sup> 20-22</sup> play crucial roles in securing sensitive data and minimizing the risk of breaches and unauthorized access.

    By proactively implementing these strategies and fostering a culture of security awareness within the organization, businesses can safeguard their data, mitigate cyber risks, and build trust with their stakeholders. Ultimately, prioritizing data security and confidentiality is not just a technical challenge, but a strategic imperative for ensuring long-term success in today's digital world.

## References

1. Schuman, Charles & Brent, Alan. (2005). Asset life cycle management: Towards improving physical asset performance in the process industry. International Journal of Operations & Production Management. 25. 566-579. 10.1108/01443570510599728. 

2. Tittel, E., & Brush, K. (2022, April 25). application lifecycle management (ALM). Software Quality. https://www.techtarget.com/searchsoftwarequality/definition/application-lifecycle-management-ALM

3. Controls | OWASP Foundation. (n.d.). https://owasp.org/www-community/controls/

4. *Cost of a data breach 2023 | IBM*. (n.d.). https://www.ibm.com/reports/data-breach#:~:text=The%20global%20average%20cost%20of,15%25%20increase%20over%203%20years.&text=51%25%20of%20organizations%20are%20planning,threat%20detection%20and%20response%20tools.

5. *The 18 CIS controls*. (2021, October 28). CIS. https://www.cisecurity.org/controls/cis-controls-list

6. Yoachimik, O. (2023, October 31). *DDoS threat report for 2023 Q3*. The Cloudflare Blog. https://blog.cloudflare.com/ddos-threat-report-2023-q3/

7. *Special report: EU intellectual property rights*. (n.d.). https://op.europa.eu/webpub/eca/special-reports/intellectual-property-rights-06-2022/en/

8. *Commission releases its Report on Intellectual Property Rights in Third Countries*. (2023, May 17). Trade. https://policy.trade.ec.europa.eu/news/commission-releases-its-report-intellectual-property-rights-third-countries-2023-05-17_en

9. *What is VPN? How It Works, Types of VPN*. (2023, July 31). www.kaspersky.com. https://www.kaspersky.com/resource-center/definitions/what-is-a-vpn

10. *What is a virtual private network (VPN)?* (2023, May 24). Cisco. https://www.cisco.com/c/en/us/products/security/vpn-endpoint-security-clients/what-is-vpn.html

11. *IBM documentation*. (n.d.). https://www.ibm.com/docs/en/i/7.5?topic=security-access-control-lists

12. *What is a Network Access Control List (ACL)? | Fortinet*. (n.d.). Fortinet. https://www.fortinet.com/resources/cyberglossary/network-access-control-list

13. *Cisco Learning Network*. (n.d.). https://learningnetwork.cisco.com/s/question/0D53i00000KsuxDCAR/cisco-idsips-fundamentals

14. *What is an intrusion prevention system (IPS)? | IBM*. (n.d.). https://www.ibm.com/topics/intrusion-prevention-system

15. *Data Classification and Protection Standards | Information Technology | Michigan Tech*. (n.d.). Michigan Technological University. https://www.mtu.edu/it/security/policies-procedures-guidelines/information-security-program/data-classification-protection-standards/

16. Data classification - security pillar - docs.aws.amazon.com. (n.d.). https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/data-classification.html

17. X. Sun and X. Xie, "Access Control Policy Management Based on Data Classification and Hierarchy," 2023 IEEE 3rd International Conference on Information Technology, Big Data and Artificial Intelligence (ICIBA), Chongqing, China, 2023, pp. 1141-1144, doi: 10.1109/ICIBA56860.2023.10165185.

18. *What is encryption? Data encryption defined  | IBM*. (n.d.). https://www.ibm.com/topics/encryption#:~:text=Data%20encryption%20is%20a%20way,Protecting%20your%20data

19. *What is data loss prevention (DLP)? | IBM*. (n.d.). https://www.ibm.com/topics/data-loss-prevention

20. *What is Security Information and Event Management (SIEM)? | IBM*. (n.d.). https://www.ibm.com/topics/siem

21. *What is Security Information and Event Management (SIEM)? | IBM*. (n.d.-b). https://www.ibm.com/id-en/topics/siem

22. *What is SIEM? | Microsoft Security*. (n.d.). https://www.microsoft.com/en-us/security/business/security-101/what-is-siem

23. Martinekuan. (2022, December 1). *What is data classification? - Cloud Adoption Framework*. Microsoft Learn. https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/govern/policy-compliance/data-classification

24. *What is access control? - Network cybersecurity systems*. (n.d.). Fortinet. https://www.fortinet.com/resources/cyberglossary/access-control#:~:text=Access%20control%20is%20a%20data,levels%20are%20granted%20to%20users.

25. *IBM documentation*. (n.d.). https://www.ibm.com/docs/en/i/7.1?topic=options-firewalls

26. *What is a firewall?* (2023, October 6). Cisco. https://www.cisco.com/c/en/us/products/security/firewalls/what-is-a-firewall.html#:~:text=A%20firewall%20is%20a%20network,defined%20set%20of%20security%20rules.

27. *What is Cryptography? Definition, Importance, Types | Fortinet*. (n.d.). Fortinet. https://www.fortinet.com/resources/cyberglossary/what-is-cryptography#:~:text=The%20Importance%20of%20Cryptography&text=Individuals%20and%20organizations%20use%20cryptography,to%20the%20sender%20and%20recipient.

### **Additional Resources:**

1. *OWASP Top Ten | OWASP Foundation*. (n.d.). https://owasp.org/www-project-top-ten/

2. *OWASP SAMM | OWASP Foundation*. (n.d.). https://owasp.org/www-project-samm/

3. *The model*. (n.d.). https://owaspsamm.org/model/

4. https://www.wireshark.org

5. https://www.aircrack-ng.org

6. https://www.snort.org

7. https://www.openvas.org

8. https://www.pfsense.org
