![](http://www.catb.org/hacker-emblem/glider.png)

* [Footprinting and Reconnaissance](#footprinting-and-reconnaissance)
* [Scanning Networks](#scanning-networks)
* [Enumeration](#enumeration)
* [System Hacking](#system-hacking)
* [Malware Threats](#malware-threats)
* [Sniffing](#sniffing)
* [Social Engineering](#social-engineering)
* [Denial-of-Service](#denial-of-service)
* [Session Hacking](#session-hacking)
* [Hacking Webservers](#hacking-webservers)
* [Hacking Web Applications](#hacking-web-applications)
* [SQL Injection](#sql-injection)
* [Hacking Wireless Networks](#hacking-wireless-networks)
* [Hacking Mobile Platforms](#hacking-mobile-platform)
* [Evading IDS, Firewalls and Honeypots](#evading-ids-firewalls-and-honeypots)
* [Forensics](#forensics)
* [Reverse Engineering](#reverse-engineering)
* [Cloud Computing](#cloud-computing)
* [Cryptography](#cryptography)
* [Cybersecurity Standarts and Documents]()


## Footprinting and Reconnaissance
*  [Footprinting](https://en.wikipedia.org/wiki/Footprinting), [PTES](http://www.pentest-standard.org/index.php/Intelligence_Gathering#Footprinting)
* Objectives: 
  * Collect Network Information
  * Collect System Information
  * Collect Organisation's Information
* Methods:
  * Footprinting through Search Engines
    * Search for Public and Restricted Wesites
  * Operating System Identification
     * Tools: [Netcraft](http://netcraft.com), [SHODAN](http://shodan.io)
  * Get Location Information:
     * Tools: [Google Maps](https://maps.google.com), [Yandex Panorama](https://yandex.ru/maps) 
  * Social Networking Sites (SNS) and People Search Services
     * Tools: Linkedin, Facebook, Twitter,  Vkontakte, Odnoklassniki
  * Collect Financial Information and [Financial Intelligence](https://en.wikipedia.org/wiki/Financial_intelligence)
  * Searching through Job Sites
     * Tools: Linkedin, Monster.com, HH.ru, zarplata.ru
  * Footprinting using [Google Dorks](https://en.wikipedia.org/wiki/Google_hacking)
    * Resources: [Powersearching](http://www.powersearchingwithgoogle.com/), [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/)
  * Footprinting using Social Media
  * [Competitive intelligence](https://en.wikipedia.org/wiki/Competitive_intelligence)
  * Website footprinting
    * Tools: [OWASP Zaproxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project), [Burp Suite](https://portswigger.net/burp/), WebSpiders, HTTrack, GNU Wget
  * Email footprinting
  * [WHOIS](https://en.wikipedia.org/wiki/WHOIS) footprinting
    * Resources: [RU-CENTER](https://www.nic.ru/whois/en/)
  * DNS footprinting
    * Tools: DNSstuff
  * Network footprinting: [TCP/IP stack fingerprinting](https://en.wikipedia.org/wiki/TCP/IP_stack_fingerprinting)
    * Tools: [Qualys SSL LAB](http://ssllab.com/sslscan), traceroute, Nmap, p0f, [SHODAN](https://www.shodan.io/), [Censys](https://www.censys.io/), [ZoomEye](https://www.zoomeye.org/)
  * Footprinting using Social Engineering
 * Tools: [Maltego](https://www.paterva.com/web7/buy/maltego-clients.php), [recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng), FOCA, [Metagoofil](http://www.edge-security.com/metagoofil.php)
 * Resources: [Awesome-OSINT](https://github.com/jivoi/awesome-osint)
 
## Scanning Networks
* Objectives:
  * Discover IP address and open [ports](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
    * Tools: [Nmap](https://nmap.org), [Hping](), [nping](), [scapy](https://github.com/secdev/scapy), [SolarWinds Engineers Toolset](http://www.solarwinds.com/engineers-toolset)
  * Discover [operating system](https://en.wikipedia.org/wiki/Operating_system)
  * Discover services running
  * Discover [vulnerabilities](https://en.wikipedia.org/wiki/Vulnerability_(computing)):
    * Tools: [Nessus](https://www.tenable.com/products/nessus-vulnerability-scanner), [OpenVAS](http://www.openvas.org/), [Microsoft Baseline Security Analyzer](https://technet.microsoft.com/ru-ru/security/cc184924.aspx) 
* Methods: 
  * [ICMP](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol) Scanning, [Ping Sweep](https://en.wikipedia.org/wiki/Ping_sweep), [RFC5927 ICMP Attacks against TCP](https://www.rfc-editor.org/rfc/rfc5927.txt)
  * [SSDP](https://en.wikipedia.org/wiki/Simple_Service_Discovery_Protocol) Scanning
  * TCP Connect/Full Open Scan
  * [Stealth Scan (Half-open Scan)](https://en.wikipedia.org/wiki/TCP_half-open)
  * Inverse TCP Flag Scan
  * [Xmas Scan](https://en.wikipedia.org/wiki/Christmas_tree_packet)
  * [ACK Flag Probe Scan](https://en.wikipedia.org/wiki/Port_scanner#ACK_scanning)
  * [IDLE Scan](https://en.wikipedia.org/wiki/Idle_scan)
  * [UDP Scanning](https://en.wikipedia.org/wiki/Port_scanner#UDP_scanning)
* Resources: [Qualys FreeScan](https://freescan.qualys.com/freescan-front/), [High-Tech Bridge Free SSL Test](https://www.htbridge.com/ssl/), [IVRE](https://github.com/cea-sec/ivre)

## Enumeration
* [NetBIOS](https://en.wikipedia.org/wiki/NetBIOS) Enumeration
* [SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol) Enumeration
* [LDAP](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) Enumeration
* [NTP](https://en.wikipedia.org/wiki/Network_Time_Protocol) Enumeration

## System Hacking
* Objectives:
  * Gain Access to System: [Password cracking](https://en.wikipedia.org/wiki/Password_cracking), [Preimage attack](https://en.wikipedia.org/wiki/Preimage_attack), 
  * [Priveledge Escalation](https://en.wikipedia.org/wiki/Privilege_escalation)
  * Maintain [Remote Access](https://en.wikipedia.org/wiki/Remote_administration_software)
  * [Rootkit](https://en.wikipedia.org/wiki/Rootkit)
  * [Steganography](https://en.wikipedia.org/wiki/Steganography)
  * Hide the [Evidence of Compromise](https://en.wikipedia.org/wiki/Indicator_of_compromise)
*
* Tools: [L0phtCrack](http://www.l0phtcrack.com/), [Cain & Abel](http://www.oxid.it/cain.html)
*

## [Malware](https://en.wikipedia.org/wiki/Malware) Threats, [Trojans](https://en.wikipedia.org/wiki/Trojan_horse_(computing)) and [Viruses](https://en.wikipedia.org/wiki/Computer_virus)
*
*
*
* Resources: [Awesome-Malware-Analysis](https://github.com/rshipp/awesome-malware-analysis), [Awesome-Threat-Intelligence](https://github.com/hslatman/awesome-threat-intelligence)

## Sniffing
*
*
*
* Resources:

## [Social Engineering](https://en.wikipedia.org/wiki/Social_engineering_(security))
*
*
*
*

## [Denial-of-Service](https://en.wikipedia.org/wiki/Denial-of-service_attack)
* 
*
*
* Resources: [RFC4732](https://tools.ietf.org/html/rfc4732)

## [Session Hacking](https://en.wikipedia.org/wiki/Session_hijacking)
* [Spoofing](https://en.wikipedia.org/wiki/Spoofing_attack)
* Application Level Session hijacking:
 * [Session fixation](https://en.wikipedia.org/wiki/Session_fixation)
 * [Cross-site scripting (XSS)](https://en.wikipedia.org/wiki/Cross-site_scripting)
 * [Cross-site Request Forgery](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
 * [Browser hijacking](https://en.wikipedia.org/wiki/Browser_hijacking)
 * [Session poisoning](https://en.wikipedia.org/wiki/Session_poisoning)
 * [Man-in-the-browser](https://en.wikipedia.org/wiki/Man-in-the-browser)
 * [Man-in-the-middle](https://en.wikipedia.org/wiki/Man-in-the-middle_attack)
 * [Session Replay](https://en.wikipedia.org/wiki/Session_replay)
* Network-level Session Hijacking:
 * [IP Spoofing](https://en.wikipedia.org/wiki/IP_address_spoofing)
 * [Packet Sniffing](https://en.wikipedia.org/wiki/Packet_analyzer)
 * TCP/IP Hijacking
 * UDP Hijacking
 * Blind Hijacking
 * [ARP Spoofing](https://en.wikipedia.org/wiki/ARP_spoofing)
* [IPSec](https://en.wikipedia.org/wiki/IPsec),[RFC7296](https://www.rfc-editor.org/rfc/rfc7296.txt)
* Tools: [OWASP Zaproxy](https://github.com/zaproxy/zaproxy), [Burp Suite](https://portswigger.net/burp/), [Firebug](https://developer.mozilla.org/en-US/docs/Tools), [Cain and Abel](http://www.oxid.it/cain.html), [Ettercap](https://ettercap.github.io/ettercap/), [sslstrip](https://github.com/moxie0/sslstrip),[Websploit](http://sourceforge.net/projects/websploit/), DroidSheep, DroidSniff

## Hacking [Webservers](https://en.wikipedia.org/wiki/Web_server)
*
*
*
* Resources: [PunkSRIDER](https://www.punkspider.org/), [IVRE](https://ivre.rocks/)

## Hacking Web Applications
*
*
*
* Resources: [Awesome-Web-Hacking](https://github.com/infoslack/awesome-web-hacking)

## [SQL Injection](https://en.wikipedia.org/wiki/SQL_injection)
* 
* 
*
* Tools: [SQLmap](http://sqlmap.org/)

## Hacking Wireless Networks
*
*
*
* Resources: [SP 800-153	Guidelines for Securing Wireless Local Area Networks (WLANs)](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-153.pdf)

## Hacking Mobile Platforms
*
*
*
* Resources: [Android-Security-Awesome](https://github.com/ashishb/android-security-awesome)

## Evading [IDS](https://en.wikipedia.org/wiki/Intrusion_detection_system), [Firewall](https://en.wikipedia.org/wiki/Firewall_(computing)) and [Honeypots](https://en.wikipedia.org/wiki/Honeypot_(computing))
* Network-based Intrusion Detection System
* [Host-based Intrusion Detection System](https://en.wikipedia.org/wiki/Host-based_intrusion_detection_system)
*
* Resources: [Awesome-Honeypots](https://github.com/paralax/awesome-honeypots)

## [Forensics](https://en.wikipedia.org/wiki/Digital_forensics)
*
* Windows Forensics
 * Objectives:
   * Garthering Volatile System Information
   * Network and Process Information
   * Parsing Registry
   * User Activity
   * Cache, Cookie and Browser History Analysis
   * Checking Integrity
   * Searching with Event Viewer
 * Tools: [Sysinternals](https://live.sysinternals.com/), [ESET SysInspector](https://www.eset.com/int/support/sysinspector/), [hardinfo](http://hardinfo.berlios.de/)
* Resources: [Awesome-Forensics](https://github.com/Cugu/awesome-forensics), [Awesome-Incident-Response](https://github.com/meirwah/awesome-incident-response), [ForensicsWiki](http://forensicswiki.org/wiki/Main_Page)

## [Reverse Engineering](https://en.wikipedia.org/wiki/Reverse_engineering)
*
*
* Tools: [IDA Pro](https://www.hex-rays.com/products/ida/), [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware.shtml), [WDK\Windbg](https://msdn.microsoft.com/en-us/windows/hardware/hh852365.aspx), [OllyDBG](http://www.ollydbg.de/), [Radare2](http://rada.re/r/index.html), [x64_dbg](http://x64dbg.com/), [Immunity Debugger](http://debugger.immunityinc.com/), [dnSpy](https://github.com/0xd4d/dnSpy), [GNU Debugger](http://www.gnu.org/software/gdb/)
* Resources: [Awesome-Reversing](https://github.com/tylerph3/awesome-reversing)

## [Cloud Computing](https://en.wikipedia.org/wiki/Cloud_computing)
*
*
*
*

## [Cryptography](https://en.wikipedia.org/wiki/Cryptography) and [Anonimity]()
 * Objectives: Confidentiality, [Integrity](https://en.wikipedia.org/wiki/Data_integrity), [Authenication](https://en.wikipedia.org/wiki/Authentication), [Non-repudiation](https://en.wikipedia.org/wiki/Non-repudiation)
 * Types: [Asymmetric](https://en.wikipedia.org/wiki/Public-key_cryptography), [Symmetric](https://en.wikipedia.org/wiki/Symmetric-key_algorithm)
* [Data Encryption Standart (DES)](https://en.wikipedia.org/wiki/Data_Encryption_Standard)
* [Triple DES](https://en.wikipedia.org/wiki/Triple_DES)
  * Resources: [NIST SP 800 67 r1 Recommendation forthe Triple Data Encryption Algorithm (TDEA) Block Cipher](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-67r1.pdf)
* [Advanced Encryption Standart (AES)](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)
  * Resources: [FIPS 197	Advanced Encryption Standard](http://csrc.nist.gov/publications/fips/fips197/fips-197.pdf)
  * Tools: [ccrypt](http://ccrypt.sourceforge.net/), [WinAES](https://github.com/yunzhu-li/winaes)
* [RC4](https://en.wikipedia.org/wiki/RC4), [RC5](https://en.wikipedia.org/wiki/RC5), [RC6](https://en.wikipedia.org/wiki/RC6) Algorithms
* [Digital Signature Algorithm (DSA)](https://en.wikipedia.org/wiki/Digital_Signature_Algorithm)
  * Resources: [FIPS 186-4 Digital Signature Standard (DSS)](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.186-4.pdf)
* [Rivest Shamir Adleman (RSA)](https://en.wikipedia.org/wiki/RSA_(cryptosystem))
* [Diffie-Hellman](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)
  * Resources: [NIST SP 800 56A r2 Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-56Ar2.pdf), [RFC 2631 Diffie-Hellman Key Agreement Method](https://tools.ietf.org/rfc/rfc2631.txt)
* [Message Digest Function (MD5)](https://en.wikipedia.org/wiki/MD5)
* [GOST (cifer)](https://en.wikipedia.org/wiki/GOST_(block_cipher))
 * Tools: MD5 calculator, [CrypTool](https://www.cryptool.org/en/), HahsCalc, [HashDroid](https://play.google.com/store/apps/details?id=com.hobbyone.HashDroid)
* [Secure](https://en.wikipedia.org/wiki/SHA-1) [Hashing](https://en.wikipedia.org/wiki/SHA-2) [Algorithm](https://en.wikipedia.org/wiki/SHA-3) (SHA)
  * Resources: [FIPS 180-4	Secure Hash Standard (SHS)](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)
* [Secure Shell (SSH)](https://en.wikipedia.org/wiki/Secure_Shell),[RFC4251](https://www.rfc-editor.org/rfc/rfc4251.txt)
 * Tools: [OpenSSH](http://www.openssh.com/), [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/), [SecureCRT](https://www.vandyke.com/products/securecrt/index.html), [WinSCP](https://winscp.net/eng/index.php)
* [Pretty Good Privacy (PGP)](https://en.wikipedia.org/wiki/Pretty_Good_Privacy)
 * Tools: [GNU Privacy Guard](https://www.gnupg.org/)
* [Public Key Infrastructure (PKI)](https://en.wikipedia.org/wiki/Public_key_infrastructure)
 * [Digital certificate](https://en.wikipedia.org/wiki/Public_key_certificate)
 * [Certificate Authority (CA)](https://en.wikipedia.org/wiki/Certificate_authority)
 * [Validation Authority](https://en.wikipedia.org/wiki/Validation_authority)
 * [Self-signed certificate](https://en.wikipedia.org/wiki/Self-signed_certificate)
* [Secure Sockets Layer (SSL)](https://en.wikipedia.org/wiki/Transport_Layer_Security), [RFC6101](https://www.rfc-editor.org/rfc/rfc6101.txt)
 * Tools: [OpenSSL](https://www.openssl.org/), [GnuTLS](http://gnutls.org/), [LibreSSL](http://www.libressl.org/), [stunnel](https://www.stunnel.org/index.html), [Keyczar](https://github.com/google/keyczar)
* [Disk Encryption](https://en.wikipedia.org/wiki/Disk_encryption)
 * Tools: [VeraCrypt](https://sourceforge.net/projects/veracrypt/), []()
* Case study: [Heartbleed](https://en.wikipedia.org/wiki/Heartbleed), [Poodle](https://en.wikipedia.org/wiki/POODLE)
* Resources: [Awesome-Cryptography](https://github.com/sobolevn/awesome-cryptography), [Cryptanalysis](https://en.wikipedia.org/wiki/Cryptanalysis)

## Cybersecurity Standarts and Documents
* [Penetration Testing Execution Standart](http://www.pentest-standard.org/index.php/Main_Page)
* [Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page)
* [Open Source Security Testing Methodology Manual (OSSTMM)](http://www.isecom.org/research/osstmm.html)
