# Roles and Permissions

## Built-in roles

- SUPER_ADMIN — global platform control
- ADMIN — organization administration
- SUB_ADMIN — delegated organization administration
- STAFF — operational processing
- AGENT — assigned sales/partner operations
- CLIENT — self-service B2C access

## Permission naming

Use resource.action naming, for example:

```text
clients.view
clients.create
clients.update
clients.archive
applications.view
applications.create
applications.update
applications.approve
documents.view
documents.upload
documents.generate
wallet.view
wallet.credit
wallet.debit
ledger.view
invoices.view
invoices.create
invoices.void
users.view
users.create
users.suspend
settings.view
settings.manage
audit.view
```

## Scope

Permissions should be evaluated with both action and scope:

```text
GLOBAL
ORGANIZATION
BUSINESS_UNIT
BRANCH
DEPARTMENT
TEAM
SELF
ASSIGNED
```

## Principle

The UI may hide unavailable actions, but authorization must always be enforced on the server/API/database boundary. Never rely on frontend visibility as a security control.
