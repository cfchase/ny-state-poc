## **4.2.8 Multi-Factor (MF) Cryptographic Device**

A MF cryptographic device is something you have, and it must be unlocked by either something you know or something you are. It is a hardware device that contains a protected cryptographic key that must be unlocked through a second authentication factor.

Authentication is accomplished by proving possession of the device and control of the key. The token is highly dependent on the specific cryptographic device and protocol, but it is generally some type of signed message. For example, in Transport Layer Services (TLS), there is a "certificate verify" message. An example would be an ATM card.

Authenticator Requirements - Cryptographic module shall be FIPS 140-3 validated, Level 2 or higher; with the token itself meeting physical security at FIPS 140-3 Level 3 or higher. This means the token is tamper proof; it can't be broken open to reverse engineer or get a seed value, etc. Products validated under subsequent versions of FIPS 140 are also acceptable.

Entry of a password, PIN, or biometric is required to activate the authentication key. The export of authentication keys is not allowed.

Verifier Requirements - Verifier generated token input (e.g., a nonce or challenge) has at least 64 bits of entropy.

## **4.3 Token Renewal/Re-issuance**

Some token types support the process of renewal, while some support re-issuance. Depending on the assurance level, the user will need to re-establish their identity with the CSP if the token has expired or prove possession of the unexpired token before renewal or re-issuance occurs. Refer to the NYS-S20-001 Digital Identity Standard for additional information.

## **$^{ }$5.0 Compliance**

This standard shall take effect upon publication. Compliance is required with all enterprise policies and standards. ITS may amend its policies and standards at any time; compliance with amended policies and standards is required.

If compliance with this standard is not feasible or technically possible, or if deviation from this standard is necessary to support a business function, SEs shall request an exception through the Chief Information Security Office exception process.

## **6.0 Definitions of Key Terms**

Except for terms defined in this standard, all terms shall have the meanings found in http://www.its.ny.gov/glossary.

## **7.0 Contact Information**

Submit all inquiries and requests for future enhancements to the policy owner at:

Chief Information Security Office Reference: NYS-S14-006 NYS Office of Information Technology Services 1220 Washington Avenue, Building 5 Albany, NY 12226 Telephone: (518) 242-

**CISO@its**ny.gov

5200 Email:

Statewide technology policies, standards, and guidelines may be found at the following website: Policies | Office of Information Technology Services (ny.gov)

## **8.0 Revision History**

This standard shall be subject to periodic review to ensure relevancy.