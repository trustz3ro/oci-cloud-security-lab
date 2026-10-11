# OCI Cloud Security Lab

Author: Edward Johnson

## Overview

This repository documents my hands-on learning while completing the Oracle Cloud Infrastructure Foundations Associate learning path and preparing for exam 1Z0-1085-26.

My goal is to connect cloud fundamentals with practical security skills, including identity and access management, network security, monitoring, and cost awareness.

## Current status

- Learning path: starting
- Certification: in progress; not yet earned
- Hands-on labs: not yet completed

Study notes and proposed designs are labeled separately from completed, validated labs.

## Learning roadmap

- [ ] OCI architecture, regions, availability domains, and fault domains
- [ ] Tenancy, compartments, authentication, and authorization
- [ ] Virtual cloud networks, subnets, routing, and network security
- [ ] Compute, containers, and serverless concepts
- [ ] Object, block, and file storage
- [ ] Cloud Guard, security zones, encryption, and Vault
- [ ] Pricing, tagging, cost controls, and resource cleanup
- [ ] Complete available Oracle University hands-on labs
- [ ] Complete practice exam and certification exam

## Repository structure

| Folder | Purpose |
| --- | --- |
| `notes/` | Original study notes and concept summaries |
| `labs/` | Lab procedures, configuration decisions, validation, and cleanup |
| `diagrams/` | Proposed or implemented architecture diagrams, clearly labeled |
| `evidence/` | Sanitized screenshots and outputs supporting completed labs |

Use [the lab template](labs/lab-template.md) for each hands-on exercise.

## Planned portfolio work

1. Document an IAM and compartment exercise, including an allowed and denied access test when the lab permits it.
2. Diagram and document a basic VCN exercise with its routing and security decisions.
3. Document a compute or storage exercise with verification and cleanup steps.

These are planned exercises, not claims of completed work. Scope depends on access to the course lab environment.

## Connection to existing projects

- [Identity and Access Management Lab](https://github.com/trustz3ro/identity-access-management-lab): compare existing RBAC and access-review concepts with OCI IAM.
- [SOC Detection Engineering Lab](https://github.com/trustz3ro/soc-detection-engineering-lab): apply the same emphasis on validation and evidence to cloud security learning.

## Evidence and security practices

- Publish original explanations rather than copied course materials or exam questions.
- Never commit passwords, API keys, private keys, tokens, or credential files.
- Inspect screenshots and outputs before publishing; redact personal and sensitive account details.
- Only use authorized lab environments and resources.
- Record resource cleanup and any cost considerations for each lab.
- Distinguish course completion from certification achievement.

## Resources

- [Oracle MyLearn](https://mylearn.oracle.com/)
- [Oracle Cloud Infrastructure documentation](https://docs.oracle.com/en-us/iaas/Content/home.htm)
