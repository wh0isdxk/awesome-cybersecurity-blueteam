# Awesome Cybersecurity Blue Team [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome resources, tool, and other shiny things for cybersecurity blue teams.

[Cybersecurity blue teams](https://en.wikipedia.org/wiki/Blue_team_(computer_security)) are groups of individuals who identify security flaws in information technology systems, verify the effectiveness of security measures, and monitor the systems to ensure that implemented defensive measures remain effective in the future. For offensive TTPs, please see [awesome-pentest](https://github.com/meitar/awesome-pentest).

Your contributions and suggestions are heartily♥ welcome. (✿◕‿◕). Please check the [Contributing Guidelines](CONTRIBUTING.md) for more details. This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contents

- [Firewalling distributions](#firewalling-distributions)
- [Honeypots](#honeypots)
- [Host-based tools](#host-based-tools)
- [Network Security Monitoring (NSM)](#network-security-monitoring-nsm)
- [Network perimeter defenses](#network-perimeter-defenses)
- [Practice, training, and drills](#practice-training-and-drills)
- [Security Information and Event Management (SIEM)](#security-information-and-event-management-siem)
- [Service and performance monitoring](#service-and-performance-monitoring)
- [Threat intelligence, analytics, and reporting](#threat-intelligence-analytics-and-reporting)
- [Tor Onion service defenses](#tor-onion-service-defenses)
- [Transport-layer defense](#transport-layer-defenses)
- [Windows-based defenses](#windows-based-defenses)

## Firewalling distributions

- [OPNsense](https://opnsense.org/) - FreeBSD based firewall and routing platform.
- [pfSense](https://www.pfsense.org/) - Firewall and router FreeBSD distribution.

## Honeypots

See also [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens) - Self-hostable honeytoken generator and reporting dashboard; demo version available at [CanaryTokens.org](https://canarytokens.org/).

## Host-based tools

- [Artillery](https://github.com/BinaryDefense/artillery) - Combination honeypot, filesystem monitor, and alerting system designed to protect Linux and Windows operating systems.
- [Fail2Ban](https://www.fail2ban.org/) - Intrusion prevention software framework that protects computer servers from brute-force attacks.

## Network Security Monitoring (NSM)

- [Bro](https://www.bro.org/) - Powerful network analysis framework focused on security monitoring.
- [Snort](https://snort.org/) - Widely-deployed, Free Software IPS capable of real-time packet analysis, traffic logging, and custom rule-based triggers.
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) - Catch spoofed NetBIOS Name Service (NBNS) responses and alert to an email or log file.
- [Suricata](https://suricata-ids.org/) - Free, cross-platform, IDS/IPS with on- and off-line analysis modes and deep packet inspection capabilities that is also scriptable with Lua.
- [Wireshark](https://www.wireshark.org) - Free and open-source packet analyzer useful for network troubleshooting or forensic netflow analysis.
- [netsniff-ng](http://netsniff-ng.org/) -  Free and fast GNU/Linux networking toolkit with numerous utilities such as a connection tracking tool (`flowtop`), traffic generator (`trafgen`), and autonomous system (AS) trace route utility (`astraceroute`).

## Network perimeter defenses

- [fwknop](https://www.cipherdyne.org/fwknop/) - Protects ports via Single Packet Authorization in your firewall.

## Practice, training, and drills

- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - Modular, menu-driven, cross-platform tool for building repeatable, time-delayed, distributed security events for Blue Team drills and sensor/alert mapping.

## Security Information and Event Management (SIEM)

- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - Single-server open source SIEM platform featuring asset discovery, asset inventorying, behavioral monitoring, and event correlation, driven by AlienVault Open Threat Exchange (OTX).
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) - Cybersecurity incident management platform allowing for easy creation, tracking, and reporting of cybersecurity incidents.
- [Prelude SIEM OSS](https://www.prelude-siem.org/) - Open source, agentless SIEM with a long history and several commercial variants featuring security event collection, normalization, and alerting from arbitrary log input and numerous popular monitoring tools.

## Service and performance monitoring

- [Icinga](https://icinga.com/) - Modular redesign of Nagios with pluggable user interfaces and an expanded set of data connectors, collectors, and reporting tools.
- [Nagios](https://nagios.org) - Popular network and service monitoring solution and reporting platform.
- [OpenNMS](https://opennms.org/) - Free and feature-rich networking monitoring system supporting multiple configurations, a variety of alerting mechanisms (email, XMPP, SMS), and numerous data collection methods (SNMP, HTTP, JDBC, etc).

## Threat intelligence, analytics, and reporting

- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) - Provides IP network situational awareness of industrial control systems (ICS) and Supervisory Control and Data Acquisition (SCADA) by passively mapping, accounting for, and reporting on your ICS/SCADA network topology and endpoints.
- [Unfetter](https://nsacyber.github.io/unfetter/) - Identifies defensive gaps in security posture by leveraging Mitre's ATT&CK framework.

## Tor Onion service defenses

- [OnionBalance](https://onionbalance.readthedocs.io/) - Provides load-balancing while also making Onion services more resilient and reliable by eliminating single points-of-failure.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - Version 3 Onion service guard discovery attack mitigation script (intended for eventual inclusion in Tor core).

## Transport-layer defenses

- [OpenVPN](https://openvpn.net/) - Open source, SSL/TLS-based virtual private network (VPN).

## Windows-based defenses

- [NotRuler](https://github.com/sensepost/notruler) - Detect both client-side rules and VBScript enabled forms used by the [Ruler](https://github.com/sensepost/ruler) attack tool when attempting to compromise a Microsoft Exchange server.

# License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).