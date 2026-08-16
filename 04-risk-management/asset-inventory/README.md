# NF-GRC-004 — Information & Technology Asset Inventory

**Status:** Complete  
**Version:** 1.0  
**Classification:** Internal  
**Register Owner:** IT Manager  
**Custodian:** GRC Analyst  
**Reviewer:** Security Manager  
**Approver:** CIO  
**Effective Date:** August 16, 2026  
**Review Cycle:** Quarterly

## Artifact File

- [Open the approved NF-GRC-004 Asset Inventory workbook](./NF-GRC-004_NovaForge-Asset-Inventory.xlsx)

## Purpose

This artifact establishes NovaForge Manufacturing's baseline inventory of information and technology assets. It provides the organizational context needed to assign ownership, identify sensitive and critical assets, prioritize risk assessment work, and select appropriate security controls.

## Baseline Scope

The approved inventory contains **35 representative assets** across:

- Cloud infrastructure and SaaS platforms
- Corporate endpoints, servers, networking, and remote access
- Security monitoring and endpoint-protection tools
- Engineering workstations, CAD/PLM, simulation, source-code, and firmware systems
- Manufacturing and operational technology, including robots, PLCs, test cells, and the OT network
- Business applications supporting sales, HR, finance, warehouse, customer support, and field services
- High-value information assets including intellectual property, employee records, and manufacturing telemetry

## Why 35 Assets Is an Appropriate Baseline

The inventory is intentionally representative rather than an attempt to simulate every device, account, component, or software instance in a production CMDB. Thirty-five records provide enough breadth to demonstrate asset identification, ownership, classification, criticality, dependency awareness, and prioritization without creating artificial volume.

The register should expand only when later risk assessments, control reviews, vendor assessments, or business-impact work identify a meaningful new asset or dependency.

## Key Metrics

| Metric | Result |
|---|---:|
| Total assets | 35 |
| Critical assets | 10 |
| High-criticality assets | 23 |
| Moderate-criticality assets | 2 |
| Internet-facing assets | 19 |
| Assets handling Restricted data | 18 |
| Departments represented | 9 |

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| Asset Register | Maintains the 35 asset records and core GRC attributes. |
| Definitions & Dropdowns | Defines entry standards, classifications, criticality, backup, and lifecycle values. |
| Asset Summary | Provides formula-driven KPIs, distributions, departmental counts, and a criticality chart. |
| Revision History | Records draft development, branding, approval, and version history. |

## Skills Demonstrated

- Asset inventory development
- Asset ownership and custodianship
- Data classification
- Business-criticality analysis
- Technology and OT scoping
- Cloud and SaaS inventory
- Dependency documentation
- Security exposure identification
- Backup and lifecycle tracking
- Formula-driven GRC reporting
- Governance documentation and approval tracking

## Next Dependency

NF-GRC-004 provides the asset context for **NF-GRC-005 — Cybersecurity Risk Assessment**. The next artifact will prioritize assets and scenarios based on criticality, data sensitivity, internet exposure, operational dependencies, and potential business impact.

> NovaForge Manufacturing, Inc. is a fictional organization created for educational and portfolio purposes.
