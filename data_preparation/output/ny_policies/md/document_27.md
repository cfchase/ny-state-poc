|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|
| Type                                                                                                                                                                       | Description                           |
| Scans of the perimeter of SE networks or any  externally available hosted infrastructure to  identify potential vulnerabilities in Internet  accessible IT infrastructure. | External Infrastructure Scan          |
| Scans of IT infrastructure on SE protected  networks or any hosted infrastructure to  identify potential vulnerabilities.                                                  | Internal Infrastructure  Scan         |
| Unauthenticated scans of SE externally  facing production web applications identify  security vulnerabilities that can be found  without authenticated credentials.        | Unauthenticated Web Application  Scan |

4

|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Type                                | Description                                                                                                                                                                    |
| Authenticated Web Application  Scan | Authenticated scans of SE web applications  identify security vulnerabilities for each level  of access available within the web application.                                  |
| Application Source Code Analysis    | Scans of application source code run during  development, or when necessary for change  control, to identify problems in the code that  could cause potential vulnerabilities. |

## **4.2 Scanning**

SEs are responsible for confirming that vulnerability scans are conducted and successfully completed. SEs must use a scanning tool approved by the SE's ISO/designated security representative. Approved scanning tools must be able to provide remediation suggestions and be able to associate a severity value to each vulnerability discovered based on the relative impact of the vulnerability to the affected IT Resource.

Scan reports are classified with a minimum of moderate confidentiality and moderate integrity, per the NYS-S14-002 Information Classification Standard, and should be protected as such.

Network and system administrators must provide sufficient access and configuration information to allow the approved vulnerability scanning tool to scan all services provided by the system. No devices connected to the network shall be specifically configured to block approved vulnerability scanning from an authorized scanning tool.