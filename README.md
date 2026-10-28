# Enterprise Security Infrastructure & SOC Monitoring

**Blue Team technical portfolio | VMware-based enterprise security lab**

This repository documents the defensive-security work I carried out in a collaborative lab project. The broader project also covered system administration and offensive security. Those activities are outside the scope of this portfolio.

## Technical reports

| Component | Work documented | Report |
| --- | --- | --- |
| **Palo Alto Networks NGFW** | Network zones, inter-zone policies, routing and NAT, management restrictions, URL filtering and data filtering tests | [Palo Alto implementation](docs/01_Palo_Alto_NGFW.md) |
| **Splunk Enterprise** | Windows and Linux log collection, Universal Forwarders, SSH log analysis, regex field extraction, monitoring dashboards and alerts | [Splunk implementation](docs/02_Splunk_SIEM.md) |
| **Wazuh** | Endpoint agents, Security Configuration Assessment, SSH monitoring, File Integrity Monitoring, VirusTotal integration and Active Response | [Wazuh implementation](docs/03_Wazuh_Endpoint_Detection.md) |

## Environment and tools

`VMware` · `Windows Server` · `Red Hat Enterprise Linux` · `Palo Alto NGFW` · `Splunk Enterprise` · `Splunk Universal Forwarder` · `Wazuh` · `VirusTotal API` · `Linux firewalld`

## Documentation

Each report follows the same structure: objective, configuration steps, checks, screenshots and observed results. The three Markdown files can be read on GitHub without downloading the PDF.

- [Full English technical report (PDF)](Blue_Team_Technical_Report_EN.pdf)
- [Palo Alto NGFW](docs/01_Palo_Alto_NGFW.md)
- [Splunk Enterprise](docs/02_Splunk_SIEM.md)
- [Wazuh](docs/03_Wazuh_Endpoint_Detection.md)

## Scope and evidence

This is a lab report, not a claim of production deployment. The work was completed within a collaborative project, and this repository covers my Blue Team activities. Screenshots were selected from the original documentation. Images showing API secrets, private account identifiers, chat IDs or personal messages were excluded. The remaining hostnames and private addresses are from the test environment.
