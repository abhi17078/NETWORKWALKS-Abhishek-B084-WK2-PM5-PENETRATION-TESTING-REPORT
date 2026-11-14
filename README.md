 Week 2 – Penetration Testing: Footprinting, OSINT & Network Scanning

## 1. Project Overview

This project is based on Footprinting and Reconnaissance, which is the first phase of ethical hacking and cybersecurity testing.

The main objective of this project is to collect publicly available information about a target website using different Kali Linux tools.

In this practical project, I used six different tools to gather information about domain registration, website technologies, IP addresses, HTTP headers, firewall protection, and DNS records.

**Target Domain:** networkwalks.com

**Operating System:** Kali Linux

**Project Type:** Cybersecurity and Ethical Hacking

---

## 2. Tools Used

The following six Kali Linux tools were used in this project:

1. WHOIS
2. WhatWeb
3. NSLookup
4. cURL
5. WAFW00F
6. DNSRecon

---

## 3. Practical Tasks

### Task 1: WHOIS – Domain Information Gathering

**Objective:**

To find domain registration details, registrar information, registration dates, and name servers.

**Command Used:**

```bash
whois networkwalks.com
```

**What I Learned:**

- How to check domain registration information.
- How to identify the domain registrar.
- How to find registration and expiry dates.
- How to check name servers.

**EVIDENCE 1 – WHOIS**
<img width="1920" height="922" alt="Screenshot_2026-11-14_18_58_22" src="https://github.com/user-attachments/assets/07edd31a-78a7-4f2b-8306-971b1e375892" />
<img width="1920" height="922" alt="Screenshot_2026-11-14_18_58_41" src="https://github.com/user-attachments/assets/6e1f8b8f-3599-4b3c-af8b-7baf38e0d0b7" />
<img width="1920" height="922" alt="Screenshot_2026-11-14_18_58_48" src="https://github.com/user-attachments/assets/80b9b24e-9eaf-4686-81a9-1c3d36eb4c17" />
<img width="1920" height="922" alt="Screenshot_2026-11-14_18_58_57" src="https://github.com/user-attachments/assets/4a8d5341-e348-4be7-ae08-da11571fc5aa" />


---

### Task 2: WhatWeb – Website Fingerprinting

**Objective:**

To identify the technologies, CMS, web server, and frameworks used by the target website.

**Command Used:**

```bash
whatweb networkwalks.com
```

**What I Learned:**

- Website technology identification.
- CMS detection.
- Web server information.
- Technology fingerprinting.

**EVIDENCE 2 – WHATWEB**

<img width="1920" height="922" alt="Screenshot_2026-11-14_19_05_38" src="https://github.com/user-attachments/assets/a5b11bfb-e6f7-4581-a7d3-54dcc8ddab5b" />


---

### Task 3: NSLookup – DNS Resolution

**Objective:**

To resolve the domain name into its IP address using DNS.

**Command Used:**

```bash
nslookup networkwalks.com
```

**What I Learned:**

- How DNS resolution works.
- How to find the IP address of a domain.
- How domain names connect to IP addresses.

**EVIDENCE 3 – NSLOOKUP**

<img width="1920" height="922" alt="Screenshot_2026-11-14_19_06_56" src="https://github.com/user-attachments/assets/763e94a6-26e8-4d9d-b09e-60f1e7f4d88e" />


---

### Task 4: cURL – HTTP Header Analysis

**Objective:**

To read HTTP response headers and check server information, status codes, cookies, and redirects.

**Command Used:**

```bash
curl -I https://networkwalks.com
```

**What I Learned:**

- How to check HTTP response headers.
- How to identify server information.
- How to understand HTTP responses.
- Basic web server analysis.

**EVIDENCE 4 – CURL**

<img width="1920" height="922" alt="Screenshot_2026-11-14_19_25_50" src="https://github.com/user-attachments/assets/139b388c-3481-4408-be09-137a10343b85" />


---

### Task 5: WAFW00F – Firewall Detection

**Objective:**

To detect whether a Web Application Firewall (WAF) is protecting the target website.

**Command Used:**

```bash
wafw00f networkwalks.com
```

**What I Learned:**

- Basic WAF detection.
- Understanding web application security.
- Identifying firewall protection.

**EVIDENCE 5 – WAFW00F**

<img width="1920" height="922" alt="Screenshot_2026-11-14_19_28_47" src="https://github.com/user-attachments/assets/420d75c7-6a92-424d-ba97-cb77fe3f30c5" />

---

### Task 6: DNSRecon – DNS Enumeration

**Objective:**

To enumerate DNS records such as name servers, mail servers, SPF, TXT, and SRV records.

**Command Used:**

```bash
dnsrecon -d networkwalks.com
```

**What I Learned:**

- DNS record enumeration.
- Name server identification.
- Mail server information.
- Understanding DNS configurations.

**EVIDENCE 6 – DNSRECON**

<img width="1920" height="922" alt="Screenshot_2026-11-14_19_30_34" src="https://github.com/user-attachments/assets/b4c4323d-b5f8-445a-be3e-e7523568fd82" />


---

## 4. Key Learnings

After completing this project, I learned:

- Basics of Footprinting and Reconnaissance.
- Practical use of six Kali Linux tools.
- Domain information gathering.
- DNS resolution and enumeration.
- Website technology fingerprinting.
- HTTP header analysis.
- Basic Web Application Firewall detection.

---

## 5. Conclusion

This project helped me understand the importance of Footprinting and Reconnaissance in cybersecurity.

I gained practical experience using different Kali Linux tools and learned how publicly available information can help in understanding a website's infrastructure.

It was a good learning experience and helped me improve my knowledge of Linux, networking, and ethical hacking.

---

## 6. Disclaimer

This project was completed for educational purposes as part of cybersecurity learning. Security testing should only be performed on systems where proper authorization has been granted.

**Project Category:** Cybersecurity | Ethical Hacking | Kali Linux

**Made by:** Abhishek

**LinkedIn:** [www.linkedin.com/in/abhishek-yadav-4655b0352](https://www.linkedin.com/in/abhishek-yadav-4655b0352)

**Project:** Footprinting and Reconnaissance Using Kali Linux

**Focus Areas:** Cybersecurity | Ethical Hacking | Footprinting | Reconnaissance | WHOIS | WhatWeb | DNS Enumeration | HTTP Header Analysis | WAF Detection | Kali Linux
