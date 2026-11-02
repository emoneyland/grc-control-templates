# Control Matrix Template (study version)

Generic controls for practice. No client data. Fill in the Result column only with real evidence from a real environment.

| Control ID | Framework | Control | Evidence to request | Test of design | Test of effectiveness | Result |
|---|---|---|---|---|---|---|
| AC-01 | SOC 2 / ISO 27001 | MFA is required for all remote access | MFA policy; IdP MFA enrollment report | Confirm the policy requires MFA and covers all remote paths | Sample remote logins; confirm MFA challenge occurred | |
| AC-02 | SOC 2 / ISO 27001 | User access is reviewed quarterly | Access review records; list of reviewers | Confirm reviews are scheduled, assigned, and cover privileged accounts | Inspect two completed reviews; confirm removals were actioned | |
| AC-03 | SOC 2 / ISO 27001 | Privileged access requires approval | Privilege request tickets; approval records | Confirm no standing privilege is granted without approval | Sample privilege grants; trace each to an approval | |
| AC-04 | SOC 2 / ISO 27001 | Leaver accounts are deactivated promptly | HR leaver list; IdP deactivation log | Confirm a defined leaver process with a time target exists | Match leavers to deactivation dates; flag gaps | |
| CM-01 | SOC 2 / ISO 27001 | Changes to production require approval and testing | Change tickets; test evidence | Confirm changes can't reach production without approval | Sample production changes; trace each to approval and test evidence | |
| BK-01 | SOC 2 / ISO 27001 | Backups are tested by restore | Backup schedule; restore test records | Confirm backups run on schedule and restores are tested | Inspect the latest restore test; confirm it succeeded | |
| VN-01 | SOC 2 / ISO 27001 | Vendors are risk-assessed before onboarding | Vendor risk assessments; onboarding checklist | Confirm no vendor is onboarded without an assessment | Sample onboarded vendors; trace each to an assessment | |

## How to use it

1. Pick the controls in scope for the framework you're working to.
2. Request the evidence listed before testing anything.
3. Record design and effectiveness results separately — a well-designed control can still fail in practice.
4. Every exception needs an owner and a remediation date, or it will still be open next quarter.
