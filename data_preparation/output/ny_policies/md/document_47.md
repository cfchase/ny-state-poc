feasible; and

· Have strictly limited permissions and access only to the system(s) required.

**e** Default Non-Privileged Accounts (guest or anonymous user) are an account for people who do not have individual accounts. An example of where this might be necessary is on a public Wi-Fi network.

This account type must:

Have limited rights and permissions;

· Be disabled until necessary;

· Only be allowed after a risk assessment;

· Be assigned a password that the user cannot change but that is changed monthly, at a minimum, by an administrator;

Have compensatory controls that include restricted network access;

· Not allow the account to be assigned for delegation by another account; and

· Have a log maintained of users to whom the password is given.

**f** Emergency Accounts are intended for short-term use and include restrictions on creation, point of origin, and usage (e.g., time of day, day of week). SEs may establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency accounts must be automatically disabled after 24 hours.

**g** Temporary Accounts are intended for short-term use and include restrictions on creation, point of origin, usage (i.e., time of day, day of week), and must have start and stop dates. SEs may establish temporary accounts as a part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation, such as for vendors, manufacturers, etc. These accounts must have strictly limited permissions and access only to the IT resources required.

## **4.3 Account Management and Access Control Functions**

Automated mechanisms must be employed to monitor the use and management of accounts. These mechanisms must allow for usage monitoring and notification of atypical account usage. Thresholds for alerting should be set based on the criticality of the system or assurance level of the account.

Staff in the appropriate account management or access control role(s) must be notified when account management activities occur, such as when accounts are no longer required, users are terminated or transferred, or system usage or need-to-know changes. The notification should be automated where technically possible.

Automated access control policies that enforce approved authorizations for IT resources must be in place within systems. These access control polices could be identity, role, or

**attribute based**

By default, no one has access unless authorized.

The IAL of a system determines the degree of certainty required. The following table describes the level of confidence associated with each IAL.

|-----|----------------------------------------------------------|
| IAL | Description                                              |
| 1   | Low or no confidence in the asserted identity's validity |
| 2   | Confidence in the asserted identity's validity           |
| 3   | High confidence in the asserted identity's validity      |

SEs must follow the NYS-P20-001: Digital Identity Policy to determine the appropriate IAL for their system. Table 1 reflects the standards for account management at each assurance level: