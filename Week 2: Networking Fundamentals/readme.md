### Questions:
1. What is an IP address, and why is it essential in networking?
2. Differentiate between IPv4 and IPv6.
3. Explain the roles of routers, switches, and firewalls in a network.

### Answers:
1. An IP address is a numerical label assigned to each device participating in a computer network. It is essential for device identification and location.
2. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses. IPv6 was introduced to address the limitation of IPv4 addresses.

   ![HTTP vs HTTPS Diagram](https://github.com/sushmita950/CyberSecurity/blob/main/Week%202%3A%20Networking%20Fundamentals/IPv4-Address-Format.png)
4. Routers connect different networks, switches connect devices within a network, and firewalls control incoming and outgoing network traffic.

### Tasks:
# Network Commands Use Cases

## 1. Ping Command:
### Purpose:
The `ping` command is used to test the reachability of a host on an Internet Protocol (IP) network.

### Example:
```bash
ping google.com

- Install Nmap and perform a basic network scan on your home network.

- Install Nmap on Ubuntu using the following command:
  ```bash
  sudo apt-get install nmap
- Explore Wireshark, capture network traffic, and analyze the data.
just write this in markdown format
# Network Commands Use Cases

## 1. Ping Command:
### Purpose:
The `ping` command is used to test the reachability of a host on an Internet Protocol (IP) network.

### Example:
```bash
ping google.com
Use Case:
Scenario: Verify connectivity to Google's servers.
Output Interpretation: Successful pings indicate a healthy network connection, while timeouts or packet loss may suggest connectivity issues.
2. Traceroute Command:
Purpose:
The traceroute command traces the route that packets take to reach a destination host.

Example:
bash
Copy code
traceroute google.com
Use Case:
Scenario: Investigate the path taken by packets to reach Google's servers.
Output Interpretation: Each hop in the output represents a router or network device along the route.
3. Nslookup Command:
Purpose:
The nslookup command is used to query DNS (Domain Name System) servers to obtain domain-related information.

Example:
bash
Copy code
nslookup google.com
Use Case:
Scenario: Obtain the IP address associated with the domain name "google.com."
Output Interpretation: Provides information about the domain, including its IP address and the DNS server used.
4. Nmap Command:
Purpose:
The nmap command is a versatile network scanning tool used for various tasks such as host discovery, port scanning, and service version detection.

Example:
bash
Copy code
nmap google.com
Use Case:
Scenario: Perform a basic scan on Google's servers to identify open ports and services.
Output Interpretation: Reveals information about open ports, services, and potentially vulnerable areas in the network.

