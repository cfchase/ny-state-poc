This standard applies to all "State Entities" (SE), defined as "State Government" in Executive Order 117 or "State Agencies" as defined in Section 101 of the State Technology Law. This includes employees and all third parties (such as local governments, consultants, vendors, and contractors) that use or access any IT resource for which the SE or ITS has administrative responsibility, including systems managed or hosted by third parties on behalf of the SE or ITS. While an SE may adopt a different standard, it must include the requirements set forth in this one. Where a conflict exists between this standard and an SE's standard, the more restrictive standard will take precedence.

## **4.0 Information Statement**

Security logs must be generated in information technology (IT) systems and networks. Due to the nature of the data contained in security logs, they are considered Personal, Private, or Sensitive Information (PPSI) with a minimum confidentiality and integrity classification of moderate and must be protected as such per the NYS-S14-002 Information Classification Standard.

## **4.1 Initial Log Generation**

**b** All security events (Appendix A) must be logged and must be set to capture significant levels of detail.

**a** All hosts and networking equipment must perform security log generation for all components (e.g., OS, service, application, database).

## **4.2 Log Administration**

**b** When non-revolving log storage reaches 90% capacity, a warning must be issued.

**a** All hosts and networking equipment must issue alerts on security log processing failures, such as software/hardware errors, failures in the log capturing mechanisms, and log storage capacity being reached or exceeded. All alerts must be as close to real-time as possible.

## **4.3 Log Consolidation**

**a** Security-related information from all systems, except for individual workstations, must be transferred to a consolidated log infrastructure. Systems

**b** running workstation OSs that are used for shared services, such as shared file storage or web services, must also satisfy these requirements.