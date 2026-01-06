# OctoAcme Project Management Docs

## Overview
This README provides a single entrypoint to OctoAcme's project management process documentation. It summarizes our core project lifecycle, principles, and key artifacts, and links to detailed process pages in this folder. These docs are intended to make onboarding faster, improve transparency, and provide repeatable checklists and templates for consistent delivery.

## Quick Links
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution &amp; Tracking](octoacme-execution-and-tracking.md)
- [Risk Management &amp; Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles &amp; Personas](octoacme-roles-and-personas.md)

## Brief Overview of OctoAcme Project Management Processes
- Lifecycle: Initiation → Planning → Execution → Release → Close &amp; Retrospective
- Initiation: Capture the problem, stakeholders, success metrics, and decide whether to proceed.
- Planning: Break approved work into prioritized backlog items, estimate, identify dependencies and risks, and create a release/milestone plan.
- Execution: Implement in small increments, use PR-based review and CI, run tests, track progress on a project board, and escalate blockers through defined paths.
- Release: Follow pre-release checks (tests, security scans, release notes), deploy through automated pipelines where possible, and run post-deploy verifications and communications.
- Retrospective: Run timeboxed retrospectives, create 1–3 action items, track improvements, and feed learnings back into planning.

## Key Artifacts &amp; Where to Find Them
- Project One-pager / Charter: see Project Initiation Guide
- Backlog &amp; Sprint Plan: see Project Planning
- Risk Register &amp; Communication templates: see Risk Management &amp; Communication
- Release notes &amp; rollback plans: see Release &amp; Deployment Guide
- Retrospective notes &amp; action items: see Retrospective &amp; Continuous Improvement

## How to Use and Contribute
- Keep process documents in this docs/ folder and link new artifacts from this README.
- Use the GitHub Issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose edits or additions to these process docs.
- Add process-specific content into .copilot/ if you want Copilot Spaces to use them as contextual inputs.

## Acceptance Criteria
- Content aligns with the existing process docs in this folder.
- The README improves discoverability and provides clear links to all process pages.
- The change is reviewed by project stakeholders as needed.
