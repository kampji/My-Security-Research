# My Security Research

| Identifier | Disclosed | Name | Summary | Impact | References |
|---|---|---|---|---|---|
| [CVE-2020-5132](CVE-2020-5132.md) | 2020-09-07 | Internal Domain Disclosure in SonicWall SSL-VPN Login Portal | SonicWall SSL-VPN login portals expose internal domain names to unauthenticated users. Unregistered names under public TLDs can be purchased to capture leaked internal DNS traffic and credentials. | Credential Compromise, Information Disclosure | [CVE Record](https://www.cve.org/CVERecord?id=CVE-2020-5132)<br>[SonicWall Advisory](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2020-0006) |
| [CVE-2020-13998](CVE-2020-13998.md) | 2020-06-10 | User Enumeration in Citrix XenApp 6.5 | With 2FA enabled, XenApp 6.5 shows its 2FA error page only for valid usernames, letting unauthenticated attackers enumerate users. End of life; no patch. | Information Disclosure | [CVE Record](https://www.cve.org/CVERecord?id=CVE-2020-13998)<br>[Advisory](https://gist.github.com/kampji/11e259d68ad98a6f0f898132f1961a96) |
| [CVE-2020-12679](CVE-2020-12679.md) | 2020-05-06 | Reflected Cross-Site Scripting in ShoreTel Conference Web Platform | The ShoreTel Conference Web Application (19.50.1000.0) reflects the path after `home.php` unsanitized, allowing arbitrary JavaScript and HTML injection. Fixed in MiVoice Connect 18.7 SP2. | Code Execution, Information Disclosure | [CVE Record](https://www.cve.org/CVERecord?id=CVE-2020-12679)<br>[Advisory](https://gist.github.com/kampji/5ade2d15817650a725aa89fa2e6e4752)<br>[Mitel](https://www.mitel.com/articles/what-happened-shoretel-products) |


## About Me
My name is Jill Kamperides. I entered cybersecurity in 2019 after being hired at a small consulting firm based on the South Shore of Massachusetts, OCD Tech, having just graduated from the University of Massachusetts Boston with an English degree. I was an entry level analyst assigned solely to a privileged access management program for an international bank, reconciling 1000s of Linux servers daily. After automating a large portion of that process with Python, I was promoted to the penetration testing team.

In the years that have followed, I have acquired industry certifications, uncovered critical vulnerabilities (many of which are locked behind clients’ NDAs), registered CVEs, scraped 1 billion robots.txt entries from the worldwide web, presented at conferences, and had my work published in hacking magazines. I have grown, led, and mentored penetration testing teams, even spanning international borders.

I specialize in internal, external, web application, mobile application, and wireless penetration testing, along with social engineering and red teaming. Tangentially, I dabble in the RF space, as both a licensed amateur radio operator (KD1AGW) and satellite enthusiast.

This repository is for formally tracking my security research. Thanks for reading.


## Stay Connected
https://www.linkedin.com/in/jkamperides/ 

https://medium.com/@jillkamperides

https://kampji.github.io/
