A limitation with the use of OOB tokens is that if the device is infected, even if the communication occurs over a separate channel/protocol, both forms of authentication (application access and receipt of token) are compromised, and all communication is therefore un-trusted.

Verifier Requirements - The maximum time-period that an OOB token can exist is 10 minutes and it can only be used once. The verifier-generated secret must have at a minimum 20 bits of entropy; however, any authentication secret that has less than 64 bits of entropy must limit the number of failed authentication attempts to no more than 100.

## **4.2.4 Single Factor (SF) Cryptographic Device**

SF cryptographic devices are something you have. It is a hardware device that performs cryptographic operations on input provided to the device. It does not require a second factor. Generally, it is a signed message. An example would be a Secure Socket Layer/Transport Layer Services (SSL/TLS) certificate.

Authenticator Requirements - The cryptographic modules used shall be validated at FIPS 140-3, Level 1 or higher. Products validated under subsequent versions of FIPS 140 are also acceptable.

Verifier Requirements - The input (e.g., a nonce or challenge) to generate the token has at least 64 bits of entropy and shall either be unique over the authenticator's lifetime, or statistically unique using an approved random bit generator. Verification must use approved cryptography.

## **4.2.5 Single-Factor (SF) One-Time Password (OTP) Device**

SF OTP devices are something you have. This category includes hardware devices and software-based OTP generators installed on devices such as mobile phones. This device has an embedded secret that is used as the seed for generation of OTPs and does not require activation through a second factor. Authentication is accomplished by providing an acceptable OTP and thereby proving user possession and control of the device. The device is used each time authentication is required.