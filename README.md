# Awesome-Identity-User-Profile-Administration

# Awesome-Identity-User-Profile-Administration

## Top Identity Management & Access Governance

**Curated List of SaaS Products & Open-Source GitHub Projects**



*Focused on Identity Governance and Administration (IGA), Access Governance, Identity Lifecycle Management, Role Management & Compliance*



**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Management & Access Governance**. These solutions help organizations manage the full identity lifecycle, enforce least privilege, perform access reviews and certifications, detect segregation-of-duties conflicts, and maintain compliance across hybrid and cloud environments.



**Examples** include SailPoint, Saviynt, Okta, Microsoft Entra ID, Ping Identity, One Identity, ForgeRock, CyberArk, Omada, and Zoho Identity (the category leaders).



**Open-source emphasis**: Full-featured commercial IGA platforms dominate large enterprises. However, strong open-source alternatives exist. **midPoint** stands out as a comprehensive open-source IGA platform, complemented by **Apache Syncope**, **Keycloak**, **authentik**, **FreeIPA**, and related projects. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[SailPoint](https://www.sailpoint.com/)**  

  Leading Identity Governance and Administration platform offering identity lifecycle management, access certifications, role management, and AI-driven insights.



- **[Saviynt](https://saviynt.com/)**  

  Enterprise identity governance platform focused on cloud and hybrid environments with strong analytics, access requests, and compliance capabilities.



- **[Okta](https://www.okta.com/)**  

  Identity platform that combines workforce identity, lifecycle management, and governance features alongside its core SSO and authentication offerings.



- **[Microsoft Entra ID Governance](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id-governance)**  

  Microsoft’s identity governance capabilities including access reviews, entitlement management, lifecycle workflows, and privileged identity management.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform offering access management, federation, and governance features for complex hybrid environments.



- **[One Identity](https://www.oneidentity.com/)**  

  Identity security portfolio covering identity governance, privileged access, and directory management (includes One Identity Manager and related products).



- **[ForgeRock](https://www.forgerock.com/)**  

  Full identity platform spanning access management, identity management, directory services, and identity gateway capabilities.



- **[CyberArk](https://www.cyberark.com/)**  

  Identity security company known for privileged access management, with broader identity management and workforce identity offerings.



- **[Omada](https://www.omadaidentity.com/)**  

  Identity governance platform focused on simplifying access management, certifications, and compliance for mid-market and enterprise customers.



- **[Zoho Identity / Directory](https://www.zoho.com/)**  

  Identity and access management capabilities within the Zoho ecosystem for workforce identity and application access control.



## Open-Source GitHub Projects

- **[midPoint](https://github.com/Evolveum/midpoint)**  

  Comprehensive open-source Identity Governance and Administration (IGA) platform. Supports identity provisioning, lifecycle management, access certification, role management, organizational structures, and policy enforcement.



- **[Apache Syncope](https://github.com/apache/syncope)**  

  Open-source Identity Management system focused on provisioning, synchronization, and workflow-driven identity processes. Suitable for enterprise identity integration scenarios.



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Widely used open-source Identity and Access Management solution. While primarily an IdP/SSO platform, it provides user federation, fine-grained authorization, and can serve as a foundation for governance workflows.



- **[authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source identity provider with strong support for SSO, MFA, user management, and policy-based access control. Popular for self-hosted governance-adjacent use cases.



- **[FreeIPA](https://www.freeipa.org/)**  

  Open-source identity management system for Linux/Unix environments combining LDAP, Kerberos, policy management, and host-based access control.



- **[OpenIAM](https://www.openiam.com/)**  

  Open-source identity and access management platform (Community Edition available) that aims to combine IGA and access management capabilities.



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  Modern, secure open-source identity management platform written in Rust, focused on simplicity and security.



- **[Ory Stack](https://github.com/ory)**  

  Cloud-native open-source identity infrastructure (Kratos for identity management, Hydra for OAuth2/OIDC) suitable for building custom governance layers.



- **[Samba Active Directory](https://www.samba.org/)**  

  Open-source Active Directory domain services implementation that can serve as a directory foundation for identity governance processes.



- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  

  Open-source identity and access management server supporting SSO, federation, provisioning, and adaptive authentication.



### Additional Strong Open-Source Options

- Full IGA platforms: **midPoint** (strongest open-source IGA option), **Apache Syncope**, **OpenIAM**.

- Identity Providers / Access Management: **Keycloak**, **authentik**, **WSO2 Identity Server**.

- Directory & Linux identity: **FreeIPA**, **Samba AD**.

- Cloud-native building blocks: **Ory**, **Kanidm**.

- Accepting that commercial IGA platforms (SailPoint, Saviynt, Microsoft Entra ID Governance, Omada, One Identity, Ping) still lead in advanced access certification campaigns, AI-driven role mining, large-scale compliance reporting, connector ecosystems, and enterprise support.



**Frameworks for building custom systems**:  

Use **midPoint** as the central IGA engine for provisioning, certifications, and policy → pair with **Keycloak** or **authentik** for authentication and SSO → leverage **FreeIPA** or LDAP directories as authoritative sources → extend with **Ory** components for cloud-native services. Ideal for organizations that need transparent, self-hosted identity governance without per-identity commercial licensing.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity Governance directly impacts security, compliance, and operational risk. Open-source IGA tools provide transparency and control but require significant expertise for design, connector development, and ongoing operations. Commercial platforms typically offer broader connector libraries, advanced analytics, and professional services. This list is not security, compliance, or identity architecture advice.



---

**Made for identity governance professionals, IAM architects, compliance teams, and open-source advocates.**



Let's keep identity management and access governance transparent, enforceable, and under your control.
