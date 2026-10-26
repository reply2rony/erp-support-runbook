# ERP Support Runbook — First Response

## When a user reports an ERP problem, ask these first
1. What were you trying to do, step by step?
2. What error message (exact words) or screen did you see?
3. Is it one user, one department, or everyone?
4. When did it start, and did it work before?
5. Can you show a screenshot? (Remove any private data from the screenshot first.)

## Then check, in this order
1. Is the user signed in with the correct account and role?
2. Is the ERP system itself running, or is it down for everyone?
3. Is the network/server available? (See the Network Troubleshooting Playbook.)
4. Is it a data problem (wrong code, missing master data) or a system problem?
5. If it is a data problem, correct it only with approval and a record of what changed.

## Escalation rule
- If more than one department is affected, or the system is down, escalate to the ERP vendor / senior IT contact immediately and tell affected managers. Do not wait for more tickets.
- Record every incident in incident-log-template.csv, even if it was fixed in five minutes. Patterns only appear in a log.
