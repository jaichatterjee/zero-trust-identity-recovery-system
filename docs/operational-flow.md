# Operational Flow

```text
User
   ↓
Company Portal
   ↓
Identity Recovery Agent
   ↓
Entra ID Authentication
   ↓
Conditional Access Evaluation
   ↓

IF Low Risk:
    → Self-Service Password Reset

IF Medium Risk:
    → Step-Up Authentication

IF High Risk:
    → Block Access
    → Create ServiceNow Ticket
```
