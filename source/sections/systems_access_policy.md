# System Access Policy

Access to Textractor systems and application is limited for all users, including but not limited to workforce members, volunteers, business associates, contracted providers, consultants, and any other entity, is allowable only on a minimum necessary basis. All users are responsible for reporting an incident of unauthorized user or access of the organization’s information systems. These safeguards have been established to address the HIPAA Security regulations including the following:

## Applicable Standards from the HIPAA Security Rule

* 164.308a4iiC Access Establishment and Modification
* 164.308a3iiB Workforce Clearance Procedures
* 164.308a4iiB Access Authorization
* 164.312d Person or Entity Authentication
* 164.312a2i Unique User Identification
* 164.308a5iiD Password Management
* 164.312a2iii Automatic Logoff
* 164.310c Workstation Security
* 164.308a3iiC Termination Procedures

## Access Establishment and Modification

* Requests for access to Textractor Platform systems and applications is made formally to the VP of Engineering, Privacy Officer, or Security Officer.
* Access is not granted until receipt, review, and approval by the Textractor Security Officer;
* The request for access is retained for future reference.
* All access to Textractor systems and services are reviewed and updated on an bi-annual basis to assure proper authorizations are in place commensurate with job functions. The form used to conduct account review is [here](https://docs.google.com/a/Textractor.io/forms/d/1oeejMta4XLiUsdH2gTKQ-glec6DBiwPJoY9F60HmPWk/viewform).
* Any Textractor workforce member can request change of access using this [form](https://docs.google.com/a/Textractor.io/forms/d/1ySICzCyEEdNqxHHErjlJqREBijwxs9z72L-rWXrxkm0/viewform).
* Access to systems is controlled using centralized user management and authentication.
* Privileged users must first access systems using standard, unique user accounts before switching to privileged users and performing privileged tasks.
* All application to application communication using service accounts is restricted and not permitted unless absolutely needed. Automated tools are used to limit account access across applications and systems.
* Generic accounts are not allowed on Textractor systems.
* In cases of increased risk or known attempted unauthorized access, immediate steps are taken by the Security and Privacy Officer to limit access and reduce risk of unauthorized access.
* Direct system to system, system to application, and application to application authentication and authorization are limited and controlled to restrict access.

## Workforce Clearance Procedures

* The level of security assigned to a user to the organization’s information systems is based on the minimum necessary amount of data access required to carry out legitimate job responsibilities assigned to a user’s job classification and/or to a user needing access to carry out treatment, payment, or healthcare operations.
* All access requests are treated on a ‘least-access principle”.

## Access Authorization

* Role based access categories for each Textractor system and application are pre-approved by the Security Officer or VP of Engineering.

## Person or Entity Authentication

* Each workforce member has and uses a unique user ID and password that identifies him/her as the user of the information system.
* Each Customer and Partner has and uses a unique user ID and password that identifies him/her as the user of the information system.

## Unique User Identification

* Access to the Textractor Platform systems and applications is controlled by requiring unique User Login ID’s and passwords for each individual user and developer.
* Passwords are not displayed at any time and are not transmitted or stored in plain text.
* Default accounts on all production systems, including root, are disabled.
* Shared accounts are not allowed within Textractor systems or networks.

## Automatic Logoff

* Users are required to make information systems inaccessible by any other individual when unattended by the users (ex. by using a password protected screen saver or logging off the system).
* Information systems automatically log users off the systems after 10 minutes of inactivity.
* The Security Officer pre-approves exceptions to automatic log off requirements.

## Employee Termination Procedures

* The Human Resources Department (or other designated department), users, and their supervisors are required to notify the Security Officer upon completion and/or termination of access needs and facilitating completion of the “Termination Checklist".
* The Human Resources Department, users, and supervisors are required to notify the IS Help Desk to terminate a user’s access rights if there is evidence or reason to believe the following (these incidents are also reported on an incident report and is filed with the Privacy Officer):
	* The user has been using their access rights inappropriately;
	* A user’s password has been compromised (a new password may be provided to the user if the user is not identified as the individual compromising the original password);
	* An unauthorized individual is utilizing a user’s User Login ID and password (a new password may be provided to the user if the user is not identified as providing the unauthorized individual with the User Login ID and password).
* The Security Officer will terminate users’ access rights immediately upon notification.
* The Security Officer audits and may terminate access of users that have not logged into organization’s information systems/applications for an extended period of time.

## Paper Records

Textractor does not use paper records for any sensitive information. Use of paper for recording and storing sensitive data is against Textractor policies.

## Password Management

* User IDs and passwords are used to control access to Textractor systems and may not be disclosed to anyone for any reason.
* Users may not allow anyone, for any reason, to have access to any information system using another user’s unique user ID and password.
* All system and application passwords are hashed by concatenating the user's password and a random 256-bit salt value, generated on a per-user basis, and then applying SHA-256 to the value to create a password hash. The password hash and the salt are then stored in the backend database and are used for password validation on future user authentication attempts.
* Each information system automatically requires users to change passwords at a pre-determined interval as determined by the organization, based on the criticality and sensitivity of the ePHI contained within the network, system, application, and/or database.
* Passwords are inactivated immediately upon an employee’s termination (refer to the termination procedures in this policy).
* All default system, application, and Partner passwords are changed before deployment to production.
* Upon initial login, users must change any passwords that were automatically generated for them.
* All passwords used in configuration scripts are secured and encrypted.
* If a user believes their user ID has been compromised, they are required to immediately report the incident to the Security Office.