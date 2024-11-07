## **4.2 Authenticator Lifecycle Management**

There are various events across the lifecycle of an authenticator that affect its use. Events include binding, loss, theft, damage, unauthorized duplication, expiration, revocation and termination. The following tables will reflect the level of confidence at each Authenticator Assurance Level (AAL) that is achieved by performing the AAL Assessment Process in Appendix C in the NYS-P20-001 Digital Identity Policy.

|-----|---------------------------------------------------------------------------------------------|
| AAL | Description                                                                                 |
|     | Some assurance that the claimant controls an authenticator registered to the subscriber     |
| 2   | Confidence that the claimant controls an authenticator(s) registered to the subscriber      |
|     | High confidence that the claimant controls an authenticator(s) registered to the subscriber |

|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AAL | Standard                                                                                                                                                                                                  |
|     | Single-factor authentication                                                                                                                                                                              |
|     | Authenticator types must follow the requirements found in the NYS Authentication Tokens Standard for AAL1 .                                                                                               |
|     | Multi-factor authentication                                                                                                                                                                               |
|     | Authenticator types must follow the requirements found in the NYS Authentication Tokens Standard for AAL2.                                                                                                |
| 3   | Multi-factor authentication using a hardware-based cryptographic authenticator and an authenticator that provides verifier-impersonation resistance. The same device may fulfill both these requirements. |
| 3   | Authenticator types must follow the requirements found in the NYS Authentication Tokens Standard for AAL3.                                                                                                |

|---|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   | Credential Storage CSP stores and protects the token and credentials from compromise at a level of security commensurate with the authenticator assurance level of the issued credential as per the NYS-S14-007 Encryption Standard:.                |
|   | Passwords and shared secrets are protected using approved algorithms in accordance with the NYS-S14-007_ITS_Encryption_Standard. Access controls should also be implemented to limit access to administrators and other applications.                |
| 2 | Passwords and shared secrets are protected using approved algorithms in accordance with the NYS-S14-0oZ_ITS_Encryption_Standard. Access controls should also be implemented to limit access to administrators and other applications.                |
|   | Passwords and shared secrets must be  protectedusing a FIPS 140-2_Security Requirements_for_Cryptoqraphic_Modules, Security Level 2 or higher algorithm and should be protected by access controls limited to administrators and other applications. |