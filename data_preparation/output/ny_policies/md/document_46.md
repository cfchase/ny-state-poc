· Have password known or accessible by at least two individuals within the SE if password is known by anyone. As such, restrictions for shared accounts, outlined below, must be followed.

**c** Service Accounts are not intended to be given to a user but are provided for a process. It is to be used in situations such as to allow a system to run jobs and services independent of user interaction.

## **Service accounts must:**

· Be restricted to specific devices and hours when possible;

· Have an assigned owner responsible for documenting and managing the account;

· Never be used interactively by a user for any purpose other than the initial system installation or, if absolutely required, for system troubleshooting or maintenance. Wherever technically feasible, administrators should leverage "switch user" or "run as" for executing processes as service accounts;

· Never be for any purpose beyond their initial scope;

· Be internally identifiable to the SE as a service account per a standardized naming convention, where possible;

· Have password known or accessible by at least two individuals within the SE if password is known by anyone. As such, restrictions for shared accounts, outlined below, must be followed.

· Not allow its password to be reset according to any standardized and/or forced schedule. However, should an employee with knowledge of said password leave the SE, that password must be changed immediately; and

**d** Shared Accounts are any accounts where more than one person knows the password or uses the same authentication token. Use of shared accounts is only allowed when there is a system or business limitation preventing use of individual accounts. These cases must be documented by the Information Owner and reviewed by the Information Security Officer (ISO) or designated security representative. Additional compensatory controls must be implemented to confirm accountability is maintained.

## **Shared accounts must:**

· Be restricted to specific devices and hours when possible;

· Have the tokens (e.g., password) reset when any of its users no longer need access, or otherwise, in accordance with the NYS-S14-006: Authentication Tokens Standard;

· Have the users log on to the system with their individual accounts and "switch user", or "run as" the shared account, wherever technically