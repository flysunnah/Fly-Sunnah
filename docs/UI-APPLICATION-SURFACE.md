# Enterprise Application Surface

## Public Experience

- Home
- About
- Services
- Products
- Solutions
- Pricing
- Promotions
- Offers
- Campaign landing pages
- Blog / News
- FAQ
- Contact
- Help Center
- Public search

## Authentication

- Login
- Register
- Email verification
- Phone / OTP verification
- Forgot password
- Reset password
- MFA
- Account recovery
- Invitation acceptance
- Session and device management

## Client / User Portal

- Dashboard
- Profile
- Services
- Applications
- Orders
- Bookings
- Documents
- Payments
- Invoices
- Wallet
- Messages
- Notifications
- Promotions
- Support tickets
- Settings

## Staff / Agent Workspace

- Dashboard
- Assigned work
- Leads
- Customers
- Applications
- Orders / bookings
- Documents
- Tasks
- Communication
- Commission
- Reports

## Sub Admin Workspace

- Delegated dashboard
- Staff management
- Agent management
- Customers
- Business operations
- Services / products
- Documents
- Finance
- Reports
- Notifications
- Delegated configuration

## Organization Admin Panel

- Organization dashboard
- Users
- Roles and permissions
- Branches / departments / teams
- CRM
- ERP
- Finance
- Documents Suite
- Marketing
- Services / products
- Operations
- Reports / analytics
- Branding
- Integrations
- Organization settings

## Super Admin Control Plane

- Global dashboard
- Organizations
- Global users
- Role / permission control
- Module manager
- Business builder
- Object builder
- Field builder
- Form builder
- Workflow builder
- Automation / rules
- ERP controls
- CRM controls
- OTA controls
- Documents Suite controls
- Marketing controls
- Finance controls
- Feature flags
- Global configuration
- Themes / branding
- Domains
- API / integrations
- Audit / security center
- System health
- Backup / recovery
- Configuration versioning / rollback

## Marketing Surface

- Promotions
- Campaigns
- Coupons
- Discount rules
- Referral
- Affiliate
- Flash offers
- Seasonal campaigns
- Audience segments
- Landing pages
- Campaign analytics

## Navigation principle

The application shell, menus, dashboards and module visibility are configuration-driven. A role only receives capabilities allowed by server-side authorization and the applicable organization/global policy. Hiding a menu item is not treated as a security control.

## Access flow

```text
Public Home
  -> Service / Product / Promotion
  -> Login / Register
  -> Authentication + Policy Evaluation
  -> Role / Organization Context
  -> Appropriate Workspace
```

The same core platform can expose different application surfaces to different organizations and roles without duplicating the underlying business engine.
