The risk assessments must be periodically reviewed and updated as necessary whenever the underlying risk assessment is modified or whenever significant changes are made to the system or application.

## **5. Select, Document, and Test Security Controls**

Appropriate security controls must be implemented by SEs to mitigate risks that are not avoided, transferred, or accepted. Security controls must be justified and documented based on the risk assessments, threat assessments, and analysis of the cost of implementing a potential security control relative to the decrease in risk afforded by implementing the control.

Documentation of controls must be sufficiently detailed to enable verification of all systems and applications and the adherence to all federal compliance requirements such as FISMA, HIPAA, IRS Publication 1075, FERPA, etc.

Residual risk must be documented and maintained at acceptable levels by the SE. After mitigating controls have been implemented, a formal risk acceptance, with SE executive management sign-off, must be performed for all remaining medium and high risks.

All controls will be thoroughly tested and re-tested in pre-production environments that are identical, in as many ways as feasibly possible, to the corresponding production environment. This includes the hardware, software, system configurations, controls, and any other customizations.

Security control requirements must be periodically reviewed and updated as necessary whenever the system, application, or the underlying risk assessment is modified.

## **6. Create Test Data**

A process for the development of significant test data must be created and documented by SEs for all systems and applications. A test process must be available for applications to perform security and regression testing (e.g., vulnerability scanning, static code analysis, red team/penetration testing).

Confidential production data should not be used for testing purposes. If production data is used, SEs must assess the risk of use and comply with all applicable federal, state, and external policies and standards regarding the protection and disposal of production data.

Associated Standards: NYS-S13-002: Secure Coding Standard; NYS-S14-005: