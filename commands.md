# COMMANDS USED
1. 'ipconfig'
  - its purpose is to show or display the computer basic IP network configuration
Example:
IPv4 address: 192.0.2.10
Subnet mask: 255.255.255.0
Default gateway: 192.0.2.1

When to use it?
  - when troubleshooting network issues and connectivity or checking whether the computer has a valid IP address and default gateway
What i learned?
  - This command shows you the computers network configuration. The command can also help you find any wrong or missing IP settings.

2. 'ipconfig /all'
  - its purpose is to display all detailed network adapter configuration
Information given by the command:
- IPv4 and IPv6 addresses
- MAC address
- DCHP configuration
- DNS servers
- Default gateway

When to use it?
 - when investigating DCHP, DNS, or network adapter connectivity or configuration issues
What i learned?
  - This command provides extra information that can help identify problems in network configuration

3. 'ping'
  - its purpose is to test netwrok connectivity between devices
Example:
'ping example.com'
'ping 192.0.2.1'

When to use it?
  - when checking whether can communicate wit another device or server
What i learned?
  - ping uses ICMP Echo Requests and Replies to check if a devices reachable and to measure how long it takes for a signal to go to the device and come back. 

4. 'tracert'
  - display the network route taken to reach a destination
Example:
'tracert example.com'

  when to use it?
  - when investigating netwrok routing problems 
  what i learned?
  - command displays intermediate network hops between the computer and the destination

5. 'nslookup'
  - checks DNS resolution
Example:
'nslookup example.com'

  when to use it?
  - when looking into problems where sites or services cannot be reached using domain names
  what i learned?
  - DNS turns domain names into IP addresses. nslookup helps verify whether a DNS server can resolve domain names

6. 'ipconfig /flushdns
  - clears the local DNS resolver cache
Example:
'ipconfig /flushdns

  when to use it?
  - when you are troubleshooting DNS cache problems, such, as DNS records stored locally you should use this method
  what i learned?
  - discovered that clearing the DNS cache forces Windows to fetch DNS information each time it looks up a name. this command must be run from a command prompt
