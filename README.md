# Rumba Identity Platform

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/rumba.id.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/rumba.id.svg">
  <img alt="Rumba Identity Platform" src="assets/rumba.id.svg" width="200">
</picture>

A sovereign, self-hosted identity platform

Microsoft Entra ID and Active Directory alternative, written in Rust

[![License: FSL-1.1-MIT](https://img.shields.io/badge/License-FSL--1.1--MIT-blue.svg)](https://fsl.software/)
[![Fair Source](https://img.shields.io/badge/Fair-Source-orange.svg)](https://fair.io/)
[![Rust](https://img.shields.io/badge/rust-2024-000000.svg?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/)

</div>

---

## Status: In Development

Rumba is under active development. First release planned for Q1 2026.

Rumba is a self-hosted identity platform designed to replace Microsoft Entra ID
(Azure AD) and Windows Active Directory. It includes native LDAP and Kerberos
server implementations, allowing organizations to run their own identity
infrastructure without depending on Microsoft cloud services.

### Planned Features

- **LDAP Server** — Native directory services implementation
- **Kerberos KDC** — Authentication protocol for Windows and Linux clients
- **OAuth 2.0 / OpenID Connect** — Identity provider with standard flows
- **Microsoft Graph API** — Compatibility layer for existing integrations
- **Multi-tenant** — Multiple organizations from a single deployment
- **Linux Integration** — NSS/PAM modules for Unix authentication

### Why Self-Host?

- **Data sovereignty** — Identity data stays on your infrastructure
- **No vendor lock-in** — Independence from cloud provider pricing and policies
- **Compliance** — Meet data residency requirements for regulated industries
- **No subscription fees** — One-time deployment, no per-user costs

### Use Cases

**Homelabs** — Run a proper identity infrastructure for your home network.
Authenticate Linux and Windows machines, manage users centrally, and learn
enterprise identity protocols without cloud dependencies or subscription costs.

**Small and Medium Businesses** — Deploy identity management that scales with
your organization. Avoid per-user licensing, keep data on-premises, and
integrate with existing applications through standard protocols.

**Regulated Industries** — Organizations in healthcare, finance, or government
that require data residency or cannot use US-based cloud services.

### Fair Source

Rumba is licensed under the [Functional Source License (FSL-1.1-MIT)][fsl],
part of the [Fair Source][fair-source] initiative. This means:

- **Full access** to source code for nearly all purposes
- **Freedom to modify** and deploy in your own infrastructure
- **Automatic conversion** to MIT license two years after each release
- **Protection for sustainability** while remaining open and transparent

### Commercial Support

Commercial licenses and support contracts available from
[Kogito UG (haftungsbeschränkt)][kogito].

### Contact

Questions or feedback: [hello@rumba.id](mailto:hello@rumba.id)

---

<div align="center">

First release: Q1 2026

[Website](https://rumba.id) ·
[Documentation](https://docs.rumba.id) ·
[GitHub](https://github.com/rumba-id/rumba.id)

</div>

[fsl]: https://fsl.software/
[fair-source]: https://fair.io/
[kogito]: https://kogito.network/
