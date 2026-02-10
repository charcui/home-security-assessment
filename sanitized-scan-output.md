NOTE: This scan output has been sanitized. All IP addresses, MAC
addresses, and identifying details have been anonymized. The assessment
was conducted on a personally owned home network for educational
purposes.

\-\--

Starting Nmap 7.98 ( https://nmap.org ) Scan Time: \[REDACTED
TIMESTAMP\]

Nmap scan report for HOST-A Host is up (low latency). Not shown: 998
closed tcp ports

PORT STATE SERVICE VERSION 80/tcp open http Embedded IoT HTTP Server
443/tcp open https Embedded IoT HTTPS Server

\| http-csrf: \| No CSRF vulnerabilities detected \| http-stored-xss: \|
No stored XSS vulnerabilities detected \| http-dombased-xss: \| No
DOM-based XSS vulnerabilities detected

Device Type: IoT Device MAC Address: \[REDACTED\] Risk Level: Low Notes:
Web interface accessible on LAN only; no automated vulnerabilities
identified.

Nmap scan report for HOST-B Host is up (low latency). Not shown: 994
closed tcp ports

PORT STATE SERVICE 5000/tcp open rtsp 7000/tcp open rtsp 7100/tcp open
rtsp

Service Identification: - Proprietary media streaming service -
Authentication enforced (HTTP/RTSP 403 responses)

Device Type: Consumer Media Device MAC Address: \[REDACTED\] Risk Level:
Informational Notes: Expected service exposure for device role.

Nmap scan report for HOST-C Host is up (low latency). Not shown: 998
closed tcp ports

PORT STATE SERVICE 49152/tcp open tcpwrapped 62078/tcp open mobile-sync?

Notes: - Typical mobile device service exposure Risk Level:
Informational

Nmap scan report for HOST-D Host is up (moderate latency). Not shown:
998 closed tcp ports

PORT STATE SERVICE 49152/tcp open tcpwrapped 62078/tcp open tcpwrapped

Notes: - No externally accessible services identified Risk Level:
Informational

Nmap scan report for HOST-E Host is up (low latency). All scanned ports
are closed or ignored.

Notes: - No externally reachable services detected Risk Level:
Informational

Nmap scan report for HOST-F Host is up (low latency). Not shown: 998
closed tcp ports

PORT STATE SERVICE 49152/tcp open tcpwrapped 62078/tcp open mobile-sync?

Notes: - Expected behavior for device type Risk Level: Informational

Nmap scan report for HOST-G Host is up (low latency). Not shown: 999
filtered tcp ports

PORT STATE SERVICE VERSION 5357/tcp open http Microsoft HTTPAPI 2.0
(UPnP/SSDP)

\| http-dombased-xss: \| No DOM-based XSS vulnerabilities detected \|
http-stored-xss: \| No stored XSS vulnerabilities detected \| http-csrf:
\| No CSRF vulnerabilities detected

Service Info: - OS: Windows - Service used for local discovery

Notes: - Service limited to local network scope Risk Level: Low

Nmap scan report for HOST-I Host is up (low latency). Not shown: 999
closed tcp ports

PORT STATE SERVICE 7/tcp filtered echo

Notes: - ICMP/echo filtered - No actionable exposure Risk Level:
Informational

Nmap scan report for HOST-J Host is up (low latency). Not shown: 999
closed tcp ports

PORT STATE SERVICE 3001/tcp open ssl/management?

Notes: - Encrypted management interface - Restricted to internal network
Risk Level: Low

\-\--

Scan Type: Service detection + default NSE scripts Total Hosts Scanned:
11 Hosts Up: 10 Scan Duration: \~36 minutes
