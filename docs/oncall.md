# On-call

Page the primary from the ops rotation. If they do not ack in 15 minutes, page the backup.

Severity 1: customer-facing outage or payments auth failures. Stay on the bridge until the CDN publish for this handbook is green, then write the incident doc.

Severity 2: degraded but a workaround exists. Fix on a pull request. Do not push to `main`.
