# ASI03 — Identity and Privilege Abuse

The agent acts with a broader identity than the task needs. That can be an inherited user token, a long-lived service credential, or a sub-agent that receives its parent's full access.

Impact: one bad decision, or one stolen credential, reaches every resource that identity can touch.

Name source: OWASP Top 10 for Agentic Applications 2026. This note is the name and the impact only.
