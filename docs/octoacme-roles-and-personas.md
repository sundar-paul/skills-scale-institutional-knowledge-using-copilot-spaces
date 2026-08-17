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
QA/Testing Leads own quality strategy, test planning, and acceptance validation for projects. They collaborate with Product Managers on acceptance criteria and with Developers to ensure testability.

### Responsibilities
- Define test strategy and test plan aligned with release scope
- Create and maintain acceptance test cases and scenarios
- Conduct manual QA and acceptance testing
- Coordinate automated testing in CI pipelines
- Document and triage defects
- Validate "Definition of Done" criteria
- Participate in release readiness and smoke testing

### Goals
- Ensure features meet acceptance criteria before release
- Identify quality issues early to reduce rework
- Build confidence in release readiness

### Typical Communication
- Sprint planning (acceptance criteria review)
- Daily standups (test status and blockers)
- Pre-release readiness reviews
- Defect triage and prioritization

### Interactions with Existing Roles
- **With Developers**: Collaborate on test design and ensure code is testable; provide early feedback on quality issues
- **With Product Managers**: Validate acceptance criteria and confirm feature completion; escalate quality blockers
- **With Project Managers**: Provide test status updates and identify timeline risks related to quality

---

## Technical Architect/Tech Lead

### Role Summary
Technical Architects/Tech Leads guide technical strategy, design decisions, and risk mitigation. They ensure solutions are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Evaluate technical approach and architecture decisions
- Identify technical risks and propose mitigations
- Conduct or lead technical design reviews
- Define coding standards and best practices
- Mentor developers on technical excellence
- Collaborate with DevOps on deployment and scalability concerns

### Goals
- Ensure technical solutions are robust and maintainable
- Reduce technical debt and rework
- Build scalable, observable systems

### Typical Communication
- Design reviews and technical discussions
- Risk assessments during planning
- Architecture decision records (ADRs)
- Code review and mentoring

### Interactions with Existing Roles
- **With Developers**: Lead technical design decisions; conduct code reviews; mentor on best practices
- **With Product Managers**: Advise on technical feasibility and trade-offs; validate that designs align with product goals
- **With Project Managers**: Identify technical risks and dependencies; provide estimates and timeline impact assessment

---

## Scrum Master/Delivery Facilitator

### Role Summary
Scrum Masters/Delivery Facilitators enable team velocity and health by facilitating ceremonies, removing blockers, and coaching the team on agile practices. They work closely with Project Managers but focus on team dynamics and process execution.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove team blockers and impediments
- Coach team members on agile practices and ceremonies
- Monitor team health and engagement
- Track sprint metrics and velocity
- Protect team focus and minimize distractions

### Goals
- Maximize team velocity and predictability
- Improve team collaboration and psychological safety
- Ensure continuous process improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- One-on-ones with team members
- Blocker escalation to Project Managers

### Interactions with Existing Roles
- **With Developers**: Remove blockers; facilitate ceremonies; support team growth
- **With Product Managers**: Ensure product backlog is well-refined; coordinate on story acceptance
- **With Project Managers**: Communicate team velocity and capacity; escalate schedule risks; support risk mitigation planning

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide executive oversight, business alignment, and decision-making authority. They approve project initiation, allocate resources, and serve as escalation points for business-impacting issues.

### Responsibilities
- Approve project charter and business case
- Allocate resources, budget, and personnel
- Make priority and trade-off decisions when conflicts arise
- Serve as escalation point for business-impacting issues
- Ensure alignment with organizational strategy
- Attend key milestone reviews, demos, and decision gates

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment across the organization
- Remove organizational and political blockers
- Manage stakeholder expectations

### Typical Communication
- Initiation and decision gate reviews
- Monthly or milestone-based stakeholder updates
- Escalated risks and critical blockers
- Release announcements and post-release reviews

### Interactions with Existing Roles
- **With Project Managers**: Provide guidance on priorities; approve major changes; escalate unresolved issues
- **With Product Managers**: Align on business outcomes and success metrics; approve roadmap priorities
- **With Developers**: Attend demos and releases; understand technical constraints on timelines

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers manage security risks, compliance requirements, and security reviews. They ensure projects meet organizational and regulatory security standards.

### Responsibilities
- Define security and compliance requirements for projects
- Conduct security reviews and threat assessments
- Manage security incident response and escalation
- Ensure compliance with regulatory and organizational policies
- Coordinate security testing and penetration testing
- Provide security guidance during design and implementation phases

### Goals
- Minimize security and compliance risks
- Ensure projects meet organizational security standards
- Support incident response and post-incident learning
- Build a security-aware culture

### Typical Communication
- Security design reviews and threat assessments
- Compliance requirement documentation
- Incident response and escalation
- Security training and awareness sessions

### Interactions with Existing Roles
- **With Developers**: Provide security guidance; review code for vulnerabilities; support secure development practices
- **With Technical Architects**: Collaborate on security architecture and design decisions
- **With Project Managers**: Escalate security risks; provide timeline impact of security activities; coordinate security reviews

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers manage deployment pipelines, infrastructure, production observability, and operational readiness. They ensure reliable, scalable, and observable systems.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Manage production and staging environments
- Implement monitoring, logging, and alerting
- Conduct capacity planning and scalability assessments
- Manage infrastructure as code and configuration management
- Provide operational support for releases and incident response

### Goals
- Enable fast, reliable, and safe deployments
- Maintain system performance, availability, and scalability
- Provide observability and incident response capabilities
- Reduce operational overhead and toil

### Typical Communication
- Release planning and pre-deployment reviews
- Infrastructure and capacity discussions
- Monitoring dashboards and alerting
- Incident response and post-incident reviews

### Interactions with Existing Roles
- **With Developers**: Support deployment process; provide infrastructure feedback; enable fast local development environments
- **With Technical Architects**: Collaborate on architecture decisions; assess scalability and observability requirements
- **With Project Managers**: Provide deployment risk assessment; coordinate release windows; escalate infrastructure blockers

---

## Release Manager/Release Engineer

### Role Summary
Release Managers/Release Engineers own the end-to-end release process, from planning and sequencing through deployment and post-release verification. They coordinate across teams to ensure safe, timely, and well-communicated releases.

### Responsibilities
- Plan release schedule, coordinate dependencies, and manage release sequencing
- Maintain release documentation and release notes
- Coordinate pre-release testing and approval gates
- Execute or oversee deployment to staging and production environments
- Coordinate post-deployment verification and rollback procedures if needed
- Communicate release status to stakeholders and support teams
- Manage version numbering and release artifacts
- Identify and mitigate release-related risks

### Goals
- Enable fast, safe, and predictable releases
- Minimize release-related downtime and incidents
- Ensure stakeholders and support teams are prepared for releases
- Reduce manual, error-prone release activities

### Typical Communication
- Release planning meetings with Product and Project leads
- Pre-release coordination with QA, DevOps, and support teams
- Release announcement to stakeholders and customers
- Post-release retrospectives

### Interactions with Existing Roles
- **With DevOps/Infrastructure**: Coordinate deployment timing, rollback procedures, and monitoring setup
- **With Project Managers**: Align on release timeline and dependencies; escalate release risks
- **With QA/Testing**: Ensure release testing is complete and approval gates are met
- **With Product Managers**: Communicate release contents and user-facing impacts
- **With Customer Success/Support**: Prepare support teams with release notes and known issues

---

## UX/Design Lead

### Role Summary
UX/Design Leads ensure that delivered features are user-centered, accessible, and meet usability standards. They collaborate with Product Managers on design vision and with Developers on implementation.

### Responsibilities
- Define user experience strategy and design principles
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Review designs for accessibility (WCAG compliance, etc.)
- Collaborate with developers on feasibility and implementation
- Validate that delivered features match design intent
- Document design decisions and rationale

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs early
- Build user confidence and satisfaction

### Typical Communication
- Design reviews with developers and product managers
- User research findings and feedback
- Design system and component library maintenance
- Acceptance testing of UX elements

### Interactions with Existing Roles
- **With Product Managers**: Align on user needs and feature vision; validate design approach
- **With Developers**: Review implementation against design specs; provide design feedback during development
- **With QA/Testing**: Define acceptance criteria for UX and conduct usability testing
- **With Customer Success/Support**: Gather user feedback to inform design improvements

---

## Business Analyst

### Role Summary
Business Analysts gather, clarify, and document business requirements. They bridge business stakeholders and technical teams, ensuring alignment on problem statements, scope, and success criteria.

### Responsibilities
- Conduct interviews and workshops with business stakeholders
- Document business requirements and process flows
- Create requirement specifications and acceptance criteria
- Clarify ambiguous requirements and identify edge cases
- Validate that solutions address original business problems
- Support traceability of requirements through implementation

### Goals
- Ensure solutions address actual business needs, not assumed needs
- Reduce rework caused by misunderstood requirements
- Improve communication between business and technical teams

### Typical Communication
- Requirements gathering meetings with stakeholders
- Requirement documentation and specifications
- Clarification and scope negotiation during planning
- Validation and sign-off of deliverables

### Interactions with Existing Roles
- **With Product Managers**: Collaborate on problem statement and requirements; ensure alignment
- **With Project Managers**: Support scope documentation and change management
- **With Developers**: Clarify requirements and answer implementation questions
- **With Stakeholders**: Gather business context and validate solutions

---

## Systems Administrator

### Role Summary
Systems Administrators manage infrastructure access, user provisioning, system configurations, and operational support. They ensure systems are secure, available, and properly configured for project needs.

### Responsibilities
- Manage user accounts, access controls, and permissions
- Configure and maintain system environments (dev, staging, production)
- Provide infrastructure documentation and runbooks
- Support incident response and system troubleshooting
- Coordinate backup and disaster recovery procedures
- Ensure compliance with security and operational policies
- Manage system updates and patches

### Goals
- Maintain system availability and performance
- Ensure secure access and compliance
- Reduce operational friction and support tickets
- Enable fast and reliable infrastructure for project teams

### Typical Communication
- Infrastructure and access request processing
- Operational runbooks and documentation
- Incident escalation and support coordination
- Security and compliance audits

### Interactions with Existing Roles
- **With DevOps/Infrastructure**: Collaborate on infrastructure setup and maintenance; coordinate system changes
- **With Security/Compliance**: Ensure access controls align with security policies
- **With Project Managers**: Support onboarding and infrastructure provisioning; escalate access-related blockers
- **With Developers**: Provide infrastructure documentation; support development environment setup

---

## Data Analyst

### Role Summary
Data Analysts track project metrics, analyze project health, and provide insights for data-driven decisions. They ensure teams have visibility into progress, quality, and business impact.

### Responsibilities
- Design and implement project dashboards and metrics tracking
- Collect and analyze project health metrics (velocity, burndown, quality)
- Analyze success metrics defined in the Project One-pager
- Provide reporting for stakeholders and sponsors
- Identify trends and risks through data analysis
- Support root cause analysis for issues and incidents
- Maintain data integrity and documentation

### Goals
- Provide data-driven visibility into project health
- Enable informed decision-making through analytics
- Identify risks and opportunities early
- Support continuous improvement with metrics

### Typical Communication
- Dashboard reviews and metric discussions
- Weekly status reports with key metrics
- Analysis and trend identification
- Post-release impact assessments

### Interactions with Existing Roles
- **With Project Managers**: Provide project health dashboards; identify timeline and quality risks
- **With Product Managers**: Track success metrics and business impact; validate product outcomes
- **With Scrum Master/Delivery Facilitator**: Monitor team velocity and capacity; support retrospective data
- **With QA/Testing**: Analyze quality metrics and defect trends

---

## Legal/Compliance Specialist

### Role Summary
Legal/Compliance Specialists address regulatory and contractual requirements for projects. They ensure projects comply with legal obligations and organizational policies.

### Responsibilities
- Review contracts and regulatory requirements for projects
- Advise on legal and compliance implications of project scope
- Conduct compliance assessments and audits
- Manage intellectual property and licensing concerns
- Coordinate with external legal counsel when needed
- Document compliance decisions and approvals
- Provide training and guidance on compliance requirements

### Goals
- Minimize legal and compliance risks
- Ensure projects meet regulatory obligations
- Protect organizational interests and reputation
- Enable compliant, risk-managed project execution

### Typical Communication
- Legal review meetings and consultations
- Compliance requirement documentation
- Risk assessments and compliance audits
- Policy and procedure updates

### Interactions with Existing Roles
- **With Stakeholders/Sponsors**: Advise on legal and compliance implications; escalate regulatory risks
- **With Product Managers**: Review product features for legal/compliance concerns
- **With Security/Compliance Officer**: Collaborate on compliance requirements and audits
- **With Project Managers**: Identify legal/compliance risks and timeline impacts

---

## Customer Success/Support Lead

### Role Summary
Customer Success/Support Leads represent customer needs, coordinate support readiness, and provide user feedback to the team. They bridge the gap between customer experience and product delivery.

### Responsibilities
- Gather customer feedback and pain points
- Coordinate support team readiness for new features
- Create support documentation and knowledge bases
- Identify usability issues and customer concerns
- Advocate for customer needs during planning and execution
- Support release preparation and customer communication
- Track customer satisfaction and support metrics

### Goals
- Ensure customer success with delivered features
- Reduce support volume through better documentation and design
- Provide customer-driven insights for improvements
- Build customer confidence and satisfaction

### Typical Communication
- Customer feedback sessions and interviews
- Support readiness reviews and planning
- Customer communication and release announcements
- Support metrics and customer satisfaction reporting

### Interactions with Existing Roles
- **With Product Managers**: Provide customer feedback and insights; advocate for customer-focused prioritization
- **With UX/Design Leads**: Share customer usability feedback; support design validation
- **With QA/Testing**: Coordinate acceptance criteria from customer perspective
- **With Release Manager/Release Engineer**: Prepare customer communications and support materials
- **With Project Managers**: Communicate customer impact and timeline concerns

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When working on projects, identify which personas are involved and use this document to clarify roles, responsibilities, and communication patterns.
