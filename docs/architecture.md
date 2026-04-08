# Architecture

```mermaid
flowchart TD
    CF[CloudFormation] --> S3[Secure S3 Baseline]
    CF --> IAM[Audit Role + Managed Policy]
    CF --> CT[CloudTrail Baseline]
    CT --> LOGS[S3 Log Bucket]
    SS[StackSet - planned] --> ACC[Multiple Accounts / Regions]
