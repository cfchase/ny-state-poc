Examples include key fob tokens, or software-based OTP generator. A user attempts to log into a website and provides a token generated code or OTP.

Authenticator Requirements - An approved block cipher or hash function to combine a symmetric key stored on the device with a nonce to generate an OTP must be used. The nonce may be a date and time or a counter generated on the device.

Verifier Requirements - The OTP shall have a limited lifetime, with a maximum of 2 minutes. The cryptographic module performing the verifier functions shall be validated at FIPS 140-3 Level 1 or higher. Products validated under subsequent versions of FIPS 140 are also acceptable.

## **4.2.6 Multi-Factor (MF) Software Cryptographic Token**

A MF software cryptographic token is something you have, and it must be unlocked by either something you know or something you are. It is a cryptographic key that is stored on a disk or some other "soft" media and must be unlocked through a second factor of authentication separate from the authentication factor used to access the disk or other "soft" media.

Authentication is accomplished by proving possession and control of the key. The token is highly dependent on the specific cryptographic protocol, but it is generally some type of signed message.

An example would be a private cryptographic certificate that is unlocked by a passphrase that is separate from that which unlocks the device on which the certificate is stored. The certificate deployed on the user's workstation (something you have) in combination with a passphrase (something you know) provides multi-factor authentication. The password to access the device cannot automatically unlock the certificate.

Authenticator Requirements - The cryptographic module shall be validated at FIPS 140-3 Level 1 or higher. Products validated under subsequent versions of FIPS 140 are also acceptable. Each authentication shall require entry of the password or other activation data and the unencrypted copy of the authentication key shall be erased after each authentication.