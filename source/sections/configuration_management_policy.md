# Configuration Management Policy

Textractor standardizes configuration management through the use of documentation to all changes to production systems and networks as a part of our Disaster Recovery plan and process.

## Applicable Standards from the HIPAA Security Rule

* 164.310(a)(2)(iii) Access Control & Validation Procedures

## Configuration Management

1. OSSEC is used to scan systems every 2 hours and on reboot. These scans capture file system changes and also unauthorized or malicious software.
2. No systems are deployed into Textractor environments without approval of the Textractor CTO.
3. All changes to production systems, network devices, and firewalls are approved by the Textractor CTO before they are implemented to assure they comply with business and security requirements. Additionally, all changes are tested before they are implemented in production. All changes are documented using Github issues. Implementation of approved changes are only performed by authorized personnel.
4. An up-to-date inventory of systems is maintained using Google spreadsheets and architecture diagrams hosted on Google Apps. All systems are categorized as production and utility to differentiate based on criticality.
5. All software and systems are tested using unit tests and end to end tests.
6. All committed code is reviewed using pull requests (on Github) to assure software code quality and proactively detect potential security issues in development.
7. Textractor utilizes development and staging environments that mirror production to assure proper function.
8. Textractor also deploys environments locally using Vagrant to assure functionality before moving to staging or production.
9. Textractor schedules production deployments every four weeks.
10. All formal change requests require unique ID and authentication.
11. Antivirus software is run on all production hosts for anti-virus protection. Hosts are scanned daily for malicious binaries in critical system paths. The malware signature database is checked hourly and automatically updated if new signatures are available.
