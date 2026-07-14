# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management process documents and provides a concise summary of the processes used across projects to help teammates discover guidance quickly and standardize onboarding references.

## Overview

- Initiation: Create a Project One-pager that captures the problem statement, objective/goal, success metrics, stakeholders, and a high-level timeline. Confirm go/no-go before moving into planning.
- Planning: Run a kickoff, build a prioritized backlog with acceptance criteria, estimate scope, define the Definition of Done, and document risks and dependencies.
- Execution & Tracking: Manage work on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Use small PR practices, include acceptance criteria in PRs, run CI and security scans, and track progress through daily standups and a weekly delivery sync. Escalate blockers via documented escalation levels.
- Release & Deployment: Follow the release checklist (CI, security scans, smoke tests, rollback plan), perform post-deploy verifications, and announce releases to stakeholders.
- Retrospectives & Continuous Improvement: Run retros after sprints/releases/incidents, create action items with owners and due dates, and track improvements through the backlog and weekly PM syncs.

## Key workflows and quality practices

- Pull requests: Keep PRs small (<= 400 lines when possible), link to the related issue, include acceptance criteria, run automated tests and linters in CI, and require at least one approval prior to merging.
- Testing: Unit and integration tests as applicable; end-to-end smoke tests for critical flows before release; manual QA for feature acceptance when needed. Security scanning is part of CI.
- Roles & ownership: Each project has a named Project Manager (PM) and Product Lead (PdM). Developers, QA, and stakeholders have clear responsibilities and communication expectations.
- Communication cadence: Daily standups (15 min), weekly delivery syncs, demos/reviews at the end of each sprint or milestone, and monthly stakeholder updates or milestone-based communications.

## Docs (linked)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use this folder

- Use this README as the single entry point for process guidance.
- Reference these docs in project templates, onboarding materials, and .copilot/ context for Copilot Spaces.
- Keep each document versioned in the repo and link to specific docs from project READMEs or templates where relevant.
