# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (coordinated by Release Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared
- UX/UI review completed for user-facing changes
- Data instrumentation validated by Data Analyst
- Support documentation and training materials prepared by Support Lead

## Deployment Checklist
- [ ] Deployment window scheduled and communicated by Release Manager
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders (coordinated by Release Manager)
- [ ] Support team briefed and ready (coordinated by Support Lead)
- [ ] Monitoring dashboards reviewed (with Data Analyst)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
