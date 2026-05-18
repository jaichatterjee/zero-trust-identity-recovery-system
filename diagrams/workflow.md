# Recovery Workflow

```text
Identity Request
        ↓
Validate User Context
        ↓
Evaluate Device State
        ↓
Evaluate Risk Signals
        ↓

Low Risk?
 ├── Yes → Allow SSPR
 │
 └── No
        ↓

Medium Risk?
 ├── Yes → Step-Up Authentication
 │
 └── No
        ↓

High Risk
        ↓
Block Access
        ↓
Generate ServiceNow Ticket
```
