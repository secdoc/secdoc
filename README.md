# Lester E. Nichols III | secdoc

I am a cybersecurity architect, security engineering leader, author, and educator. My work focuses on turning security requirements into practical architecture across enterprise networks, cloud platforms, applications, infrastructure, and security operations.

I hold an MS in Information Assurance and maintain CISSP and GIAC certifications. My experience spans cybersecurity architecture, risk management, network engineering, cloud security, detection engineering, incident response, compliance, and technical leadership.

The material I publish here is practitioner-built. I favor deployable examples, documented tradeoffs, sanitized reference architectures, and reusable security content over abstract guidance.

## Focus areas

- Cybersecurity architecture and security engineering
- Risk assessment, governance, compliance, and control design
- Network, cloud, Linux, Windows, and application security
- SIEM, detection engineering, threat intelligence, SOAR, and DFIR
- DevSecOps, infrastructure as code, and security automation
- AI agent skills for technical security and architecture work

## Book

I am the author of [Cybersecurity Architect's Handbook, Second Edition](https://www.amazon.com/Cybersecurity-Architects-Handbook-architects-enterprise/dp/180610539X), published by Packt in 2026. It is an architect's guide to designing, building, and defending the modern enterprise.

## Public repositories

All links in this section point only to public repositories that contain my original projects and published resources.

### Security operations architecture and integrations

- [soc-pipeline-public](https://github.com/secdoc/soc-pipeline-public): A sanitized, adaptable end-to-end security operations pipeline. It brings network, DNS, endpoint, identity, and vulnerability telemetry into Graylog and Wazuh, then supports AI enrichment, SOAR, and DFIR workflows using Terraform and Ansible.
- [socfortress-waf-siem](https://github.com/secdoc/socfortress-waf-siem): A reference integration that brings SOCFortress WAF events from Caddy, Coraza, and OWASP CRS into Graylog and Wazuh, including collection, normalization, detections, and dashboards.
- [greenbone-wazuh-graylog](https://github.com/secdoc/greenbone-wazuh-graylog): A read-only Greenbone/OpenVAS integration for sending normalized vulnerability findings to Graylog and Wazuh, with decoders, rules, and dashboard content.
- [technitium-wazuh-graylog](https://github.com/secdoc/technitium-wazuh-graylog): A Technitium DNS telemetry integration with query enrichment and detections for blocking, NXDOMAIN activity, DGA behavior, and DNS tunneling signals.
- [wazuh-unifi-detections](https://github.com/secdoc/wazuh-unifi-detections): Custom Wazuh decoders, rules, MITRE ATT&CK mappings, and dashboards for UniFi gateway firewall and threat logs.

### Graylog content and network telemetry

- [Graylog_Dashboards](https://github.com/secdoc/Graylog_Dashboards): Security dashboards for DHCP, Maltrail, NAXSI, NetFlow, OPNsense, DNS, Suricata, and Zenarmor telemetry.
- [Graylog_Inputs](https://github.com/secdoc/Graylog_Inputs): Reusable Graylog input and parser configurations for common network and security data sources.
- [Graylog_Pipeline](https://github.com/secdoc/Graylog_Pipeline): Graylog pipeline configurations and rules for normalizing and processing network and security events.
- [OPNsense-24.7-Graylog-Grok-Patterns](https://github.com/secdoc/OPNsense-24.7-Graylog-Grok-Patterns): Grok patterns, pipeline rules, content packs, and dashboards for OPNsense 24.7 filterlog and Suricata data.
- [Unifi-Graylog-Grok-Patterns](https://github.com/secdoc/Unifi-Graylog-Grok-Patterns): Grok patterns and pipeline rules for parsing UniFi Network application CEF events in Graylog.

### Detection content and utilities

- [custom_suricata_rules](https://github.com/secdoc/custom_suricata_rules): Custom Suricata IDS/IPS rules for protocol and traffic visibility not covered by standard feeds.
- [whois_search](https://github.com/secdoc/whois_search): A shell utility that performs WHOIS lookups from an IP address list and writes the results to a report.

### AI agent tooling and professional resources

- [AI-Agent-Skills](https://github.com/secdoc/AI-Agent-Skills): Practitioner-built skills for AI assistants covering cybersecurity architecture, threat modeling, application and code security, network engineering, Linux, Windows, firewall platforms, and executive reporting.
- [Recommended_Reading](https://github.com/secdoc/Recommended_Reading): A maintained reading list for security, networking, operating systems, software development, AI, leadership, and technical careers.

## Elsewhere

- [secdoc.tech](https://www.secdoc.tech)

## Licensing

This repository is dual-licensed, with attribution required under both licenses:

- Code and configuration: [Apache License 2.0](LICENSE)
- Documentation, guides, and diagrams: [Creative Commons Attribution 4.0 International](LICENSE-docs)

See [LICENSING.md](LICENSING.md) and [NOTICE](NOTICE) for details.
