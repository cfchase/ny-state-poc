· Validate input data from all data sources including, but not limited to, command line arguments, network interfaces, environmental variables, and user-controlled files. Proper input validation can eliminate most software vulnerabilities.

· Validate/limit output data sent to other systems such as command shells, relational databases, and COTS components to prevent misusing functionality in such systems.

· Keep the code simple as complexity will increase the likelihood that errors will be introduced.

· Use industry best practices for authentication methods and services to validate users accessing the system and all resources within the system.

· All developed code must be stored in a secure repository.

· Whenever possible, use tested and approved code for common tasks rather than create new, untested code.

· Restrict error handling from providing details of how the application works or about the system upon which it resides.

· Generate log files per system requirements and the NYS-S14-005 Security Logging Standard. These log files would be relevant to forensic analysis in the event of an incident.

· Perform code scanning per NYS-S15-002 Vulnerability Management Standard on both SE developed code, any open source components utilized by the SE, and any third-party developed code.

· Use peer reviews by team members who can draw upon their respective knowledge and experience to uncover potential issues.

· Document/comment the code for easier maintenance and remediation of any security issues.

· Remain aware of current threats and vulnerabilities to the code and respective technologies in use by the SE . Please see Exhibit 1 for some examples.

## **4.2 Security Risk Assessments**

Security risk assessments are required for use of current frameworks, common security control libraries, and common application programming interfaces (APIs). This provides a consistent approach that minimizes defects and prevents vulnerabilities from being incorporated into SE code.

Code must be checked for errors throughout development and during maintenance in order to prevent defects, or detect and remove them early, often realizing cost and schedule benefits to the SE.

## **4.3 Vulnerability Scanning**