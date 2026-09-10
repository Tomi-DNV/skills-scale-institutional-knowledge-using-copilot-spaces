# OctoAcme Project Management Docs

## Overview
OctoAcme follows a structured five-phase project lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. Each phase has clear deliverables and decision gates. During Initiation, teams validate business need, define success metrics, and align stakeholders around a lightweight Project One-pager. Planning transforms approved initiatives into actionable backlogs with prioritized work items, estimated scope, dependencies, and a release timeline. This governance approach emphasizes iterative delivery of small, testable increments while maintaining clear ownership through dedicated Project Managers and Product Managers who coordinate delivery and define outcomes respectively.

OctoAcme organizes around three core personas: Developers (who design, build, and test features), Product Managers (who define what should be built and prioritize the roadmap), and Project Managers (who coordinate delivery, manage risks, and enable team efficiency). Communication happens through a consistent cadence: daily standups (15 minutes) for progress and blockers, weekly syncs between PM and Product Lead, twice-weekly team standups, and monthly stakeholder updates. The organization maintains a single source of truth through project boards (e.g., GitHub Projects) with standardized columns—Backlog, Ready, In Progress, In Review, QA, Done—ensuring transparency and alignment across distributed teams.

Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release. All pull requests must follow a small-PR discipline (≤400 lines when possible), include issue links and acceptance criteria in descriptions, pass automated tests and linting in CI, and require at least one approval before merging. Pre-release requirements include passing security scans, drafted release notes, and a documented rollback plan. This rigorous approach minimizes production risk while maintaining velocity.

OctoAcme proactively manages risks through a maintained Risk Register (capturing ID, description, impact, probability, owner, and mitigation) that is reviewed weekly during syncs. Escalation follows three levels: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. After each sprint, release, or milestone, teams conduct retrospectives (45–75 minutes) to capture learnings, identify improvements, and track action items. This culture of continuous improvement, paired with data-informed decision-making and psychological safety, enables OctoAcme to iterate rapidly while maintaining high quality and stakeholder confidence.

## Table of Contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Core Principles
- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has named PM and Product Lead roles.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

## Quick Start
If you're new to OctoAcme project delivery, start with the [Project Management Overview](./octoacme-project-management-overview.md) for the full lifecycle, then review [Roles and Personas](./octoacme-roles-and-personas.md) to understand responsibilities. Next, read [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) before joining active work in [Execution and Tracking](./octoacme-execution-and-tracking.md). Use the release, risk, and retrospective guides as phase-specific references during delivery.

## Key Artifacts
- **Project One-pager / Charter:** Captures the problem, goal, success metrics, stakeholders, and initial timeline during initiation.
- **Backlog and release plan:** Translate approved work into prioritized items, scope, dependencies, and milestones during planning.
- **Project board:** Serves as the single source of truth across Backlog, Ready, In Progress, In Review, QA, and Done.
- **Risk Register:** Tracks ID, description, impact, probability, owner, and mitigation for ongoing risk management.
- **Release notes and rollback plan:** Required before production deployment to reduce release risk.
- **Retrospective notes and action items:** Preserve learnings and follow-through after each sprint, release, or milestone.
