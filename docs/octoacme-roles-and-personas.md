# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop test plans aligned with feature acceptance criteria
- Define and execute manual and automated testing strategies
- Manage regression testing and smoke test procedures
- Track and triage bugs and quality blockers
- Participate in sprint planning and release readiness assessments
- Collaborate with developers on test automation frameworks

### Goals
- Catch defects early to prevent production incidents
- Reduce time spent in QA cycles through better test automation
- Ensure features meet user and business quality expectations
- Build a culture of quality ownership across the team

### Typical Communication
- Sprint planning and daily standups
- Test case reviews and bug triage sessions
- Release readiness sign-off
- Quality metrics and trend reporting

### Interaction with Other Roles
- Works closely with **Developers** on testability and test strategy
- Aligns with **Product Managers** on acceptance criteria
- Reports quality blockers to **Project Managers** and **Technical Leads**

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business priorities, funding authority, and end-user needs. They approve project direction, accept deliverables, and remove high-level blockers.

### Responsibilities
- Approve project charter and success metrics
- Provide business context and priority decisions
- Accept completed work and features
- Remove organizational blockers and resource constraints
- Attend milestone reviews and escalated risk discussions
- Define business value and ROI expectations

### Goals
- Ensure project delivers measurable business value
- Maintain alignment between delivery and strategy
- Reduce project delays due to organizational issues
- Maximize return on investment

### Typical Communication
- Milestone and release reviews
- Monthly stakeholder updates
- Escalation and decision requests
- Executive status briefings

### Interaction with Other Roles
- Provides direction to **Project Managers** and **Product Managers**
- Reviews outcomes against **Project Managers' Risk Registers**
- Approves major decisions and resource needs

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects define technical strategy, review design decisions, and ensure system scalability and reliability. They mentor developers on technical best practices.

### Responsibilities
- Design system architecture and technology choices
- Review technical designs and major refactoring proposals
- Identify technical risks and propose mitigation strategies
- Mentor developers and establish coding standards
- Participate in architecture reviews and cross-team technical discussions
- Evaluate build vs. buy decisions and third-party integrations

### Goals
- Build scalable, maintainable, and performant systems
- Reduce technical debt and system complexity
- Establish patterns and shared knowledge across teams
- Enable team velocity through technical enablement

### Typical Communication
- Technical design reviews and architecture discussions
- Risk register reviews (technical risks)
- Code reviews and mentoring
- Technical documentation and decision records

### Interaction with Other Roles
- Guides **Developers** on architecture and design decisions
- Identifies technical risks for **Project Managers' Risk Registers**
- Collaborates with **QA/Testing Lead** on testability and performance validation
- Advises **Product Managers** on technical feasibility and trade-offs

---

## Release Manager/DevOps Engineer

### Role Summary
Release Managers/DevOps Engineers own release planning, deployment automation, and production stability. They ensure smooth, low-risk deployments and incident response.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Maintain deployment pipelines, automation, and infrastructure
- Execute deployments and manage rollbacks if needed
- Monitor production health and respond to incidents
- Document release notes and post-deploy verification procedures
- Manage infrastructure as code and deployment environments

### Goals
- Enable frequent, safe deployments with minimal downtime
- Reduce mean time to resolution (MTTR) for production issues
- Maintain high system availability and performance
- Automate and streamline release processes

### Typical Communication
- Release planning meetings and go/no-go decisions
- Deployment checklists and post-release verifications
- Incident response and status updates
- Infrastructure and deployment metrics

### Interaction with Other Roles
- Coordinates with **Project Managers** on release scheduling
- Works with **Developers** on deployment readiness and rollback procedures
- Validates **QA/Testing Lead's** smoke tests before production deployment
- Reports production health to **Stakeholders/Sponsors** on escalations

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate agile ceremonies, remove process blockers, and coach teams on continuous improvement. They ensure the team operates effectively within its process framework.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Help teams identify and address process improvements
- Remove impediments blocking team progress
- Coach teams on agile principles and healthy team dynamics
- Track sprint metrics and iteration health
- Foster psychological safety and continuous learning

### Goals
- Maximize team velocity and flow through process optimization
- Build a culture of continuous improvement and psychological safety
- Reduce unplanned work and context switching
- Enable self-organizing, high-performing teams

### Typical Communication
- Agile ceremonies and team meetings
- Retrospective action item tracking
- One-on-ones and coaching conversations
- Metrics and team health reports

### Interaction with Other Roles
- Supports all roles in removing blockers and improving processes
- Escalates team impediments to **Project Managers**
- Facilitates collaboration between **Developers**, **QA/Testing Lead**, and **Technical Leads**
- Tracks action items from retrospectives and follows up with the team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to these role definitions when establishing communication patterns and escalation paths in project planning.
