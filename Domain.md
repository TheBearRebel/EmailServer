# Configuring Domain settings
Now that domain name has been purchased we need to set it up and configure it.
## Records
  - DNS record (Zone Files): Are intructions in a DNS Server that provide information about the domain like its IP Address and on how to handle request to that domain
  - A Record: The record that holds the IP address of a domain (IPv4)
  - AAAA Record: The record that contains the IPV6 address for a domain (IPv6)
  - CNAME Record: Forwards one domain or subdomain to another domain
  - MX Record: Directs mail to email server
  - TXT Record: Lets an admin store text notes in the record. Used for email security.
  - NS Record: Store the name server for a DNS entry
  - SOA Record: Stores admin information about a domain
  - PTR Record: Provides a domain name in reverse-lookups.
## How to use the Records  
  - Type: What kind of record is being used 
  - Name: This is where the domain and subdomain names go (like @, www, mail)
  - Data: Destication of the record 
  - TTL (Time to Live): How long before the record is refreshed in secords
## What to put in the Records
  - A record would be the IPv4 public ip address where the email server is located.
  - AAAA record would be the IPv6 public ip address where the email server is located if ypu have one.
  - CNAME Record 
