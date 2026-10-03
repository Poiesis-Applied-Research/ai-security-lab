# AI Security Lab

This repository will document the design, implementation, and evolution of the Poiesis Applied Research AI security lab.

The lab is intended to support research into AI-enabled security operations, including:

- instrumented victim systems
- attacker infrastructure
- centralized security telemetry
- SIEM and defensive tooling
- APIs and MCP integrations
- AI-assisted investigation workflows
- adversarial testing and system evaluation

## Status

Architecture and system requirements are currently being researched.

Initial work is focused on defining:

- hardware requirements
- virtualization approach
- network architecture
- telemetry sources
- SIEM platform
- lab segmentation
- AI and MCP integration points

Design decisions and implementation details will be added as the lab develops.

### Technologies Under Consideration

- **Adversarial Mock API (Flask)** — A controlled internal API capable of returning normal or adversarial tool responses. This will allow the lab to test prompt injection, tool-response manipulation, and whether AI/MCP security controls behave as expected.

## Security Note

Secrets, credentials, local environment files, telemetry, packet captures, and VM artifacts should not be committed to this repository.