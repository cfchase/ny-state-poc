· Data is being transmitted with a State public-facing website or web services (Hypertext Transfer Protocol Secure (HTTPS) must be used in lieu of Hypertext Transfer Protocol (HTTP) where technically possible). State public-facing websites must use HTTP Strict Transport Security (HSTS), automatically redirecting HTTP requests to HTTPS websites where technically possible. See minimum browser support listed in Appendix C.

Appropriate encryption methods for data in transit include, but are not limited to, Transport Layer Security (TLS) 1.2 or later, Secure Shell (SSH) 2.0 or later, Wi-Fi Protected Access (WPA) version 2 or later (with WiFi Protected Setup disabled) and encrypted Virtual Private Networks (VPNs). Components should be configured to support the strongest cipher suites possible. Ciphers that are not compliant with this standard must be disabled.

## **4.2 Data at Rest**

Encryption is required for data at rest when

· Desktops access or contain State Entity (SE) PPSI.

· Data stores (including, but not limited to, databases, file shares) contain SE PPSI.

· Mobile devices, whether State issued or third-party, access or contain any SE information.

· Portable storage devices contain any SE information.

· Electronic PPSI is transported or stored outside of a State facility.

Full disk encryption is required for all State issued laptops that access or contain SE information. Full disk encryption products must use either pre-boot authentication that

utilizes the device's Trusted Platform Module (TPM), or Unified Extensible Firmware Interface (UEFI) Secure Boot.

To mitigate attacks against encryption keys, when outside of State facilities, SE laptops and third-party laptops that access or contain SE PPSI must be powered down (i.e., shut down or hibernated) when unattended.

SEs must have a process or procedure in place for confirming devices and media have been successfully encrypted using at least one of the following, listed in preferred order:

**1** automated policy enforcement