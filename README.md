# Fly Sunnah — Universal Enterprise Platform

A configuration-driven, white-label, multi-organization enterprise platform foundation.

> This repository is being evolved from the current Document Workbench into a universal enterprise platform. The platform is not tied to travel, visa, work permits, or any single industry.

<p align="center">
  <img src="docs/assets/platform-overview.svg" alt="Fly Sunnah Universal Enterprise Platform overview" width="100%" />
</p>

<p align="center">
  <strong>One core engine. Multiple organizations. Configurable business capabilities.</strong>
</p>

## Core principles

- Universal business model: services, products, objects, forms and workflows are configurable.
- Enterprise-first architecture rather than SaaS-first product packaging.
- Multi-organization isolation with B2B and B2C support.
- Hierarchical identity: Super Admin, Admin, Sub Admin, Staff, Agent and Client.
- Fine-grained RBAC and policy-based access control.
- Configuration-driven modules, fields, forms, workflows, pricing, menus and feature flags.
- Financial separation between wallet, transactions, ledger, invoices and payments.
- Versioned templates, documents and configuration.
- Secure file access and immutable audit history for sensitive/financial actions.
- API-first design for web, mobile and integrations.
- White-label branding and domain configuration per organization.

## Application surfaces

- Public Home, Services, Products, Pricing, Promotions, Offers, News, FAQ, Contact and Help Center.
- Authentication: Login, Register, Email/Phone Verification, OTP, MFA, Recovery and Session Management.
- Client / User Portal.
- Staff / Agent Workspace.
- Sub Admin Workspace.
- Organization Admin Panel.
- Super Admin Control Plane.

See `docs/UI-APPLICATION-SURFACE.md` for the complete application surface and role-based navigation model.

## Target platform modules

1. Super Admin Control Plane
2. Organization / B2B Management
3. B2C Client Management
4. Admin / Sub Admin / Staff / Agent Management
5. Identity, Roles and Permissions
6. Business Builder
7. Object and Field Builder
8. Form Builder
9. Workflow Builder
10. Automation / Rules Engine
11. CRM / Applications / Orders
12. Document and Template Engine
13. Secure File Management
14. E-Wallet
15. Ledger
16. Invoice / Payment / Refund
17. Commission Engine
18. Live Chat
19. Support Ticketing
20. Notifications
21. Reports and Analytics
22. Audit and Security
23. White-label / Theme / Domain Engine
24. API and Integration Layer
25. Global Search
26. System Health / Backup / Configuration Versioning

## Visual design

The README architecture graphic is maintained at `docs/assets/platform-overview.svg`. It is a repository-native SVG so the product overview remains version-controlled alongside the platform documentation.

## Repository direction

The existing `index.html` remains the current browser prototype. The enterprise implementation will be modularized under the application/backend structure without discarding the prototype until the replacement is ready.

See `docs/ARCHITECTURE.md` for the platform blueprint and `docs/ROADMAP.md` for implementation phases.
