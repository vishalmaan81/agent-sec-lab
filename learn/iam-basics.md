# IAM basics

A principal is who is calling. A policy is what that principal may do on which resources. Authentication answers who it is. Authorization answers what it may do.

Least privilege means the principal can complete the task and does not keep standing access beyond it. Short-lived credentials are safer than keys that sit in a file, because a stolen long-lived key keeps working until someone finds and revokes it.

Impact of getting this wrong: the agent's identity, or a stolen copy of it, can reach every resource the policy allows.

This note is the vocabulary only.
