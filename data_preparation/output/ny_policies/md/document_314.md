**5** All system clocks must synchronize to a centralized reference time source set to UTC (Coordinated Universal Time) which is itself synchronized to at least three synchronized time sources.

**6** Environments and test plans must be established to validate the system works as intended prior to deployment in production.

**7** Separation of environments (e.g., development, test, quality assurance, production) is required, either logically or physically, including separate environmental identifications (e.g., desktop background, labels).

**8** Formal change control procedures for all systems must be developed, implemented, and enforced. At a minimum, any change that may affect the production environment and/or production data must be included.

**a** Databases and software (including in-house or third party developed and commercial off the shelf [COTS]):

**1** All software written for or deployed on SE systems must incorporate secure coding practices, to avoid the occurrence of common coding vulnerabilities and to be resilient to high-risk threats, before being deployed in production.

**2** Once test data is developed, it must be protected and controlled for the life of the testing in accordance with the classification of the data.

**3** Production data may be used for testing only if a business case is documented and approved in writing by the information owner and the following controls are applied:

**i** All information security measures, including but not limited to access controls, system configurations, and logging requirements for the production data are applied to the test environment and the data is deleted as soon as the testing is completed; or

**ii** sensitive data is masked or overwritten with fictional information.

**4** Where technically feasible, development software and tools must not be maintained on production systems.

**5** Where technically feasible, source code used to generate an application or software must not be stored on the production system running that application or software.

**6** Scripts must be removed from production systems, except those required for the operation and maintenance of the system.

**7** Privileged access to production systems by development staff must be restricted.