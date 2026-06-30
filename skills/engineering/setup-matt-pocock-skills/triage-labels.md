# Triage Labels

The skills speak in terms of canonical triage roles. This file maps those roles to the actual tracker fields used in this repo.

For GitHub and GitLab, the tracker field is usually a label. For Linear, it may be a state, a label, or both; use `triage-labels-linear.md` as the starting point.

| Role in mattpocock/skills | Tracker mapping      | Meaning                                  |
| ------------------------- | -------------------- | ---------------------------------------- |
| `needs-triage`            | `needs-triage`       | Maintainer needs to evaluate this issue  |
| `needs-info`              | `needs-info`         | Waiting on reporter for more information |
| `ready-for-agent`         | `ready-for-agent`    | Fully specified, ready for an AFK agent  |
| `ready-for-human`         | `ready-for-human`    | Requires human implementation            |
| `wontfix`                 | `wontfix`            | Will not be actioned                     |

When a skill mentions a role, use the corresponding tracker mapping from this table.

Edit the right-hand column to match whatever vocabulary you actually use.
