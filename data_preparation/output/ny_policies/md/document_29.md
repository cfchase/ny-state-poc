· Systems must be scanned immediately upon being placed into the production environment with an authenticated internal infrastructure scan, where technically feasible. If the system is accessible from the Internet or an external network, then the system must be scanned with an external infrastructure scan.

· Web applications must be scanned within the first month of being placed into the production environment. An authenticated web application scan is required if feasible, but at minimum an unauthenticated web application scan is required. Sensitivity and criticality of the application must be considered when determining the schedule for the initial implementation scan.

**4**2.3 Recurring Scans: After the initial scan in the production environment, the frequency of scans must occur according to the system or application's risk rating (see Table 2).

· When performing internal infrastructure scans on systems built using a shared image, such as workstations, scans may be run on a sampling of systems, but the sample set must vary from scan to scan.

· Web applications in production are required to undergo recurring scans. At minimum, web applications in production are required to undergo recurring unauthenticated application scans.

· All vulnerabilities found during scans must be addressed as per the remediation section below.

## **4.3 Determine Risk Rating and Frequency of Scans**

The risk that vulnerabilities pose to systems and applications is based on the likelihood of a vulnerability being exploited and the impact if the confidentiality, integrity, or availability of the SE's information assets were compromised. The likelihood of a vulnerability being exploited increases in direct relation to the systems or application's accessibility from other systems.

The impact of a vulnerability to a SE's information asset is based on that asset's information classification ( see NYS-S14-002 Information Classification Standard). The SE must consider the impact (i.e., high, moderate, or low) of a compromise to the confidentiality, integrity, and availability of that asset. The highest impact level identified must be used when determining the overall risk rating, per the table below.

|-|-|-|-|
| Table 2: RISK RATING | Table 2: RISK RATING | Table 2: RISK RATING | Table 2: RISK RATING |
| | Exposure | Exposure | Exposure |
| Impact  (Confidentiality,  Integrity,  Availability) | Systems with no  network  connectivity to  production data | Systems with network  connectivity to  production data (not  Internet facing) | System that is  publicly  available from  the Internet |
| High | Moderate | High | High |
| Moderate | Low | Moderate | High |
| Low | Low | Low | High |

The minimum frequency of scans is dependent on the risk rating. All systems and applications that are publicly available from the Internet are considered High risk regardless of their impact rating because they represent a potential entryway to an SE's internal network. Systems and applications without a risk rating must be scanned as if they had a risk rating of "High" until they are rated.

|-|-|
| TABLE 3: FREQUENCY OF SCANS | TABLE 3: FREQUENCY OF SCANS |
| Risk Rating | Frequency |
| Infrastructure scans | Infrastructure scans |

|-|-|
| High | Monthly |
| Moderate | Quarterly |
| Low | Semi-annually |
| Web Application Scans | Web Application Scans |
| High | Monthly or after significant change |
| Moderate | Quarterly |
| Low | Semi-Annually |

## **4.4 Remediation**

Vulnerabilities discovered during scans must be remediated based on the systems or application's risk rating (see Table 2) and vulnerability severity identified by the scanning tool as per the table below.