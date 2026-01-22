CORE CONCEPTS:
Encryption is used to protect systems in transit
WPA secures traffic between your device and the Wi Fi access point
HTTP sends data in plaintext and is vulnerable to eavesdropping
HTTPS uses TLS to encrypt data between browser and server
Machine in the middle attacks can read or modify unencrypted traffic

Web Security:
1. Packet sniffing allows attackers to read unencrypted packets
2. Cookies are session identifiers used to keep users logged in
3. Session hijacking occurs when attackers steal cookies
4. HTTPS protects cookies and prevents hijacking

Trust and Certificates:
1. TLS uses public key cryptography
2. Websites present X.509 certificates
3. Certificate Authorities verify and sign certificates
4. Browsers trust sites through trusted CAs
5. SSL stripping exploits the first unencrypted request
6. HSTS forces browsers to always use HTTPS

Network Protection:
1. VPN encrypts all traffic between user and VPN server
2. VPN providers can see traffic after it exits the tunnel
3. SSH provides encrypted remote command access
4. Ports are numbered entry points for services
5. Port scanning checks which ports are open
6. Firewalls control which traffic is allowed in or out
7. Proxies inspect and filter network traffic

Threats:
1. Malware is malicious software
2. Viruses require user action to spread
3. Worms spread automatically over networks
4. Botnets are networks of infected machines
5. DDoS attacks overwhelm systems to deny service
6. Zero day attacks exploit unknown vulnerabilities

Defense:
1. Penetration testing finds weaknesses before attackers
2. Security through obscurity relies on hiding rather than securing
3. Layered defenses raise attacker cost
4. Updates and patches reduce known risks

Takeaway:
Security is about layers. No single tool is enough. Encryption protects data in transit, certificates establish trust, firewalls and ports control access, and updates reduce known risks. The goal is not perfect security but raising the cost so attackers move on.
