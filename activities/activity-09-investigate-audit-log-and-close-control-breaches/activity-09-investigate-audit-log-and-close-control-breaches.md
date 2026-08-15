# Activity 09 — Investigate Audit Log and Close-Control Breaches

**Level:** Advanced  
**TSC mapping:** K1, A1  
**Estimated time:** 45–70 minutes  

## Scenario

After management sign-off, the controller finds a backdated invoice edit, a deleted bill, a new bank rule, and a supplier bank-detail change.

## Goal

Reconstruct events, assess financial impact, strengthen roles, and lock the approved period.

## Workflow

![Activity workflow](workflow.png)

## Files in this activity

- `activity-09-control.xlsx`
- `audit_log.csv`
- `close_checklist.csv`
- `user_roles.csv`
- `workflow.png`

## Detailed step-by-step

1. Filter the audit-log dataset by date, user, event type, transaction, and indirect/system administration activity.

2. Reconstruct each event using before/after values and supporting-document references.

3. Quantify the financial-statement, tax, reconciliation, and control impact of every change.

4. Compare current roles with least privilege and segregation-of-duties requirements; propose changes.

5. Correct or escalate affected transactions in the practice company and document approval.

6. Complete the close checklist, set the approved close date/password control, and define exception authority.

7. Present root cause, immediate containment, corrective action, owner, and due date.

## Evidence to retain

- Completed control workbook with formulas intact.
- QuickBooks Online report/export or screenshot references listed in the Evidence Log.
- Exception decisions and approval evidence.
- Final reconciliation and acceptance-test sign-off.

## Acceptance criteria

- [ ] Every event is reconstructed
- [ ] Financial impact is quantified
- [ ] Role conflicts are remediated
- [ ] Close is locked with controlled exceptions

## Trainer checkpoint

Explain one posting or configuration choice, its financial-statement effect, the control evidence, and what would happen if it were wrong.
