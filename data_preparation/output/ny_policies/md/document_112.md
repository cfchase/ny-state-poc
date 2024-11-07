Where memorized secret tokens are randomly chosen by the Credential Service Provider (CSP) or verifier (i.e., onboarding with temporary password), tokens must be at least 6 characters in length and use an approved random bit generator.

Table 5 includes optional features that can enhance user experience.

|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| Table 5: Memorized Secret Token OptionalRecommendations  Memorized  Secret  Management Standard | Description                                                                                  | Recommendation                                                                                                          |
| Password Strength  Indicator                                                                    | This is a feature (typically a  1 - 10 measurement) that  shows the strength of a  password. | Provide some form of password  strength  indication on creation.                                                        |
| Password Display                                                                                | Allow display of the password the user is entering.                                          | On Creation : Allow display  of the entire password. On Entry : Allow temporary  display of each character  as entered. |
| Password Manager                                                                                | Use of external password  management products.                                               | Encouraged especially in  cases where users need to  manage strong passwords  for multiple accounts.                    |
| Copy/Paste                                                                                      | Allowing a cut/copied password to be pasted into  a password field.                          | Only to facilitate a password  management  product usage.                                                               |
Caption: Table 5: Memorized Secret Token OptionalRecommendations


## **4.2.2 Look-Up Secrets**

A look-up secret is something you know, and a CSP/verifier has. It is either a physical or electronic record that stores a set of secrets shared between the user and CSP. An authenticator is used to look up the appropriate secret(s) needed to respond to a prompt from the verifier. An example is the use of a look-up secret as a "recovery key" for use when another authenticator is lost or malfunctions.

Look-up secrets are commonly used at AAL1. AAL2 and AAL3 require multifactor authentication. When combined with a memorized secret, the rules at AAL2 apply.

Authenticator Requirements Look-up secrets must have at least 20 bits of entropy and must be distributed over a secure channel.