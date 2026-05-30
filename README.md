# Homelab Enterprise Simulator

> **Built by [Limelight IT Group](https://limelight-it.co.uk)** — Enterprise IT expertise. SMB pricing.

A self-contained enterprise IT simulation environment built on commodity hardware, replicating real-world infrastructure patterns used in SMB and mid-market deployments across Scotland and the UK.

---

## What This Is

This repository documents a fully functional enterprise homelab that mirrors a production SMB IT environment. It covers:

- **Active Directory** — domain setup, DNS/DHCP, Group Policy management
- **Hyper-V infrastructure** — host configuration, nested virtualisation, network topology
- **Client endpoints** — Windows 10, Windows 11 and Linux domain integration
- **Architecture diagrams** — real lab configurations visualised end-to-end

Built to develop, test and demonstrate enterprise-grade configurations in a safe environment — and to show prospective clients exactly what Limelight IT brings to the table.

---

## Repository Structure

```
homelab-enterprise-sim/
├── ad/                  # Active Directory configuration guides
│   ├── dns-dhcp/        # DNS and DHCP setup
│   ├── domain/          # Domain and forest configuration
│   └── gpo/             # Group Policy management
├── endpoints/           # Client endpoint guides
│   ├── windows10/       # Windows 10 setup and domain join
│   ├── windows11/       # Windows 11 setup and domain join
│   ├── linux/           # Linux domain integration
│   ├── joining/         # Standard domain join procedure
│   └── validation/      # Post-join testing and validation
├── infrastructure/      # Core infrastructure docs
│   ├── hyperv-host.md   # Hyper-V host configuration
│   ├── network-topology.md # Network design and VLANs
│   └── vmware-nested-setup.md # Nested VMware setup
├── toolbox/             # Quick-reference command libraries
│   ├── ad-commands.md
│   ├── hyperv-commands.md
│   └── powershell-commands.md
└── docs/diagrams/       # Architecture and flow diagrams
```

---

## Who This Is For

- IT professionals building or studying enterprise lab environments
- SMBs evaluating what a well-structured IT infrastructure looks like
- Engineers looking for reference implementations of AD, Hyper-V and endpoint management

---

## Premium Version

Advanced hardening documentation — including Phase 4 host hardening, Phase 5 DC01 security baselines, Kerberos/NTLM hardening, certificate services and Sysmon event pipelines — is maintained in a separate private repository as part of the **Limelight IT Group** engineering toolkit.

---

## About Limelight IT Group

Limelight IT Group is a technical consultancy and automation studio based in Hamilton, Scotland. We provide enterprise-grade IT infrastructure, Microsoft 365 deployments, Cyber Essentials certification and endpoint management for UK SMBs.

- 🌐 [limelight-it.co.uk](https://limelight-it.co.uk)
- 📧 vincent@limelight-it.co.uk
- 📞 03305 202369

---

## License

MIT License — Copyright (c) 2026 Limelight IT Group
