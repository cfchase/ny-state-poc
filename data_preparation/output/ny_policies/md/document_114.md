OOB tokens are something you have. They are a combination of a physical device (e.g., cellular phone, PDA, pager, land line) and a secret that is transmitted to the device over a distinct communications channel, by a verifier for one-time use.

An example of an OOB token would be a user logging into a website and receiving a text message or phone call on their cellular phone (pre-registered with the CSP during the registration phase) with a random authenticator to be presented as part of the electronic authentication protocol. E-mail cannot be used to transmit the random authenticator for the OOB device.

Authenticator Requirements - The device must be possessed and controlled by the user and be uniquely addressable. The authenticator must establish a separate channel with the verifier to retrieve the out-of-band secret or authentication request. The secondary channel is considered out-of-band (even if it terminates on the same device) if the device does not leak information from one channel to the other without authorization from the claimant.

Use of the Public Switched Telephone Network (PSTN) is restricted unless the preregistered telephone number in use is associated with a specific physical device. Changing the pre-registered telephone number is equivalent to the binding of a new authenticator and should follow applicable requirements. Voice Over Internet Protocol (VOIP) or email cannot be used for OOB authentication.

Token Requirements - The token must be possessed and controlled by the user, uniquely addressable and must support communication over a channel/protocol that is separate from the primary channel/protocol for e-authentication.

Uniquely addressable means that the token can be addressed by a unique characteristic (e.g., phone number).

When accessing an application via a mobile device and using a virtual phone and communications management system (e.g., Google Voice), then that mobile device will not be viable as an OOB token as there is no separate channel/protocol for communication of the random authenticator.