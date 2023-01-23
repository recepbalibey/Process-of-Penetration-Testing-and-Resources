# Process of Penetration Testing and Resources

![alt text](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj7vu1-H8khZ1L5JmwE7kYpDGNNbahp46gRVNJz-scI7j2_t_XoEl7QK7n-oW8ATDuzR-igPse73MR7rqfGLQVg5fhwJpOTxmgmVsQtxRirRl2QzRWDLOhyZewwFZNNMNw1ORsE2sjPgR538Z1S-EwoYjBLny9W9-hM1c05UkGpqMqRiTNFmdMVgcPM/w667-h229/0000004.png)

There are several phases to a typical pen testing engagement, which are as follows:

1. **Planning and reconnaissance**: This phase involves gathering information about the target system, including its IP addresses, open ports, and any publically available information such as company websites and social media profiles. This helps the pen tester to understand the attack surface and determine the most appropriate approach to take. Some useful tutorials, tools, and blogs to learn about this phase:

• The Wayback Machine: https://web.archive.org/ <br>
• Shodan: https://account.shodan.io/ <br>
• CentralOps: https://centralops.net/co/ <br>
• Certificate Search: https://crt.sh/ <br>
• Certificate Transparency (CT) Exposer: https://github.com/chris408/ct-exposer <br>
• YouGetSignal: https://www.yougetsignal.com/ <br>
• DomainTools: https://reverseip.domaintools.com/ <br>
• What is my IP Address?: https://www.ipaddress.com/ <br>
• Find out what websites are Built With: https://builtwith.com/ <br>
• Photon-Incredibly fast crawler designed for OSINT: https://github.com/s0md3v/Photon <br>
• Raccoon-Offensive Security Tool for Reconnaissance and Information Gathering https://github.com/evyatarmeged/Raccoon <br>
• OSINT Framework: https://osintframework.com/ <br>
• Hunter lets you find professional email addresses in seconds and connect with the people that matter to your business.: https://hunter.io/ <br>

------------
2. **Scanning**: In this phase, the pen tester uses specialized tools to scan the target system for vulnerabilities. This can include network scans, port scans, and vulnerability scans. The results of these scans are used to identify potential attack vectors. Some useful tutorials, tools, and blogs to learn about this phase:

• netdiscover: https://www.cyberpratibha.com/blog/netdiscover/ <br>
• Nmap: https://www.freecodecamp.org/news/what-is-nmap-and-how-to-use-it-a-tutorial-for-the-greatest-scanning-tool-of-all-time/ <br>
• Nmap Scripting Engine: https://linuxhint.com/nmap-scripting-engine-tutorial/ <br>
• SMB Enumeration: https://www.hackingarticles.in/a-little-guide-to-smb-enumeration/ <br>
• Legion Framework: https://www.c-sharpcorner.com/article/an-overview-of-network-penetration-testing-using-legion-framework/ <br>
• Nessus: https://www.tenable.com/blog/how-to-run-your-first-vulnerability-scan-with-nessus <br>
• OpenVAS: https://hackertarget.com/openvas-tutorial-tips/ <br>
• Wordlist: https://github.com/berzerk0/Probable-Wordlists <br>
• Wordlist: https://github.com/danielmiessler/SecLists <br>
• Wordlist: https://github.com/xajkep/wordlists <br>
• Turkish Wordlist: https://github.com/utkusen/turkce-wordlist <br>

------------
3. **Gaining access(Exploiting)**: Once vulnerabilities have been identified, the pen tester will attempt to exploit them to gain access to the system. This may involve using tools such as password-cracking software or exploiting known vulnerabilities in software or operating systems. Some useful tutorials, tools, and blogs to learn about this phase:

• Bind shell and reverse shell: https://encyclopedia.kaspersky.com/glossary/remote-shell/ <br>
• Netcat: https://www.geeksforgeeks.org/introduction-to-netcat/ <br>
• Metasploit: https://www.varonis.com/blog/what-is-metasploit <br>
• Meterpreter: https://www.javatpoint.com/meterpreter-in-ethical-hacking <br>
• Exploit Database: https://www.exploit-db.com/ <br>
• Exploit Database: https://sploitus.com/ <br>
• Exploit Database: https://cxsecurity.com/ <br>
• Exploit Database: https://www.rapid7.com/db/ <br>
• Exploit Database: https://www.vulnerability-lab.com/ <br>
• Man in the Middle Attack: https://www.cyberpratibha.com/kali-linux-man-in-the-middle-attack-tutorial/ <br>
• Promiscuous Mode: https://www.blumira.com/glossary/promiscuous-mode/ <br>
• Packet Storm: https://packetstormsecurity.com/ <br>

------------
4. **Maintaining access(Post Exploit)**: Once the pen tester has gained access to the system, they will try to maintain this access by setting up "backdoors" or other methods of maintaining access even if the original vulnerability is fixed. Post-exploit activities are a crucial part of an attacker's overall strategy, as they allow the attacker to maintain access to the compromised system and continue their malicious activities even if the initial vulnerability has been fixed. Some useful tutorials, tools, and blogs to learn about this phase:

• Post Exploitation Concept: https://www.javatpoint.com/post-exploitation-concept <br>
• Windows Exploit Suggester: https://github.com/bitsadmin/wesng <br>
• Linux Exploit Suggester 2: https://github.com/jondonas/linux-exploit-suggester-2 <br>
• A Guide To Linux Privilege Escalation: https://payatu.com/guide-linux-privilege-escalation/ <br>
• Advanced persistent threat (APT): https://www.imperva.com/learn/application-security/apt-advanced-persistent-threat/ <br>
• Using a Keylogger with Metasploit: https://www.offensive-security.com/metasploit-unleashed/keylogging/ <br>
• Msfvenom Tutorials for Beginners: https://www.hackingarticles.in/msfvenom-tutorials-beginners/ <br>
• Pass the Hash Attack: https://infosecwriteups.com/pass-the-hash-attack-ddf956cf9551 <br>
• How to Implement Pivoting and Relaying Techniques Using Meterpreter: https://medium.com/axon-technologies/how-to-implement-pivoting-and-relaying-techniques-using-meterpreter-b6f5ec666795

------------
5. **Covering tracks**: In this phase, the pen tester will try to cover their tracks by deleting any log files or other evidence of their activities. This is important to prevent the system administrator from detecting the pen test and potentially fixing the vulnerabilities before the testing is complete. Some useful tutorials, tools, and blogs to learn about this phase:

• Penetration Testing: Covering Tracks: https://resources.infosecinstitute.com/topic/penetration-testing-covering-tracks/ <br>
• How to cover your tracks after a penetration test: https://talkingcyber.uk/2022/09/10/how-to-cover-your-tracks-after-a-penetration-test/ <br>
• Eraser is a tool that can be used to securely delete files and wipe free space on a hard drive, making it more difficult for an attacker's activities to be detected <br>
• BleachBit is a tool that can be used to securely delete files, clear browser history and cache, and more, making it more difficult for an attacker's activities to be detected. <br> 
• Covering Track for EH on Penetration testing: https://tanmay26.medium.com/covering-track-for-eh-on-penetration-testing-8b9d8915b8ce <br>

------------
6. **Reporting**: The final phase of a pen test is to report on the findings and provide recommendations for how to fix any vulnerabilities that were identified. This report should include a detailed description of the vulnerabilities and any recommendations for fixing them. Some useful tutorials, tools, and blogs to learn about this phase:

• https://www.e-spincorp.com/pdf/Service/serviceDescription_externalpentest_internalsecurityassessment.pdf <br>
• What To Look For In A Penetration Testing Statement Of Work?: https://www.triaxiomsecurity.com/what-to-look-for-in-a-penetration-testing-statement-of-work/ <br>
• Rapid7 Master Services Agreement: https://www.rapid7.com/legal/msa/ <br>
• Abnormal Security Cloud Terms of Service: https://legal.abnormalsecurity.com/ <br>
• Non Disclosure: http://www.m5computersecurity.com/partners/NDA-M5-Systems.pdf <br>
• Non Disclosure:https://www.dla.gov.in/sites/default/files/pdf/NondisclosureAgreement.pdf <br>
• WHY YOU NEED PENETRATION TESTING RULES OF ENGAGEMENT AS PART OF YOUR PENETRATION TEST: https://www.emagined.com/blog/why-you-need-rules-of-engagement-as-part-of-your-penetration-test <br>
• Penetration Test Report: https://www.offensive-security.com/reports/sample-penetration-testing-report.pdf <br>
• Penetration Test Report: https://pentestreports.com/reports/PrimoConnect/SAMPLE+Security+Testing+Findings.pdf <br>

![alt text](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhWrh1FQcVOB1eIIz6i0t2HjVde5g8cz7kj2FCY9T_B57pwM8X82pKb58e9j9pc4iDerwN7FkDq8HYkmioQAwWprIGmOcnv_fsvsgcOdyqymwtskP2-OZ9LnU1mWmk5PEr_QcgnD5u48njj7IFkobJl_wsVDEt97atIRQfVfoCx3c3iHb7JTjUpyti1/w597-h220/000007.png)

------------
7. **Security Hardening**: The process of enhancing the security of a system or application by reducing its attack surface and minimizing the potential for successful attacks. This can be achieved through a variety of methods, including:

• What Is SMB Protocol and Why Is it a Security Concern?: https://cybersophia.net/articles/what-is/what-is-smb-protocol-and-why-is-it-a-security-concern/ <br>
• Restrict access on RDP by IP Address: https://www.mivocloud.com/en/blog/Restrict-access-on-RDP-by-IP-Address <br>
• Restrict Access to Only Specified Users or Computers: https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-firewall/restrict-access-to-only-specified-users-or-devices <br>
• Disabling NTLMV1: https://www.csun.edu/it/ntlmv1#:~:text=Disabling%20NTLMV1,disable%20NTLMv1%20through%20the%20registry. <br>
• Debug Privilege: https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debug-privilege <br>
• Password security – Understanding the basics: https://saferinternet.org.uk/blog/password-security-understanding-the-basics <br>
• GPO - Disable cached-account logon: https://techexpert.tips/windows/gpo-disable-cached-account-logon/ <br>
• RDP: https://www.eshlomo.us/restricted-rdp-for-admin-restrictedadmin/#:~:text=Restricted%20Admin%20Mode,-Restricted%20Admin%20Mode&text=This%20means%20that%20if%20malware,for%20the%20malware%20to%20attack. <br>
• Share and NTFS Permissions: https://learn.microsoft.com/en-us/iis/web-hosting/configuring-servers-in-the-windows-web-platform/configuring-share-and-ntfs-permissions <br>
• How to Disable NetBIOS and LLMNR Protocols in Windows Using GPO?: https://woshub.com/how-to-disable-netbios-over-tcpip-and-llmnr-using-gpo/ <br>
• ARP Poisoning: What it is & How to Prevent ARP Spoofing Attacks: https://www.varonis.com/blog/arp-poisoning <br>
• Antivirus tests: https://www.av-test.org/en/ <br>
• Why You Need To Know About HSTS and SSL Stripping Attack?: https://www.encryptionconsulting.com/hsts-and-ssl-stripping-attack/ <br>

By following a structured approach and covering all of these phases, organizations can ensure that they are thoroughly testing the security of their systems and identifying any vulnerabilities that may be exploited by cybercriminals. Make sure to include all of these phases in your pen-testing process to keep your systems secure.


References: <br>
• https://chat.openai.com/ <br>
• https://recepbalibey.blogspot.com/2023/01/understanding-process-of-penetration.html  <br>
• https://www.udemy.com/user/kayhan-20/
