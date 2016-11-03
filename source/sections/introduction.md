# Introduction

Textractor Technologies LLC ("Textractor") is committed to ensuring the confidentiality, privacy, integrity, and availability of all electronic protected health information (ePHI) it receives, maintains, processes and/or transmits on behalf of its Customers. As a provider of compliant, assisted chart abstraction software used by healthare enterprises, Textractor strives to maintain compliance, proactively address information security, mitigate risk for its Customers, and assure known breaches are completely and effectively communicated in a timely manner. The following documents address core policies used by Textractor to maintain compliance and assure the proper protections of infrastructure used to store, process, and transmit ePHI for Textractor Customers.

## Textractor Organizational Concepts

The physical infrastructure environment used by a Textractor application is hosted on premise at the customer of Textractor and is managed by the customer of Textractor.  The network components and supporting network infrastructure are hosted on premise at the customer of Textractor and managed by the customer of Textractor.

Textractor does not have physical access into the network components.  The Textractor application environment consists of Internet Information Server, Helicon Zoo, Ruby on Rails, Java, Microsfot SQL Server, Windows Server 2008 R2 64bit and OSSEC IDS services.

Within the Textractor application environment all data transmission is encrypted and all hard drives are encrypted so data at rest is also encrypted; this applies to all servers - those hosting database servers and application servers. Textractor assumes all data *may* contain ePHI, even though our Risk Assessment does not indicate this is the case, and provides appropriate protections based on that assumption.

All Textractor applications and operating systems are tested end-to-end for usability, security and impact prior to deployment to production.

## Version Control

Policies were last updated Octover 30th, 2016.
