# Homelab Enterprise Simulator

## Overview
A self-contained enterprise IT simulation environment built on commodity hardware — replicating real-world infrastructure patterns used in SMB and mid-market deployments.

## Purpose
Built by Limelight IT Group to develop, test and demonstrate enterprise-grade configurations in a safe homelab environment. Covers Active Directory / Entra ID, M365 integration, endpoint management, network segmentation, Cyber Essentials compliance simulation and automated provisioning.

Use this repo to follow along, fork your own lab, or reference real-world SMB configurations.

## Structure
```
homelab-enterprise-sim/
├── ad/                  # Active Directory / Entra ID configurations
├── m365/                # Microsoft 365 setup scripts and policies
├── network/             # Network topology, VLANs, firewall rules
├── endpoints/           # Endpoint management (Intune, MDM configs)
├── cyber-essentials/    # Cyber Essentials compliance checks and evidence
├── provisioning/        # Automated provisioning scripts
├── docs/                # Architecture diagrams and runbooks
├── .gitignore
└── README.md
```

## Architecture
The lab simulates a typical 10–50 user SMB environment:
- **Domain controller** — Windows Server (physical or VM)
- **Entra ID sync** — Azure AD Connect / Entra Connect
- **M365 tenant** — Exchange Online, Teams, SharePoint, Intune
- **Network layer** — pfSense / UniFi with VLAN segmentation
- **Endpoints** — Windows 10/11 managed via Intune

## Usage
Each subdirectory contains its own README with setup instructions. Start with `docs/` for the architecture overview, then follow the numbered setup guides.

## Standards
- All configurations documented with inline comments
- No production credentials — lab credentials only, rotated regularly
- Configurations version-controlled with clear change history
- Designed to map directly to Cyber Essentials v3.1 technical controls

## License
MIT License — Copyright (c) 2026 Limelight IT Group