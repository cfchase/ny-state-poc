**2** automated inventory system

**3** manual record keeping

## **4.3 Key Management**

The SE must ensure that a secure environment is established to protect the cryptographic keys used to encrypt and decrypt information.

· Keys must be securely distributed and stored.

· Unencrypted keys must not be stored with the data that they encrypt.

Access to keys must be restricted to only individuals who have a business need to access the keys.

Keys will be protected with an authentication token that conforms to the identified assurance level as per the NYS-P20-001 Digital Identity Policy.

Compromise of a cryptographic key would cause all information encrypted with that key to be considered unencrypted. If a compromise has been discovered, a new key must be generated and used to continue protection of the encrypted information. Specific circumstances should be evaluated to determine if a breach notification is required.

Encryption keys and their associated software products must be maintained for the life of the archived data that was encrypted with that product.

## **5.0 Compliance**

This standard shall take effect upon publication. Compliance is expected with all enterprise policies and standards. ITS may amend its policies and standards at any time; compliance with amended policies and standards is expected.

If compliance with this standard is not feasible or technically possible, or if deviation from this policy is necessary to support a business function, State Entities shall request an exception through the Chief Information Security Office exception process.

## **6.0 Definitions of Key Terms**

Except for terms defined in this policy, all terms shall have the meanings found in http://www.its.ny.gov/glossary.

## **7.0 Contact Information**

Submit all inquiries and requests for future enhancements to the policy owner at:

Chief Information Security Office Reference: NYS-S14-007 NYS Office of Information Technology Services 1220 Washington Avenue, Building 5 Albany, NY 12226 Telephone: (518) 242-5200

**Email: CISO@its**ny.gov

Statewide technology policies, standards, and guidelines may be found at the following website: http://www.its.ny.gov/tables/technologypolicyindex

## **8.0 Revision History**

This policy document should be reviewed consistent with the requirements set forth in NYS-P09-003 Process for Establishing Information Technology Policies, Standards, and Guidelines

|-|-|-|
| Date | Description of Change | Reviewer |
| Original Standard Release;  replaces  CSCIC/OCS Cryptographic Controls (S10-006)  and Key Management Standards (S10-007)  and ITS Encryption Standard (ITS-S07-001) | Thomas Smith,  Chief Information  Security Officer | 03/21/2014 |
| Allow for UEFI Secure Boot in place of pre- boot authentication. Require TPM for pre-boot  authentication. Minor wording clarifications.  Updated key length for ECDSA and SHA from  224 to 256 in Appendix A. | Deborah A.  Snyder, Deputy  Chief Information  Security Officer | 03/20/2015 |
| Require all websites and web services within  scope to be accessible through a secure  connection (HTTPS). Revised TLS 1.1 to 1.2 | Deborah A.  Snyder, Deputy  Chief Information  Security Officer | 03/15/2016 |
| Update to Scope, contact information and  rebranding | Deborah A.  Snyder, Deputy  Chief Information  Security Officer | 02/15/2017 |

|-|-|-|
| 06/26/2017 | Add Appendix C - Minimum Browser Support | Deborah A.  Snyder, Acting  Chief Information  Security Officer |
| 07/16/2020 | Update revised Scope and Authority and  update links from Identity Assurance to Digital  Identity | Karen Sorady,  Chief Information  Security Officer |
| 05/20/2021 | Updated Scope language | Karen Sorady,  Chief Information  Security Officer |

## **9.0 Related Documents**

NIST Special Publication 800-111, Guide To Storage Encryption Technologies For End User Devices

NIST Special Publication 800-131A, Transitions: Recommendation for Transitioning the Use of Cryptographic Algorithms and Key Lengths

NIST Special Publication 800-57, Part 1, Recommendation for Key Management - Part 1: General

NIST Federal Information Processing Standard (FIPS) Publication 140-3

NIST Federal Information Processing Standard (FIPS) Publication 198-1

NIST Federal Information Processing Standard (FIPS) Publication 180-4

NIST Special Publication 800-107, Revision 1, Recommendation for Applications Using Approved Hash Algorithms

## **APPENDIX A - Approved Algorithms**