**c** When required, workstations must have the ability to transfer logs to a consolidated log infrastructure.

**e** SEs must implement and document processes for the establishment, operation, and, as appropriate, integration of log management systems.

**d** Security log data must be transferred in real-time from individual hosts to a consolidated log infrastructure. Where real-time transfer is not possible, the security log data must be transferred from the individual hosts to a consolidated log infrastructure as quickly as the technology allows.

## **4.4 Log Retention and Disposal**

**b** Security log data must be securely disposed of (at both the system and the infrastructure level) in compliance with the NYS-S13-003 Sanitization/Secure Disposal Standard.

**a** Within the consolidated log infrastructure, security logs must be maintained and readily available for a minimum of one year. Based on SE requirements, including audit or legal requirements, security logs may need to be retained for a longer period of time.

**c** Systems that collect security logs, whether local or consolidated, must maintain sufficient storage space to meet the minimum requirements for both readily available and retained security logs. Storage planning must account for increases in log activity and storage requirements that could reasonably be expected to result from system issues, including security incidents.

**e** Security log integrity for consolidated log infrastructure needs to be preserved. Examples include, but are not limited to, storing security logs on write-once media or generating message digests for each log file.

**d** A process must be put in place to provide for security log preservation requests, such as a legal requirement to prevent the alteration and destruction of particular security log records (e.g., how the impacted security logs must be marked, stored, and protected).

## **4.5 Log Access and Use**

**b** Security log data must be initially analyzed as close to real time as possible.