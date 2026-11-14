# Week 2 – Footprinting, Reconnaissance & Network Scanning

**Cybersecurity & Ethical Hacking Internship**

## Project Information

- **Prepared By:** Meher Ali
- **Batch:** B084-C
- **Organization:** Networkwalks
- **Mentor:** Waqas Karim, CCIE
- **Date:** 12 November 2026
- **Platform:** Kali Linux

## Project Overview

This project focuses on Footprinting, Reconnaissance and Network Scanning using Kali Linux tools.

The practical work was divided into two parts:

1. Gathering publicly available information about the assigned domain `networkwalks.com`.
2. Discovering active devices on my own local network using Zenmap (Nmap).

## Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Penetration testing environment |
| Ping | Connectivity checking |
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS lookup |
| Curl | HTTP response headers |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS enumeration |
| Zenmap (Nmap) | Network host discovery |
| ipconfig | Local network configuration |

## Practical Commands

### 1. Connectivity Check
```bash
ping google.com
```

### 2. WHOIS
```bash
whois networkwalks.com
```

### 3. WhatWeb
```bash
whatweb networkwalks.com
```

### 4. Nslookup
```bash
nslookup networkwalks.com
```

### 5. Curl
```bash
curl -I https://networkwalks.com
```

### 6. Wafw00f
```bash
wafw00f networkwalks.com
```

### 7. DNSRecon
```bash
dnsrecon -d networkwalks.com
```

### 8. Local Network Configuration
```cmd
ipconfig
```

### 9. Zenmap / Nmap
- Target: My own local network
- Profile: Ping Scan
- Purpose: Discover active devices and view network topology.

## Key Findings

- Identified domain registration information.
- Detected website technologies and server information.
- Retrieved DNS records.
- Checked HTTP response headers.
- Identified ModSecurity as the detected Web Application Firewall.
- Discovered active devices on the local network.
- Generated a network topology diagram.

## Risk Assessment

The assessment covered:
- Website technology and version disclosure.
- Public hosting information.
- HTTP security headers.
- DNSSEC configuration.
- DNS software version disclosure.
- Local network device discovery.

## Recommendations

1. Keep website software and plugins updated.
2. Review HTTP security headers.
3. Enable DNSSEC.
4. Review DNS and email security settings.
5. Keep Web Application Firewall rules updated.
6. Secure the local network and router.
7. Perform security testing only with permission.

## Conclusion

During Week 2, I practised footprinting, reconnaissance and network scanning using Kali Linux tools. I learned how to collect public domain information, inspect website technologies, enumerate DNS records and discover active devices on a local network using Zenmap.

## Authorization and Disclaimer

All activities were performed for educational purposes against systems owned by me or systems for which authorization was obtained. Unauthorized scanning or testing is not permitted.

## Project Evidence

Practical screenshots, command outputs, and the network topology diagram will be added to the `Screenshots` folder.

---

**Prepared by Meher Ali**  
Cybersecurity & Ethical Hacking Internship – Week 02  
Networkwalks
