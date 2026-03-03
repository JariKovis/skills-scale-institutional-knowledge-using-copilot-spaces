# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. For handoff ownership across lifecycle stages, see [octoacme-handoffs-and-ownership-checklist.md](octoacme-handoffs-and-ownership-checklist.md).

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

## UX/UI Designer

### Role Summary
UX/UI Designers shape the user experience by defining interaction flows, creating wireframes and prototypes, and ensuring user-centric design throughout the product lifecycle.

### Responsibilities
- Define user flows, wireframes, and high-fidelity prototypes
- Conduct usability research and testing
- Collaborate with Product Managers on feature requirements and acceptance criteria
- Review implementations with Developers to ensure design fidelity
- Participate in QA validation for usability and accessibility

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by surfacing design concerns early
- Bridge user research and technical implementation

### Typical Communication
- Design critiques and review sessions with PdM and Developers
- Prototype handoffs via design tools (e.g., Figma)
- Usability test summaries shared with PdM and QA

### Lifecycle Touchpoints
- **Initiation**: Contributes to problem statement and user research
- **Planning**: Defines UX scope, wireframes, and acceptance criteria for UI stories
- **Execution**: Collaborates with Developers on implementation; reviews PRs for design accuracy
- **Release**: Validates final UI against approved designs; reviews release notes for user impact
- **Retrospective**: Shares usability findings and design process improvements

---

## Quality Assurance (QA) Engineer

### Role Summary
QA Engineers define test strategies, execute manual and automated tests, and ensure features meet acceptance criteria before release. They are embedded throughout the development process.

### Responsibilities
- Define and maintain test plans, test cases, and automated test suites
- Conduct functional, regression, and exploratory testing
- Track and coordinate defect resolution with Developers
- Validate that acceptance criteria are met for each story/feature
- Contribute to CI pipeline quality gates

### Goals
- Prevent defects from reaching production
- Increase automated test coverage over time
- Ensure consistent quality across releases

### Typical Communication
- Sprint ceremonies: planning, standups, and reviews
- Defect reports and triage sessions with Developers and PM
- QA sign-off notes shared with PdM and Project Manager before release

### Lifecycle Touchpoints
- **Initiation**: Reviews high-level requirements for testability
- **Planning**: Drafts initial test plan and identifies QA resource needs
- **Execution**: Performs continuous testing within each sprint; flags blockers early
- **Release**: Executes release readiness testing and provides go/no-go input
- **Retrospective**: Reports on defect trends and suggests quality improvements

---

## DevOps / Site Reliability Engineer (SRE)

### Role Summary
DevOps/SRE Engineers maintain CI/CD pipelines, manage infrastructure as code, automate deployments, and monitor system reliability to support fast, safe delivery.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and configuration as code
- Monitor reliability metrics (uptime, latency, error rates)
- Coordinate rollback and incident response procedures
- Support Developers and QA with environment access and tooling

### Goals
- Reduce deployment risk and time-to-production
- Maintain system reliability and observability
- Enable self-service capabilities for development teams

### Typical Communication
- Infrastructure change requests and runbooks shared with Developers and PM
- On-call rotation and incident retrospectives
- Deployment readiness checks with QA and Project Manager

### Lifecycle Touchpoints
- **Initiation**: Identifies infrastructure requirements and constraints
- **Planning**: Estimates DevOps work items; reviews release plan for infrastructure impact
- **Execution**: Maintains pipeline health; supports developer tooling and environment parity
- **Release**: Executes and monitors deployments; confirms rollback readiness
- **Retrospective**: Reviews deployment metrics and incident data for process improvements

---

## Business Analyst

### Role Summary
Business Analysts gather and articulate business requirements, clarify user stories, and ensure alignment between business needs and technical solutions throughout the project.

### Responsibilities
- Elicit, document, and validate business requirements with stakeholders
- Translate business needs into clear user stories and acceptance criteria
- Facilitate requirements workshops and stakeholder sessions
- Identify gaps, conflicts, or ambiguities in requirements
- Support Product Manager in backlog refinement

### Goals
- Ensure technical solutions address underlying business problems
- Reduce ambiguity and rework caused by unclear requirements
- Maintain a shared understanding across business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written requirements documents, user stories, and process flows shared with PdM and PM
- Clarification threads in project backlog items

### Lifecycle Touchpoints
- **Initiation**: Leads stakeholder analysis and documents business requirements
- **Planning**: Refines user stories with acceptance criteria; identifies process dependencies
- **Execution**: Available for requirements clarification; reviews implemented features for business alignment
- **Release**: Validates release notes and user communications against business requirements
- **Retrospective**: Reviews whether requirements processes led to clear outcomes

---

## Customer Support Liaison

### Role Summary
Customer Support Liaisons bring front-line customer insights into the project, advocate for customer needs, and ensure feedback loops between end users and the product team are active and actionable.

### Responsibilities
- Surface recurring customer issues and feedback to Product Management and QA
- Contribute to release readiness by reviewing documentation and support materials
- Participate in incident retrospectives to represent the customer impact perspective
- Maintain knowledge base articles and internal support runbooks
- Coordinate with QA when customer-reported bugs need reproduction and validation

### Goals
- Reduce support ticket volume through proactive documentation and product improvements
- Ensure customer impact is considered in prioritization and release decisions
- Close the feedback loop between customers and the development team

### Typical Communication
- Regular syncs with PdM to share customer feedback themes
- Release preview briefings to prepare support team for new features
- Incident reports and post-mortems involving customer impact

### Lifecycle Touchpoints
- **Initiation**: Provides customer problem data and common pain points
- **Planning**: Reviews planned features for support readiness implications
- **Execution**: Prepares support documentation in parallel with development
- **Release**: Reviews release notes; trains support team on new capabilities
- **Retrospective**: Shares post-release customer satisfaction data and recurring issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [octoacme-handoffs-and-ownership-checklist.md](octoacme-handoffs-and-ownership-checklist.md) for how these roles interact at key project handoff points.

