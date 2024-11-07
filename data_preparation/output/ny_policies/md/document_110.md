|-|-|
| Level | Definition |
| Provides some assurance that the claimant controls an  "authenticator" bound to the subscriber's account. AAL1  requires either single-factor (e.g., password) or multi- factor  (e.g., password + token) authentication using a wide range  of available authentication technologies. Successful  authentication requires that the individual logging in prove  possession and control of the authenticator through a  secure authentication protocol as defined in the NYS-S14- 007 Encryption Standard. | AAL1 |
| Provides high confidence that the claimant controls  authenticator(s) bound to the subscriber's account. Proof  of possession and control of two distinct authentication  factors (multi-factor) is required through secure  authentication protocol(s). Approved cryptographic  techniques, as defined in the NYS-S14-007 Encryption  Standard, are required at AAL2 and above. | AAL2 |
Caption: Table 1: Authenticator Assurance Level (AAL)




SEs must follow the Digital Identity Policy, NYS-P20-001 Digital Identity Policy, to determine the appropriate assurance level for their system. For token distribution requirements refer to the Digital Identity Standard, NYS-S20-001 Digital Identity Standard.

Each assurance level requires different authentication tokens which incorporate one or more authentication factors (i.e., something you know, something you have, and something you are). AAL1 requires a minimum of single factor authentication. AAL2 and AAL3 require multifactor authentication.

SEs must choose the appropriate token type(s) for their assurance level. Table 1 explains what token is required based on assurance level, and Table 2 shows the maximum assurance level that can be achieved with a single token type.

|-|-|-|-|
| Token Types | AAL1 | AAL2 | AAL3 |
| Memorized Secret | X | | |
| Look-up Secret | X | | |
| Out-of-Band Device | | | |
| Single-Factor One-Time Password Device  (Hardware or Software) | X | | |
| Single-Factor Cryptographic Hardware or  Software | X | | |
| Multi-Factor One-Time Password Device  (Hardware or Software) | | X | |
| Multi-Factor Cryptographic Software | | X | |
| Multi-Factor Cryptographic Hardware  Device | | | X |
Caption: Table 2: Single-token Options


SEs may use multi-token authentication (i.e., a combination of tokens) to upgrade the overall level of assurance as depicted in Table 2.

|-|-|-|
| AAL2 | AAL3 | AAL3 |
| AAL2 requires that a  combination of single-factor  authenticators must include a | AAL 3 requires the use of one of the following  combination of authenticators: | AAL 3 requires the use of one of the following  combination of authenticators: |
| Memorized Secret token, and a  possession-based second factor  from the following list: | Single-Factor  Cryptographic Device  &  Multi-factor OTP  & | Memorized Secret |
| · Look-up Secrets  Out-of-Band Device  · Single-Factor One-Time | Device (hardwareor  software) | Single-Factor  Cryptographic Device |
| Password (OTP) Device | Multi-Factor OTP  Device (hardware  only)  & | Single-Factor  Cryptographic  Software Authenticator |
| · Single-Factor  Cryptographic Software  · Single-Factor  Cryptographic Device | Single-Factor OTP  Device (hardware  only)  & | Multi-Factor  Cryptographic  Software Authenticator |
| | Single-Factor OTP  Device (hardware  only)  & | Single-Factor  Cryptographic  Software Authenticator  &  Memorized Secret |
| | Multi-Factor Cryptographic Hardware Device  (MeetsAAL3 with one device - See Table 1) | Multi-Factor Cryptographic Hardware Device  (MeetsAAL3 with one device - See Table 1) |
Caption: Table 3: Multi-token Options


## **4.2 Authentication Token Types**

## **4.2.1 Memorized Secret Token**

A memorized secret token is something you know. Memorized secret tokens are typically character or numerical strings. Examples include passwords, passphrases, and Personal Identification Numbers (PINs).

Typically, a memorized secret token is used on its own for AAL1. AAL2 and AAL3 require multi-factor authentication (MFA). When a memorized secret token is used as one of the factors in a multi-factor authentication solution, the token requirements at the associated AAL apply.

The following table addresses the minimum requirements regarding memorized secret tokens. It is important to note that other requirements dictated by regulatory bodies

$^{ }$

**(i**e., IRS for Federal Tax Information) may have different requirements. An SE's relevant compliance domains should be consulted to address the authentication needs of a system and if different from this standard, a security exception must be filed with the ITS Chief Information Security Office (CISO) per the Information Security Exception Policy, NYS-P13-001 Information Security Exception Policy.