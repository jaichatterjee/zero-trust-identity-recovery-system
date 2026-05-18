# Architecture Diagram

```text
                    Zero Trust Identity Recovery System
                                      │
        ┌─────────────────────────────┼────────────────────────────┐
        │                             │                            │
        ↓                             ↓                            ↓

 Identity Plane               Device Plane              Authentication Layer

 Microsoft Entra ID           Microsoft Intune          Authenticator/MFA
 Risk Scoring                 Device Compliance         Step-Up Authentication

        │                             │                            │
        └─────────────────────────────┼────────────────────────────┘
                                      ↓

                           Detection & Analytics

                           Microsoft Sentinel
                           Behavior Analytics
                           Risk Correlation

                                      ↓

                              Decision Engine

                                      ↓

                           Recovery / ITSM Layer

                           ServiceNow Workflow
```
