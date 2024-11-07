Verifier Requirements - Verifier generated token input (e.g., a nonce or challenge) has at least 64 bits of entropy.

## **4.2.7 Multi-Factor (MF) One-Time Password (OTP) Device**

A MF OTP device is something you have, and it must be unlocked by either something you know or something you are. It is a hardware and software-based device that generates OTPs for use in authentication and which must be unlocked through a second factor of authentication. The second factor of authentication may be achieved through an integral entry pad, an integral biometric (e.g., fingerprint) reader or a direct computer interface (e.g., USB port).

The OTP is typically displayed on the device and manually input to the verifier as a password, although direct electronic input from the device to a computer is also allowed.

An example would be a key fob token in combination with a PIN. A user attempts to log into a website and provides a user-defined PIN (established when the token was assigned) and a token generated code. The combination of the PIN and token generated code is referred to as a passcode.

Authenticator Requirements - The cryptographic module shall be validated at FIPS 140-3 Level 2 or higher with the token itself meeting physical security at FIPS 140-3 Level 3 or higher. This means the token is tamper proof; it can't be broken open to reverse engineer or get a seed value, etc. Products validated under subsequent versions of FIPS 140 are also acceptable. Refer to the NYS-S14-007 Encryption Standard for additional information.

The OTP must be generated using an approved block cipher or hash function to combine a symmetric key stored on a personal hardware device with a nonce to generate an OTP. The nonce may be a date and time or a counter generated on the device. Each authentication shall require entry of a password or other activation data through an integrated input mechanism.

Verifier Requirements - The OTP shall have a limited lifetime, with a maximum of 2 minutes.