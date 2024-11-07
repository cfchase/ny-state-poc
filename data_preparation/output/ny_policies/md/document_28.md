Scans must be performed within the system development life cycle ( see NYS-S13-001 SSDLC Standard) while in pre-production environments, when deployed to the production environment, and periodically thereafter as specified below:

**4**2.1 Pre-production scans occur prior to the move of the system, source code, or web application to the production environment:

· All systems must undergo an authenticated internal infrastructure scan, where technically feasible, before being deployed to the production environment. Any infrastructure vulnerability discovered must be remediated, determined to be a false positive, or deemed an insignificant risk by the SE ISO/designated security representative prior to the system being deployed for intended use.

· When source code is available, scan of the source code should be conducted throughout the development process. Applications must undergo source code scanning before the application moves to production and between environments if there has been a change to source code.

· Web applications that require authentication must undergo an authenticated scan before being deployed to the production environment or into an environment that is externally accessible. When authentication is required to access the application, scans must run with authenticated access at each access level (e.g., user, admin) supported by the application, except where limitations in the scanning tool and/or application prevent authenticated scanning, in order to determine if vulnerabilities exist in the different functionality of the application accessible by each access level. Any web application vulnerability discovered must be remediated or determined to be a false positive or insignificant risk by the SE ISO/designated security representative prior to the web application being placed into the production environment.

· Any system, source code, or web application deployed to its production environment with un-remediated vulnerabilities must have a formal remediation plan and the documented approval of the SE executive responsible for risk management, or their designee.

**4**2.2 Implementation scans occur the first time a system or web application is moved to its production environment: