|-|-|
| Adds the requirement that the assertion be encrypted using approved  cryptography. The RP is the only party that can decrypt it. This provides  strong assurance over the confidentiality, and therefore privacy, of the  assertion. FAL2 additionally requires that the assertion (e.g., the OpenID  Connect ID Token or SAML Assertion) be encrypted to a public key  representing the RP in question. | FAL2 |
| Requires the individual to present proof of possession of a cryptographic  key referenced in the assertion in addition to the assertion artifact itself. The  assertion is signed by the IdP and encrypted to the RP using approved  cryptography. | FAL3 |

Appendix E outlines the process used by a SE to examine the data within its system and identify the risks of improperly validated access or potential data exposure. By understanding these risks, the SE is better able to determine the required federated level of assurance.

## **5.0 Compliance**

This policy shall take effect upon publication. Compliance is required with all enterprise policies and standards. ITS may amend its policies and standards at any time; compliance with amended policies and standards is required.

If compliance with this policy is not feasible or technically possible, or if deviation from this policy is necessary to support a business function, SEs shall request an exception through the Chief Information Security Office exception process.

## **6.0 Definitions of Key Terms**

Except for terms defined in this policy, all terms shall have the meanings found in http://www.its.ny.gov/glossary.

## **7.0 Contact Information**

Submit all inquiries and requests for future enhancements to the policy owner at:

Chief Information Security Office Reference: NYS-P20-001 NYS Office of Information Technology Services 1220 Washington Avenue, Building 5 Albany, NY 12226

**CISO@its**ny.gov

Telephone: (518) 242-5200 Email:

Statewide technology policies, standards, and guidelines may be found at the following website: http://www.its.ny.gov/tables/technologypolicyindex

## **8.0 Revision History**

This policy document should be reviewed consistent with the requirements set forth in NYS-P08-002 Authority to Establish State Enterprise Information Technology (IT) Policy, Standards and Guidelines.

|-|-|-|
| Date | Description of Change | Reviewer |
| Original Policy Release | Thomas Smith,  Chief Information  Security Officer | 10/05/2010 |
| Reformatted and updated to reflect current  CIO, agency name, logo and style | Thomas Smith,  Chief Information  Security Officer | 09/12/2012 |
| 10/18/2013  Full revision | | Thomas Smith,  Chief Information  Security Officer |
| 09/19/2014  Removed references to EIAM service and  EIAM Program Office; moved procedures to  Appendix B; removed Mitigation Request and | Deborah A.  Chief  Information | Proposal - replaced by exception request form  Snyder, Acting |
| Update of contact information and rebranding | Security Officer  Deborah A.  Snyder, Deputy  Chief  Information | 02/16/2017 |
| Content updated based on new NIST SP  800- 63-3 Digital Identity Guidelines.  Renamed policy from Identity Assurance  (NYS-P10-006) | Security  Officer  Karen Sorady,  Acting Chief  Information  Security Officer | 07/16/2020 |
| to Digital Identity (NYS-P20-001).  Updated Scope language | Karen Sorady,  Acting Chief  Information  Security Officer | 05/20/2021 |

|-|-|-|
| Date | Description of Change | Reviewer |
| 01/08/2024 | Update language, added Appendix A, add | Chris DeSain, |
| 01/08/2024 | detail to IAL3 regarding remote supervised  proofing | Chief Information  Security Officer |

## **9.0 Related Documents**

NYS-P03-002 Information Security Policy

NYS-S14-007 Encryption Standard

NYS-S20-001 Digital Identity Standard

NYS-S14-001 Information Security Risk Management Standard

NYS-S14-013 Account Management/Access Control Standard

NYS-S14-006 Authentication Tokens Standard

National Institute of Standards and Technology (NIST) Special Publication 800-63-3, Digital Identity Guidelines

## **APPENDIX A - Identity Proofing 4**

Identity proofing is the process by which a Credential Service Provider (CSP) collects and verifies information about a person for the purpose of issuing credentials to that person, as illustrated.

## **APPENDIX B - Potential Impacts for each Category of Harm4**

This section defines the three levels of impact for each category of harm. Each assurance level, IAL, AAL, and FAL (if accepting or asserting a federated identity) shall be evaluated separately.

Note: If an error in the identity system causes no measurable consequences for a category, there is no impact. For assessment purposes a category with no impact is marked with "N/A" or Not Applicable.