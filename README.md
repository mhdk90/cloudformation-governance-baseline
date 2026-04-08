# Infrastructure Governance with CloudFormation

## Overview
Reusable CloudFormation governance baseline with secure-by-default S3 configuration and least-privilege IAM controls.

## Goal
Standardize core governance controls through YAML-based Infrastructure as Code.

## Current Scope
- Secure S3 baseline
- Public access block
- Default encryption
- Versioning
- Least-privilege IAM role/policy

## Repository Structure
- `cloudformation/` – templates
- `docs/` – design notes and architecture

## Deployment
Add your deploy command here.

## Security Notes
- No secrets are stored in this repository
- Environment-specific values are parameterized
- Public access is blocked by design

## Roadmap
- Add CloudTrail baseline
- Add StackSet version
- Add CI
- Add architecture diagram
