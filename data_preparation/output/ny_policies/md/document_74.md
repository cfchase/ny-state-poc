|-------------|---------------------|--------------------------------------------|
| Algorithm   | Minimum Key  Length | Use Case                                   |
| AES         | 128                 | Data Encryption                            |
| RSA         | 2048                | Digital Signatures  Public Key  Encryption |
| ECDSA       | 256                 | Digital Signature  Public Key  Encryption  |
| SHA         | 256                 | Hashing                                    |
| HMAC SHA  1 | 112                 | Keyed-Hash  Message  Authentication Code   |

All government agencies that use cryptographic-based systems to protect Personal, Private or Sensitive Information (PPSI), need to have a minimum level of assurance that the product's stated security claim is valid.

On July 17, 1995, the National Institute of Standards and Technology (NIST) established the Cryptographic Module Validation Program (CMVP) that validates cryptographic modules to Federal Information Processing Standards (FIPS) cryptography-based standards.

Historically, over 48% of cryptographic modules that have undergone FIPS validation had security flaws that were corrected during testing. In other words, without validation, users would have had only a 50-50 chance of buying correctly implemented cryptography.

The list of FIPS validated cryptographic modules can be found on the NIST web site at http://csrc.nist.gov/groups/STM/cmvp/validation.html. The list can be searched by vendor or by year of validation.

It is important to note that the items on this list are cryptographic modules which may either be an embedded component of a product or application, or a complete product in and of itself. In addition, it is possible that vendors who are not found on this list might incorporate a validated cryptographic module from this list into their own products and components.