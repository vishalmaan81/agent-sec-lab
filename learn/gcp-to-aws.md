# GCP to AWS

Foundations mapping for the cloud move in Phase 1. Names only.

| GCP | AWS |
| --- | --- |
| Project | Account |
| Service account | IAM role used by a workload |
| IAM binding | Policy attached to a principal |
| Cloud Storage bucket | S3 bucket |
| Cloud Run or Cloud Functions | Lambda |
| Secret Manager | Secrets Manager |
| VPC | VPC |
| Cloud Audit Logs | CloudTrail |

The identity idea is the same on both: a workload should receive a role for the task, not a long-lived key with broad access.
