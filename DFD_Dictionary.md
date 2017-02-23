# DFD Dictionary

## Entities
### Developer
Creates software and uploads to be evaluated for vulnerabilities and licenses.
### Manager
Sets and requests policies and requests vulnerabilities and licenses.

## Data Respositories
### NIST Vulnerability Database
Database of vulnerabilities maintained by the National Institute of Standards and Technology.
### Vulnerability and License Database
Database of vulnerabilities and licenses for developer submitted software.
### Policy Database
Database of software policies created by a manager.

## Processes
### Scan Software for Licenses and Vulnerabilties
Scans software for vulnerabilities and licenses by sending data to the NIST Vulnerability Database and License Scanner. Sends vulnerabilities and licenses results to the vulnerabilities and licenses database.
### License Scanner
Scans software to determine applicable licenses. Returns license results.
### Retrieve Vulnerabilities and Licenses
Retreives vulnerabilities and licenses results from the vulnerabilities and licenses database.
### Retreive Policies
Retrieves polices from the policy database.
### Set Policies
Creates or changes policies in the policy database.

## Data Flows
### Software
Created and uploaded by the developer to be evaluated for vulnerabilities and licenses.
### Software Name
The name of the software uploaded by the developer and all of the open source software used.
### Vulnerability Results
Results of searching a specific software name in the NIST Vulnerability Database.
### License Results
Results of scanning a specific software for licenses.
### Vulnerability and License Request
Request for vulnerabilities and licenses information.
### Vulnerability and License Results
Results of vulnerabilities and licenses request.
### Policy Request
Request for policy information.
### Policy Results
Results of policy request.
### Policy Change
Change to information in the policy database
