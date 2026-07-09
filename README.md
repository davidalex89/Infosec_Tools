# Infosec Tools

A categorized reference of security tools — open source, free, and commercial — worth knowing. Skews toward tools that are actively maintained and widely used in practice.

*Pull requests welcome.*

---

## Table of Contents

- [Reconnaissance & OSINT](#reconnaissance--osint)
- [Network Scanning & Enumeration](#network-scanning--enumeration)
- [Web Application Testing](#web-application-testing)
- [Exploitation Frameworks](#exploitation-frameworks)
- [Password Attacks & Credential Testing](#password-attacks--credential-testing)
- [Wireless Security](#wireless-security)
- [Traffic Analysis & Network Monitoring](#traffic-analysis--network-monitoring)
- [SIEM & Log Management](#siem--log-management)
- [Forensics & Incident Response](#forensics--incident-response)
- [Malware Analysis & Reverse Engineering](#malware-analysis--reverse-engineering)
- [Vulnerability Scanning & Management](#vulnerability-scanning--management)
- [Cloud & Container Security](#cloud--container-security)
- [Threat Intelligence](#threat-intelligence)
- [AI & Machine Learning for Security](#ai--machine-learning-for-security)
- [Browser Extensions](#browser-extensions)
- [Open Source vs. Commercial](#open-source-vs-commercial)

---

## Reconnaissance & OSINT

- **[Maltego](https://www.maltego.com)** — Graph-based OSINT and link analysis. Community edition free; commercial versions available.
- **[theHarvester](https://github.com/laramies/theHarvester)** — Gather emails, subdomains, hosts, and open ports from public sources. *(Open source)*
- **[Recon-ng](https://github.com/lanmaster53/recon-ng)** — Full-featured web reconnaissance framework with modular design. *(Open source)*
- **[SpiderFoot](https://github.com/smicallef/spiderfoot)** — Automated OSINT tool with 200+ modules for target profiling. *(Open source / commercial HX version)*
- **[Amass](https://github.com/owasp-amass/amass)** — In-depth attack surface mapping and asset discovery (DNS, IP, ASN). *(Open source — OWASP)*
- **[Subfinder](https://github.com/projectdiscovery/subfinder)** — Fast passive subdomain enumeration. *(Open source — ProjectDiscovery)*
- **[Shodan](https://www.shodan.io)** — Search engine for internet-connected devices. *(Freemium / API)*
- **[Censys](https://search.censys.io)** — Internet-wide scan data, certificates, and host intelligence. *(Freemium)*
- **[OSINT Framework](https://osintframework.com)** — Web-based directory of OSINT resources by category. *(Free)*
- **[Photon](https://github.com/s0md3v/Photon)** — Fast crawler designed for OSINT. *(Open source)*
- **[httpx](https://github.com/projectdiscovery/httpx)** — Fast HTTP probing and technology fingerprinting across large host lists. *(Open source — ProjectDiscovery)*
- **[dnsx](https://github.com/projectdiscovery/dnsx)** — High-speed DNS toolkit for resolution, wildcard detection, and record enumeration. *(Open source — ProjectDiscovery)*

---

## Network Scanning & Enumeration

- **[Nmap](https://nmap.org)** — The standard for host discovery, port scanning, and service fingerprinting. *(Open source)*
- **[Zenmap](https://nmap.org/zenmap)** — Official Nmap GUI. *(Open source)*
- **[Masscan](https://github.com/robertdavidgraham/masscan)** — Fastest internet-scale port scanner; useful for large subnets. *(Open source)*
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** — Template-based vulnerability scanner with a large community template library. *(Open source — ProjectDiscovery)*
- **[Rustscan](https://github.com/RustScan/RustScan)** — Extremely fast port scanner that pipes results into Nmap. *(Open source)*
- **[Naabu](https://github.com/projectdiscovery/naabu)** — Fast port scanner focused on reliability. *(Open source — ProjectDiscovery)*
- **[Netdiscover](https://github.com/netdiscover-scanner/netdiscover)** — Active/passive ARP-based network address scanner. *(Open source)*

---

## Web Application Testing

- **[Burp Suite](https://portswigger.net/burp)** — The industry-standard web app testing proxy. Community edition free; Pro is paid. *(Freemium)*
- **[OWASP ZAP](https://www.zaproxy.org)** — Full-featured web app scanner and proxy, actively maintained by OWASP. *(Open source)*
- **[sqlmap](https://sqlmap.org)** — Automated SQL injection detection and exploitation. *(Open source)*
- **[ffuf](https://github.com/ffuf/ffuf)** — Fast web fuzzer for directory/file discovery and parameter brute-forcing. *(Open source)*
- **[Gobuster](https://github.com/OJ/gobuster)** — Directory/DNS/vhost brute-forcing tool. *(Open source)*
- **[Nikto](https://github.com/sullo/nikto)** — Web server scanner for known vulnerabilities and misconfigurations. *(Open source)*
- **[Caido](https://caido.io)** — Modern web security testing platform, gaining traction as a Burp alternative. *(Freemium)*
- **[Wfuzz](https://github.com/xmendez/wfuzz)** — Web application fuzzer for brute-forcing parameters, auth, and more. *(Open source)*
- **[Arjun](https://github.com/s0md3v/Arjun)** — HTTP parameter discovery tool. *(Open source)*
- **[Dalfox](https://github.com/hahwul/dalfox)** — Fast XSS scanner and parameter analysis tool. *(Open source)*

---

## Exploitation Frameworks

- **[Metasploit Framework](https://www.metasploit.com)** — The most widely used exploitation framework. Community version free; Pro is paid. *(Open source / commercial)*
- **[Cobalt Strike](https://www.cobaltstrike.com)** — Commercial adversary simulation and red team platform. *(Commercial)*
- **[Sliver](https://github.com/BishopFox/sliver)** — Open source C2 framework from BishopFox, increasingly popular as a Cobalt Strike alternative. *(Open source)*
- **[Havoc](https://github.com/HavocFramework/Havoc)** — Modern C2 framework with an extendable agent. *(Open source)*
- **[Empire](https://github.com/BC-SECURITY/Empire)** — Post-exploitation framework with PowerShell and Python agents. *(Open source)*
- **[Armitage](https://www.fastandeasyhacking.com)** — GUI front-end for Metasploit. *(Open source)*
- **[SILENTTRINITY](https://github.com/byt3bl33d3r/SILENTTRINITY)** — Post-exploitation framework using .NET's DLR. *(Open source)*

---

## Password Attacks & Credential Testing

- **[Hashcat](https://hashcat.net)** — GPU-accelerated password cracking. Supports hundreds of hash types. *(Open source)*
- **[John the Ripper](https://www.openwall.com/john)** — Classic password cracker, still widely used. *(Open source)*
- **[Hydra](https://github.com/vanhauser-thc/thc-hydra)** — Fast network login cracker for dozens of protocols. *(Open source)*
- **[Medusa](https://github.com/jmk-foofus/medusa)** — Parallel, modular brute-force tool. *(Open source)*
- **[NetExec (nxc)](https://github.com/Pennyw0rth/NetExec)** — Active Directory enumeration and lateral movement (successor to CrackMapExec). *(Open source)*
- **[Responder](https://github.com/lgandx/Responder)** — LLMNR/NBT-NS/mDNS poisoner for capturing NetNTLM hashes. *(Open source)*
- **[Impacket](https://github.com/fortra/impacket)** — Python library and toolset for Windows networking protocols. Essential for AD attacks. *(Open source)*
- **[BloodHound](https://github.com/SpecterOps/BloodHound)** — Active Directory attack path analysis using graph theory. *(Open source)*
- **[Kerbrute](https://github.com/ropnop/kerbrute)** — Kerberos username enumeration and password spraying. *(Open source)*

---

## Wireless Security

- **[Aircrack-ng](https://www.aircrack-ng.org)** — Suite of tools for 802.11 monitoring, attacking, testing, and cracking. *(Open source)*
- **[Kismet](https://www.kismetwireless.net)** — Wireless network detector, sniffer, and IDS that works with monitor-mode hardware. *(Open source)*
- **[Bettercap](https://www.bettercap.org)** — Swiss army knife for network attacks and MITM. Supports WiFi, BLE, and Ethernet. *(Open source)*
- **[Wifite](https://github.com/derv82/wifite2)** — Automated wireless auditor. *(Open source)*
- **[hcxtools / hcxdumptool](https://github.com/ZerBea/hcxtools)** — WiFi key material capture and conversion for use with Hashcat. *(Open source)*
- **[WiFi Pineapple](https://www.hak5.org/products/wifi-pineapple)** — Purpose-built hardware for wireless auditing and pen testing. *(Commercial hardware)*

---

## Traffic Analysis & Network Monitoring

- **[Wireshark](https://www.wireshark.org)** — The standard packet capture and analysis tool. *(Open source)*
- **[tcpdump](https://www.tcpdump.org)** — CLI packet capture. Wireshark for the terminal. *(Open source)*
- **[Zeek](https://zeek.org)** — Network analysis framework that produces rich, structured logs. *(Open source)*
- **[Suricata](https://suricata.io)** — High-performance network IDS/IPS/NSM engine. *(Open source)*
- **[Snort](https://www.snort.org)** — Long-standing IDS/IPS; signature-based detection. *(Open source / commercial)*
- **[Security Onion](https://securityonionsolutions.com)** — Linux distro and platform built for threat hunting and NSM, integrating Zeek, Suricata, and Elastic. *(Open source)*
- **[RITA](https://github.com/activecm/rita)** — Real Intelligence Threat Analytics — analyzes Zeek logs for C2 beaconing and other threats. *(Open source)*
- **[NetworkMiner](https://www.netresec.com/?page=NetworkMiner)** — Passive network sniffer and PCAP analyzer. *(Free / commercial)*
- **[Arkime](https://arkime.com)** — Large-scale PCAP indexing and session search (formerly Moloch). *(Open source)*

---

## SIEM & Log Management

- **[Elastic / ELK Stack](https://www.elastic.co/security)** — Elasticsearch + Logstash + Kibana + Beats. Widely deployed SIEM foundation. *(Open source core / commercial features)*
- **[Wazuh](https://wazuh.com)** — Open source SIEM and XDR with agent-based host monitoring. *(Open source)*
- **[Graylog](https://graylog.org)** — Log management platform with good search and alerting. *(Open source / commercial)*
- **[OpenSearch Security Analytics](https://opensearch.org/docs/latest/security-analytics)** — AWS-backed Elasticsearch fork with security analytics capabilities. *(Open source)*
- **[Splunk](https://www.splunk.com)** — Enterprise SIEM/observability platform. Industry standard but expensive. *(Commercial)*
- **[Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel)** — Cloud-native SIEM/SOAR on Azure. *(Commercial / consumption-based)*
- **[Shuffle](https://shuffler.io)** — Open source SOAR for playbook automation; pairs with SIEMs for alert triage and response. *(Open source)*
- **[osquery](https://osquery.io)** — SQL-powered endpoint visibility; query running processes, sockets, and configs across fleets. *(Open source — Meta)*

---

## Forensics & Incident Response

- **[Autopsy / The Sleuth Kit](https://www.autopsy.com)** — Disk image and file system forensics. *(Open source)*
- **[Volatility](https://volatilityfoundation.org)** — Memory forensics framework — essential for analyzing RAM dumps. *(Open source)*
- **[SIFT Workstation](https://www.sans.org/tools/sift-workstation)** — SANS-built Linux distro preloaded with forensics tools. *(Free)*
- **[KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)** — Fast artifact collection and processing for Windows. *(Free)*
- **[Chainsaw](https://github.com/WithSecureLabs/chainsaw)** — Rapidly search and triage Windows event logs. *(Open source)*
- **[Hayabusa](https://github.com/Yamato-Security/hayabusa)** — Windows event log fast forensics and threat hunting. *(Open source)*
- **[CyberChef](https://github.com/gchq/CyberChef)** — Browser-based data transformation and analysis "Swiss army knife" from GCHQ. *(Open source)*
- **[Eric Zimmerman Tools (EZ Tools)](https://ericzimmerman.github.io)** — Comprehensive suite of Windows forensics utilities. *(Free)*
- **[REMnux](https://remnux.org)** — Linux distro for reverse-engineering and malware analysis. *(Free)*
- **[DFIR-ORC](https://github.com/DFIR-ORC/dfir-orc)** — Collects forensic artifacts at scale on Windows endpoints. *(Open source)*
- **[Timesketch](https://github.com/google/timesketch)** — Collaborative timeline analysis for incident response and threat hunting. *(Open source — Google)*

---

## Malware Analysis & Reverse Engineering

- **[Ghidra](https://ghidra-sre.org)** — NSA's open source reverse engineering suite. Strong competitor to IDA Pro. *(Open source)*
- **[IDA Pro / IDA Free](https://hex-rays.com/ida-pro)** — Long-standing industry-standard disassembler and debugger. *(Commercial / free limited version)*
- **[Binary Ninja](https://binary.ninja)** — Modern disassembler and binary analysis platform. *(Commercial / free cloud version)*
- **[x64dbg](https://x64dbg.com)** — Open source x64/x32 debugger for Windows. *(Open source)*
- **[Cutter](https://cutter.re)** — GUI frontend for Rizin/Radare2. *(Open source)*
- **[CAPE Sandbox](https://github.com/kevoreilly/CAPEv2)** — Malware sandbox with configuration extraction. *(Open source)*
- **[ANY.RUN](https://any.run)** — Interactive online malware sandbox. *(Freemium)*
- **[VirusTotal](https://www.virustotal.com)** — File and URL scanning against 70+ antivirus engines. *(Free / commercial API)*
- **[YARA](https://virustotal.github.io/yara)** — Pattern matching for malware identification and classification. *(Open source)*
- **[Detect-It-Easy (DIE)](https://github.com/horsicq/Detect-It-Easy)** — Identifies file types, packers, compilers, and protections. *(Open source)*
- **[floss](https://github.com/mandiant/flare-floss)** — Automatically extract obfuscated strings from malware (Mandiant FLARE). *(Open source)*

---

## Vulnerability Scanning & Management

- **[Greenbone / OpenVAS](https://www.greenbone.net)** — Open source vulnerability scanner. Community edition free. *(Open source / commercial)*
- **[Nessus](https://www.tenable.com/products/nessus)** — Widely used vulnerability scanner. Essentials (free up to 16 IPs); Pro is paid. *(Freemium / commercial)*
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** — Fast, template-based vulnerability scanner with massive community library. *(Open source)*
- **[Faraday](https://www.faradaysec.com)** — Collaborative vulnerability management platform. *(Open source / commercial)*
- **[DefectDojo](https://www.defectdojo.com)** — Open source DevSecOps vulnerability management. *(Open source)*
- **[Vulncheck](https://vulncheck.com)** — Exploit intelligence and KEV/XDB feeds beyond public CISA data. *(Commercial / API)*
- **[Dependency-Track](https://dependencytrack.org)** — SBOM analysis and continuous monitoring for third-party component risk. *(Open source — OWASP)*

---

## Cloud & Container Security

- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** — Multi-cloud security auditing across AWS, Azure, and GCP. *(Open source — NCC Group)*
- **[Prowler](https://github.com/prowler-cloud/prowler)** — Cloud security tool for AWS, Azure, and GCP with hundreds of checks. *(Open source)*
- **[Pacu](https://github.com/RhinoSecurityLabs/pacu)** — AWS exploitation framework for red teaming cloud environments. *(Open source — Rhino Security)*
- **[Trivy](https://github.com/aquasecurity/trivy)** — Comprehensive vulnerability scanner for containers, filesystems, and IaC. *(Open source — Aqua)*
- **[Grype](https://github.com/anchore/grype)** — Container image vulnerability scanner. *(Open source — Anchore)*
- **[Falco](https://falco.org)** — Runtime security and threat detection for containers and Kubernetes. *(Open source — CNCF)*
- **[Checkov](https://www.checkov.io)** — Static analysis for IaC (Terraform, CloudFormation, Kubernetes, etc.). *(Open source — Bridgecrew/Prisma)*
- **[CloudSploit](https://github.com/aquasecurity/cloudsploit)** — Cloud security configuration scanning. *(Open source — Aqua)*

---

## Threat Intelligence

- **[MISP](https://www.misp-project.org)** — Open source threat intelligence platform for sharing IoCs and threat data. *(Open source)*
- **[OpenCTI](https://www.opencti.io)** — Cyber threat intelligence management with STIX/TAXII support. *(Open source)*
- **[TheHive](https://www.strangebee.com/thehive)** — Scalable incident response and case management platform. *(Open source / commercial)*
- **[Cortex](https://www.strangebee.com/cortex)** — Analysis and active response engine that integrates with TheHive. *(Open source)*
- **[YARA](https://virustotal.github.io/yara)** — Pattern matching for malware classification and threat hunting. *(Open source)*
- **[SIGMA](https://github.com/SigmaHQ/sigma)** — Generic signature format for SIEM rules — write once, use anywhere. *(Open source)*
- **[STIX / TAXII](https://oasis-open.github.io/cti-documentation)** — Structured Threat Information Expression and sharing protocol standards. *(Open standard)*
- **[Abuse.ch](https://abuse.ch)** — Free threat intelligence feeds: MalwareBazaar, URLhaus, ThreatFox, Feodo Tracker. *(Free)*
- **[MITRE ATT&CK](https://attack.mitre.org)** — Adversary tactics, techniques, and procedures framework used across detection engineering. *(Open standard)*
- **[OpenSanctions](https://www.opensanctions.org)** — Consolidated sanctions, PEP, and watchlist data for screening and enrichment. *(Open source / API)*

---

## AI & Machine Learning for Security

Practitioner-focused ML/AI — anomaly detection on telemetry, LLM red teaming, and adversarial testing of models. Not a catalog of every data-science library; these are widely cited in security work.

### Anomaly Detection & Security Analytics

- **[PyOD](https://github.com/yzhao062/pyod)** — Python outlier detection toolkit; common starting point for unsupervised anomaly scoring on logs and metrics. *(Open source)*
- **[Kitsune](https://github.com/ymirsky/Kitsune-py)** — Online network anomaly detection via an ensemble of autoencoders on packet features. *(Open source — research)*
- **[Elastic Machine Learning](https://www.elastic.co/guide/en/machine-learning/current/ml-ad-overview.html)** — Built-in time-series anomaly detection and UEBA-style jobs in the Elastic Stack. *(Open source core / commercial)*

### LLM Security & Red Teaming

- **[Garak](https://github.com/NVIDIA/garak)** — LLM vulnerability scanner and probe harness; checks for jailbreaks, prompt injection, and data leakage patterns. *(Open source — NVIDIA)*
- **[Promptfoo](https://github.com/promptfoo/promptfoo)** — Repeatable LLM evaluation and red-team test suites with CI-friendly workflows. *(Open source)*
- **[LLM Guard](https://github.com/protectai/llm-guard)** — Input/output scanners for PII, injection, toxicity, and other policy violations in LLM pipelines. *(Open source — Protect AI)*

### Adversarial ML & Model Security

- **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)** — IBM's library for evasion, poisoning, extraction, and inference attacks against ML models. *(Open source — Linux Foundation)*
- **[Counterfit](https://github.com/Azure/counterfit)** — Microsoft's CLI for automated adversarial attack campaigns against deployed ML endpoints. *(Open source)*
- **[TextAttack](https://github.com/QData/TextAttack)** — Framework for adversarial attacks on NLP models; useful for testing classifier robustness. *(Open source)*

### Malware & Binary ML

- **[EMBER](https://github.com/elastic/ember)** — Open malware classifier benchmark and feature set from Elastic; de facto reference for PE static analysis ML. *(Open source — Elastic)*
- **[MalwareBazaar](https://bazaar.abuse.ch)** — Abuse.ch malware sample feed frequently used as labeled data for classification research. *(Free)*
- **[Capa](https://github.com/mandiant/capa)** — Mandiant's capability extractor; rules-based but pairs well with ML pipelines for feature engineering. *(Open source — Google/Mandiant)*

---

## Browser Extensions

Useful for passive reconnaissance and web app testing directly in the browser.

- **[Wappalyzer](https://www.wappalyzer.com)** — Identifies technologies (frameworks, CMS, libraries) used by websites.
- **[FoxyProxy](https://getfoxyproxy.org)** — Proxy switcher — essential for routing traffic through Burp Suite or ZAP.
- **[Cookie-Editor](https://cookie-editor.com)** — View, edit, and export cookies in one click.
- **[HackTools](https://github.com/LasCC/Hack-Tools)** — All-in-one cheat sheet extension: XSS, SQLi, reverse shells, and more.
- **[Shodan](https://www.shodan.io/add-ons)** — Shows Shodan data for the current IP/domain while you browse.
- **[DotGit](https://github.com/davtur19/DotGit)** — Checks if a `.git` directory is exposed on web servers.
- **[Retire.js](https://retirejs.github.io/retire.js)** — Detects use of vulnerable JavaScript libraries on visited pages.
- **[TruffleHog](https://github.com/trufflesecurity/trufflehog)** — Browser extension that checks for exposed secrets and credentials.

---

## Open Source vs. Commercial

Worth knowing that for most capabilities, open source tools match or exceed their commercial counterparts.

| Use Case | Open Source | Commercial Equivalent |
|---|---|---|
| Network IDS/IPS | Suricata, Snort | Cisco Firepower |
| NSM Platform | Security Onion, Zeek | Darktrace, ExtraHop |
| SIEM | Wazuh, Elastic Security | Splunk, Microsoft Sentinel |
| Vulnerability Scanning | OpenVAS, Nuclei | Nessus Pro, Qualys |
| Exploitation Framework | Metasploit, Sliver | Cobalt Strike |
| Endpoint Detection | Wazuh, Velociraptor | CrowdStrike, SentinelOne |
| Disk Forensics | Autopsy/TSK | EnCase, FTK |
| Memory Forensics | Volatility | Magnet RAM Capture |
| Network Access Control | FreeRADIUS | Cisco ISE |
| Cloud Security Audit | Prowler, ScoutSuite | Wiz, Prisma Cloud |
| Log Management | Graylog, ELK | Splunk |
| Threat Intelligence | MISP, OpenCTI | Recorded Future, ThreatConnect |
| LLM Red Teaming | Garak, Promptfoo | HiddenLayer, Robust Intelligence |
| Anomaly Detection | PyOD, Elastic ML | Darktrace, Vectra |
