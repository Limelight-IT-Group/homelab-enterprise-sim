# Diagrams

This directory contains architecture and flow diagrams for the Limelight IT Homelab Enterprise Simulator.

## Contents

| Diagram | Description |
|---------|-------------|
| `enterprise-homelab-architecture.png` | Full lab topology overview |
| `network-topology.png` | Network layout, VLANs and routing |
| `hyper-v-host-architecture.png` | Hyper-V host configuration |
| `hyper-v-host-issue.png` | Documented host issue and resolution |
| `vmware-nested-setup.png` | Nested VMware configuration |
| `client-authentication-flow.png` | Client authentication path through AD |
| `client-dns-dc-adds-flow.png` | DNS resolution and domain join flow |
| `client-network-ad-flow.png` | Client network and AD communication |
| `dc01-account-policy-flow.png` | DC01 account policy enforcement flow |
| `dc01-adcs-architecture.png` | Active Directory Certificate Services layout |
| `dc01-audit-logging.png` | Audit logging pipeline |
| `dc01-audit-policy-overview.png` | Audit policy structure overview |
| `dc01-authentication-event-flow.png` | Authentication event sequence |
| `dc01-certificate-enrollment.png` | Certificate auto-enrollment flow |
| `dc01-gpo-baseline-architecture.png` | GPO baseline structure |
| `dc01-hardening-architecture.png` | DC01 hardening architecture |
| `dc01-kerberos-flow.png` | Kerberos authentication flow |
| `dc01-ntlm-restrictions.png` | NTLM restriction configuration |
| `phase-4-hardening-path.png` | Phase 4 hardening progression |
| `phase-5-audit-policy-overview.png` | Phase 5 audit policy overview |
| `phase-5-certificate-autoenrollment.png` | Phase 5 certificate autoenrollment |
| `phase-5-folder-structure.png` | Phase 5 folder/repo structure |
| `phase-5-kerberos-ntlm-flow.png` | Phase 5 Kerberos and NTLM flow |
| `phase-5-sysmon-pipeline.png` | Phase 5 Sysmon event pipeline |
| `phase4-host-hardening.png` | Phase 4 host hardening overview |
| `phase4-vmware-settings.png` | Phase 4 VMware configuration |
| `phase4-vswitch-binding.png` | Phase 4 vSwitch binding |

## Usage

Reference these diagrams alongside the documentation in `/ad/`, `/infrastructure/` and `/endpoints/` for a full picture of the lab environment. Diagrams are generated from real lab configurations and updated as the environment evolves.
