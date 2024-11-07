NIST Special Publication 800-92, Guide to Computer Security Log Management NIST SP 800-92 Rev. 1 (Initial Public Draft), Cybersecurity Log Management Planning Guide

## **Appendix A: Security Events to Log**

Security events that must be logged for all systems include but are not limited to:

**1** Successful and unsuccessful authentication events including but not limited to:

account or user-ID;

· system logon/logoff;

· change of password;

· an indication of success or failure of the event;

the type of event;

the date and time of the event; and

· identification of the source of the event such as location, IP addresses terminal ID, or other means of identification.

**2** Successful and unsuccessful privileged operations including but not limited to:

· system starts and stops;

· use of system privileged accounts;

hardware attachments and detachments;

· security events - account/group management and policy changes.

· system and network management alerts and errors messages; and

**3** Successful and unsuccessful access to security log files including but not limited to:

the type of event;

· account or user-ID;

· an indication of success or failure of the event;

· identification of the source of the event such as location, IP address, terminal ID, or other means of identification.

the date and time of the event; and

**4** Unsuccessful resource access events will be logged to include at a minimum:

· the type of event;

· account or user-ID;

an indication of the event;

the resource; and

· the date and time of the event;

· identification of the source of the event such as location, IP addresses terminal ID, or other means of identification.

**5** For systems identified as critical based on an SE risk assessment or systems that have not yet been classified, in addition to the above, successful resource access events will be logged to include at a minimum:

the type of event;

· account or user-ID;

· an indication of the event;

· the resource; and

the date and time of the event;

identification of the source of the event such as location, IP addresses terminal ID, or other means of identification.

Most web servers offer the option to store log files in either the common log format or an extended log format. The extended log format records more information than the common log file format. When technically feasible, web servers must use the extended log format. The extended log format adds valuable logging information to your log file so you can determine where messages are coming from, who is sending the message, and adds information to the log file that would be necessary to trace an attack.