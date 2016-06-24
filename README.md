# DevOps Job Interview Questions!

## Table of Contents

  1. [General Questions](#general-questions)
  1. [Configuration Management Questions](#configuration-management-questions)
  1. [Network Questions](#network-questions)
  1. [Linux Questions](#linux-questions)
  1. [Windows Questions](#windows-questions)
  1. [Security Questions](#security-questions)
  1. [Cloud Questions](#cloud-questions)
  1. [Architecture Questions](#architecture-questions)
  1. [CI Questions](#ci-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

#### General Questions

* Describe the most challenging situation that you were faced with and how you overcame the challenge?

### Configuration Management Questions

* Do you have any experience with a CMS (configuration management system)?
* How long have you used a CMS for?
* Have you used it in production or Test/Dev?
* How large was the environment?

#### Network Questions

* What is a PTR in DNS?

> You can think of the PTR record as an opposite of the A record. While the A record points a domain name to an IP address, the PTR record resolves the IP address to a domain/hostname. PTR records are used for the reverse DNS (Domain Name System) lookup.

* What is a MX record in DNS?

> A mail exchanger record (MX record) is a type of resource record in the Domain Name System that specifies a mail server responsible for accepting email messages on behalf of a recipient's domain, and a preference value used to prioritize mail delivery if multiple mail servers are available.

* How does a CDN chooses the closest host to serve a client?

> When the browser makes a DNS request for a domain name that is handled by a CDN, there is a slightly different process than with small, one-IP sites. The server handling DNS requests for the domain name looks at the incoming request to determine the best set of servers to handle it. At it’s simplest, the DNS server does a geographic lookup based on the DNS resolver’s IP address and then returns an IP address for an edge server that is physically closest to that area. So if I’m making a request and the DNS resolver I’m routed to is Virginia, I’ll be given an IP address for a server on the East coast; if I make the same request through a DNS resolver in California, I’ll be given an IP address for a server on the West coast. You may not end up with a DNS resolver in the same geographic location from where you’re making the request.

* When would you ever not want to use a CDN?

#### Linux Questions

* What are RAID 0, 1, 5, 6 and 10?
* Advantages/disadvantages between each raid scheme?
* What is an alternative to init.d in Linux?
* How do you view running processes in Linux?
* How do you check DNS records in Linux?

#### Windows Questions

* Do you have any experience with Active Directory?
* Have you ever integrated Active Directory with any applications?
* Describe what an OU is within Active Directory.

> An organizational unit (OU) is a subdivision within an Active Directory into which you can place users, groups, computers, and other organizational units. You can create organizational units to mirror your organization's functional or business structure.

#### Security Questions

* What is the difference between authorization and authentication?
* What is two-factor authentication?

#### Cloud Questions

* What is your experience with any Cloud platform? (AWS/Openstack/Azure)
* Have you used a cloud environment in a production environment?
* What is a logging strategy for servers or containers with ephemeral storage?
* Where should you look when trying to reduce cloud costs without reducing capacity?

#### Architecture Questions

* What are the differences between relational databases and noSQL databases?
* What advantages do NoSQL databases like MongoDB have compared to MySQL?
* How would you manage API versions?
* How would you reduce load time of a dynamic website?
* How would you reduce load time of a static website?

#### CI Questions

* Do you have any expreience with CI tools? Which ones?
* Describe your experience implementing continuous deployment in a production environment

#### Coding Questions

* Describe a dev/test/production workflow using GIT

#### Fun Questions

* What is your favorite side project?
* If you could learn any technology now, what would be?
* How do you keep up with current technology trends?