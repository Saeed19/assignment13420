#DFD Data Dictionary 

#Entities

Developer - The Corporate Person responsible for all the coding and the main software packages and preparing for the license scan.

Manager - Advising Authority to the software packages.

#Data stores -- 
(S/w – Software)

NIST Vulnerability DB - Database that contains all known vulnerabilities in the software package.

Software Project License and Vulnerability Policy - Database that stores Policy documents for the relevant, associated software packages

Software Package & License Info - Database that stores software package, license and vulnerability information.

#Processes
(S/w- Software)

1. Pull up policies for the S/w project - Process that pulls up the policy request data for corresponding software projects based on Developer’s and Manager's request.

2. Manage Software Package for License Scanning- Process that checks for open source software in the file.

3. Policy documents - Process where Manager submits or modifies policy documents.

4. License Scanner- Process that scans for any licenses that can be found in the program.

5. Consolidate Project Data: Consolidate and integrate the software project License Vulnerability Information came from the manger and developer.

6. Create policy: Process the data flow which would come came from the manager and send to policy data store to create/ Update and Upload the policy.

#Data Flows

(S/w - Software)

Software Package - Multiple code files that make up a software.

OSS Licenses - Open Source Software Licenses. These include Open source, MIT, Apache licences, etc.

Tally and Group Vulnerability with License data - Sends vulnerability data if any to be paired with the license data to store vulnerable data associated with the licenses.

Software Package Name - Name of software package/collection of files.

OSS Issues - Documented Open Source Software Package vulnerabilities.

Package License Vulnerability Data Request- Process where manager requests package for corresponding license info.

Package License Vulnerability Data Repose - Response to manager for package, license & vulnerability information.

Request S/w Project Policy - Request from manager for package policy, license & vulnerability information.

Create Policy Request- Creation of policy that is requested by the manager to be sent to the Policy DB for storage.

Acknowledgement Response of the Created policy- Acknowledgement by Policy DB that the request has been processed and stored.

Software Policies request - Software policies that correspond with their respective software projects.

Software Project Policy Request - Request associated policy information for respective software projects.

Updated Policy and confirmation post approval- Most up to date policy document approved by Manager.

Software Package License and Vulnerability Policy - Database that stores all Software Project License and Vulnerability Policy information.
