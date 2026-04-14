# DNS Threat Detection Analysis

## Objective
To identify and analyze suspicious DNS activity using Wireshark.

## Tools Used
- Wireshark
- Kali Linux

## Activity Performed
- Captured DNS traffic
- Generated normal and abnormal domain queries
- Observed DNS responses including failures

## Observations
- google.com resolved successfully (normal traffic)
- random-data-api.com returned SERVFAIL
- asd123fake-domain-test.com returned NXDOMAIN (non-existent domain)

## Threat Detection Insight
- Failed DNS lookups can indicate suspicious or abnormal activity
- Unknown domains may suggest malware communication attempts
- DNS monitoring is critical in SOC environments

## Key Learning
- Ability to differentiate normal vs suspicious DNS traffic
- Understanding DNS-based threat indicators
- Applying SOC analyst mindset in real-time analysis
