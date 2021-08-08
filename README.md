### whoami

Compilation of projects from my spare time. Built for pentests, red teams, and analysis. 

Tools generally released with accompanying blog posts, can be found here: [https://whynotsecurity.com/tags/#knavesec](https://whynotsecurity.com/tags/#knavesec)


Tool list:

* Max - BloodHound utility tool for data import/export, Domain Password Audit Tool (DPAT), analytics
* CredMaster - Password spraying tool using FireProx AWS APIs to rotate request IP on every attempt. Full opsec considerations applied to not leak information
* DPS - Distributed port scanning tool, generates high number of AWS Lambdas with unique IPs to scan hosts. Configurable to sleep between scan hosts to bypass scan prevention
* EyeWitnessTheFitness - Generates a single FireProx API to be used for multiple pass through API hosts. Nice to be used for large EyeWitness files without generating a unique FireProx API per host
