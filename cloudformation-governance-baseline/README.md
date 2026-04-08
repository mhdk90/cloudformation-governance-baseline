\# Infrastructure Governance with CloudFormation



\## Overview

This project demonstrates a reusable CloudFormation governance baseline with secure-by-default S3 settings and least-privilege IAM controls.



\## Goal

Show how infrastructure governance can be standardized through YAML-based Infrastructure as Code.



\## Current Scope

\- Secure S3 bucket

\- Default encryption

\- Block public access

\- Bucket versioning

\- Least-privilege IAM managed policy

\- Read-only audit role



\## Why This Matters

Cloud governance is not only about creating resources. It is also about defining reusable security and access patterns that can be applied consistently.



\## Files

\- `cloudformation/secure-baseline.yaml` – baseline governance template

\- `docs/` – notes and later architecture diagrams



\## Services Covered

\- AWS CloudFormation

\- Amazon S3

\- AWS IAM



\## Planned Next Steps

\- Add StackSet version for multi-account rollout

\- Add CloudTrail baseline

\- Add tagging policy examples

\- Add architecture diagram



\## What I Learned

\- How to define governance controls in YAML

\- How to apply secure-by-default S3 settings

\- How to design least-privilege IAM access

\- How to present infrastructure governance work on GitHub

