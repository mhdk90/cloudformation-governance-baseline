# Infrastructure Governance with CloudFormation

## Overview
This project demonstrates a reusable CloudFormation governance baseline with secure-by-default S3 settings and least-privilege IAM controls.

## Goal
Show how infrastructure governance can be standardized through YAML-based Infrastructure as Code.

## Current Scope
- Secure S3 bucket
- Default encryption
- Block public access
- Bucket versioning
- Least-privilege IAM policy
- Read-only audit role

## Repository Structure
- `cloudformation/` – CloudFormation YAML templates
- `docs/` – notes and architecture explanations

## Security Notes
- No secrets are stored in this repository
- Environment-specific values should be passed as parameters
- Public access is blocked by design

## Planned Next Steps
- Add CloudTrail baseline
- Add StackSet version for multi-account rollout
- Add architecture diagram
- Add design decisions

## What I Learned
- How to define governance controls in YAML
- How to apply secure-by-default S3 settings
- How to design least-privilege IAM access
- How to present infrastructure governance work on GitHub
