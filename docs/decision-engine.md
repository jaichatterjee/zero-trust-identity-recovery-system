# Decision Engine

## Inputs

- Identity token
- Device compliance
- MFA state
- Risk score
- Behavioral signals

## Logic

| Condition | Action |
|---|---|
| Low risk + MFA verified | Allow SSPR |
| Medium risk | Step-up authentication |
| High risk | Block and create ITSM ticket |
