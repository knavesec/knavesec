### whoami

Compilation of projects from my spare time. Built for pentests, red teams, and analysis. 

Tools generally released with accompanying blog posts, can be found here: [https://whynotsecurity.com/tags/#knavesec](https://whynotsecurity.com/tags/#knavesec)


Tool list:

* [CredMaster](https://github.com/knavesec/CredMaster) ([Blog1](https://whynotsecurity.com/blog/credmaster/)) ([Blog2](https://whynotsecurity.com/blog/credmaster2/)) - Password spraying tool using FireProx AWS APIs to rotate request IP on every attempt. Full opsec considerations applied to not leak information
* [Max](https://github.com/knavesec/Max) ([Blog1](https://whynotsecurity.com/blog/max/)) ([Blog2](https://whynotsecurity.com/blog/max2/)) ([Blog3](https://whynotsecurity.com/blog/max3/))- BloodHound utility tool for data import/export, Domain Password Audit Tool (DPAT), analytics
* [External Email Warning Bypass](https://gist.github.com/knavesec/570ddd0cd7e00d02e87121576a677b59) ([Blog](https://whynotsecurity.com/blog/external-email-warning-bypass/)) - POC to obfuscate "external email warning" banners on phishing emails via CSS injection
* [EyeWitnessTheFitness](https://github.com/knavesec/EyeWitnessTheFitness) ([Blog](https://whynotsecurity.com/blog/eyewitnessthefitness/)) - Generates a single FireProx API to be used for multiple pass through API hosts. Nice to be used for large EyeWitness files without generating a unique FireProx API per host
* [DPS](https://github.com/knavesec/DPS) - Distributed port scanning tool, generates high number of AWS Lambdas with unique IPs to scan hosts. Configurable to sleep between scan hosts to bypass scan prevention
* [Reverse-DNS-Info](https://github.com/knavesec/Reverse-DNS-Info) - Reverse search WHOIS records by keywords to enumerate potential alternate client root domains
* [o365fedenum](https://github.com/knavesec/o365fedenum) ([Blog](https://whynotsecurity.com/blog/o365fedenum/))- Office365 Federated user enumeration script, based off correlated HTTP response analysis 

Conference Talks: 

* [RMISC 2020 - BloodHound Use and Abuse](https://github.com/knavesec/Conference-Talks/tree/main/2021-RMISC-Bloodhound-Use-And-Abuse) - Taking BloodHound from beginner to advanced with both high level actions and in depth details
* [Way West Hackin' Fest 2022 - Office365 Federated User Enumeration](https://github.com/knavesec/Conference-Talks/tree/main/2022-WayWestHF-Office365-Federated-UserEnum) - Enumerating Office365 users via a new dynamic response technique
