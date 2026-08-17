# OctoAcme Project Management Documentation

## Overview
OctoAcme Project Management follows a structured, iterative approach focused on delivering customer value, clear ownership, and data-informed decisions. This repository's docs capture the lifecycle, roles, and templates the team uses to initiate, plan, execute, release, and learn from work—helping new teammates onboard quickly and providing a single source of truth for project processes.

## Table of Contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Project Management Processes Summary
OctoAcme runs projects through a clear lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation uses a Project One‑pager to capture problem, objectives, stakeholders, success metrics, and a high‑level timeline. Planning converts that into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone plan. These artifacts ensure alignment before work begins.

Day‑to‑day execution is organized on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and governed by small, well-scoped pull requests that include acceptance criteria and run automated CI checks. Quality is assured with unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA as needed. Releases follow a standardized checklist—deploy to staging, smoke-test, deploy to production (automated when possible), then run post-deploy verifications and announce results.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedule, risks, and communications; Developers implement and test; QA validates acceptance; Stakeholders provide inputs and approvals. Communication cadence is structured—daily standups for blockers, weekly delivery syncs, regular PM–PdM alignment, sprint demos/reviews, and monthly stakeholder updates—while a simple risk register and escalation path (team → PM → Product Lead → Sponsor) keep stakeholders informed and issues escalated appropriately.

## Key Artifacts & How to Use These Docs
- Project One‑pager / Charter — required at initiation (see Project Initiation)
- Backlog items with acceptance criteria — used during planning & sprinting (see Project Planning)
- Project board & release plan — used during Execution & Tracking
- Risk register & communication templates — used for stakeholder updates and incident comms
- Release notes & rollback plan — used at Release & Deployment
- Retrospective notes & tracked action items — used to continuously improve

How to navigate:
- New team members: start with the Project Management Overview and Roles & Personas docs.
- At kickoff: follow Project Initiation and Project Planning.
- During work: reference Execution & Tracking and Risk Management.
- For releases and project close: follow Release & Deployment and Retrospective & Continuous Improvement.
