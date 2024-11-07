When selecting a product from a vendor, verify that the application or product that is being offered is either a validated cryptographic module itself (e.g., full disk encryption solution, SmartCard) or the application or product uses an embedded validated cryptographic module (toolkit, etc.) by confirming the module's validation certificate number. Ask the vendor to supply a signed letter stating their application, product or module is a validated module or incorporates a validated module which provides all the cryptographic services in the solution and references the module's validation certificate number. This number can be checked against the CMVP validation list. If the information does not agree, the vendor is not offering a validated solution.

Be aware that vendors may sometimes make invalid conformance claims such as:

· The module has been designed for compliance to FIPS 140-3.

· The module has been pre-validated and is on the CMVP pre-validation list.

· The module will be submitted for testing.

· The module has been independently reviewed and tested to comply with FIPS 140-3.

· The module meets all the requirements of FIPS 140-3.

· The module implements FIPS Approved algorithms; including having algorithm certificates.

· The module follows the guidelines detailed in FIPS 140-3.

A cryptographic module does not meet the requirements or conform to the FIPS standard unless a reference can be made to the validation certificate number.

Users must also be cognizant of the version number of the validated cryptographic module and, for software products, the operating systems that it has been tested on. Only the version numbers listed in the Cryptographic Module column of the CMVP list are FIPS validated and only when run on the operating systems listed in the Level or Description column.

## **FIPS Mode**

Many validated products have the capability to operate in FIPS mode, as well as non-FIPS mode. Operating in FIPS mode will ensure that the module uses only FIPS approved encryption algorithms.