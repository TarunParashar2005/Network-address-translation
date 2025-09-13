
Network Address Translation (NAT) is a process used by routers to modify the source or destination IP addresses of packets as they pass through. NAT allows multiple devices in a private network (using private IP addresses) to share a single public IP address when accessing external networks like the Internet

Types of NAT include:-

Static NAT – One-to-one mapping between a private and public IP.
Dynamic NAT – Maps private IPs to a pool of public IPs dynamically.
PAT (Port Address Translation / Overload) – Many private IPs share a single public IP using different port numbers.

By the end of this lab, you will be able to:-

Configure static NAT, dynamic NAT, and PAT (overload).
Differentiate between inside local, inside global, and outside global addresses.
Verify NAT translations with show ip nat translations.
Test communication between private hosts and a server using NAT.

Expected result:-

PCs should reach the server even though they use private IPs.
NAT translations will be visible in show ip nat translations.

It provides three major benefits:-

Address Conservation → Saves public IPv4 addresses by letting many hosts share one or a few global addresses.
Security → Hides internal network details from outside users.
Flexibility → Enables seamless communication between private networks and public networks.
