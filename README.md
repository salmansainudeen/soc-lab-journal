# SOC Lab Journal

A public, daily log of building and defending my own detection lab on the road to SOC analyst roles.

**Stack:** Windows Server (AD DC) · Windows 10/11 client · Sysmon · Wazuh (SIEM) · Kali (attacker)

## What this is
I attack my own Active Directory lab and try to catch every attack with custom detections —
Wazuh + Sigma rules, mapped to MITRE ATT&CK. This repo is the running journal: what I built,
what broke, what I learned, one commit at a time.

## Lab architecture
![Lab architecture](screenshots/architecture.png)
<!-- TODO: add architecture.png -->

## Detections (coming in Phase 2)
| # | Attack | MITRE | Wazuh rule | Sigma rule | Status |
|---|--------|-------|-----------|-----------|--------|
| 1 | Password spraying | T1110.003 | | | planned |
| 2 | Kerberoasting | T1558.003 | | | planned |
| 3 | AS-REP roasting | T1558.004 | | | planned |
| 4 | Pass-the-Hash | T1550.002 | | | planned |
| 5 | DCSync | T1003.006 | | | planned |
| 6 | New admin user / group add | T1098 / T1136 | | | planned |
| 7 | Suspicious service install | T1569.002 | | | planned |
| 8 | Golden Ticket (stretch) | T1558.001 | | | planned |

## Journal
See [`journal/`](journal/) — one entry per working day.

---
*Salman Sainudeen · working toward SOC analyst roles (Gulf / remote)*
