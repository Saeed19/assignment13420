Use Case Diagrams (3)
#USE CASE 1

Title: Determine License and Vulnerability data by pulling up software project policy to compare with software project license.

Primary Actor: Manager 
Goal in Context: The Manager is able to determine license and vulnerability information from provided project information.

Stakeholders:a> Manger b.> Developer 

Manager: To get relevant OSS license and vulnerability data.
Developer: To provide the relevant file/package level information

Preconditions:

Software project policies are stored in the policy database.
Relevant file/package information is in the NIST Vulnerability database
Scanner provides proper OSS license data
License and Vulnerability database is current and up to date

Main Success Scenario: Manager receives accurate and valid license and vulnerability data for the requested project packages and receives the policy data from the policy database.

Failed End Conditions: manager receives inaccurate or invalid license and vulnerability information for the requested project packages and also does not receive the policy from the policy database.

Trigger: Manager requests project policy data to which license and vulnerability data is provided.



#USE CASE 2

Title: Retrieve and update policy for software project

Primary Actor: Manager

Goal in Context: The manager is able to pull up and update policy documents for the software project.

Stakeholders:

Manager: To provide updated software policy data.
Preconditions: Relevant file/package data is in Software Project License and Vulnerability Policy Database and is upto-date.

Main Success Scenario: The Manager recies software project policy data and updates the policy for the software project.

Failed End Conditions: 
Manager receives inaccurate / corrupt policy information from the Software Package License and Vulnerability Policy Database. 

The Nist Vulnerability database gives a licese number assciated with a vulnerable data.

Software Package License and Vulnerability Policy is not up and running.

Trigger: Corporate manager sends request to Software Project License and Vulnerability Policy Database



#USE CASE 3

Title: To find Policies for Corresponding Software Packages

Primary Actor: Manager

Goal in Context: The Manager is able to determine Open Source Software Package Policies from provided project data. 
The Corporate Manager can receive and update current policy documents.

Stakeholders:

Manager: To retrieve and update software package policy data.
Developer: To request and retrieve associated software policies.

Preconditions:

Relevant file/package data is in the Software Package License and Vulnerability Policy database
Software Package Database and NIST Vulnerability Database is uptodate.

Main Success Scenario: Manager recieves associated policy for corresponding software based on corresponding request.

Failed End Conditions: Manager recieves incorrect or corrupt software package policy.

Trigger: Corporate Manager request and recieves accurate policy data.
