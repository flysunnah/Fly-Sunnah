# Universal Enterprise Domain Model

The platform uses configuration-driven business entities.

## Organization hierarchy

```text
Platform
└── Organization
    ├── Business Unit
    ├── Branch
    ├── Department
    └── Team
```

## Identity

```text
User
├── Roles
├── Permissions
├── Sessions
└── Profile
```

## Universal business records

A business can define objects such as:

- Customer
- Application
- Order
- Booking
- Case
- Employee
- Student
- Property
- Vehicle
- Membership
- Product
- Service

Objects are composed from configurable fields, relationships, forms, workflows, permissions and automations.

## Financial chain

```text
Wallet Transaction
      ↓
Ledger Entry
      ↓
Invoice / Payment / Refund
      ↓
Receipt / Financial History
```

Balances are derived from transactions rather than being freely edited values. Ledger corrections use reversal/adjustment entries.

## Workflow model

```text
Record
  ↓
State
  ↓
Transition
  ↓
Permission + Validation
  ↓
Actions / Events / Notifications
  ↓
Next State
```

## Configuration hierarchy

```text
System Defaults
      ↓
Global Configuration
      ↓
Organization Configuration
      ↓
Role Configuration
      ↓
User Preferences
```

All important configuration should be versioned so changes can be reviewed and rolled back.
