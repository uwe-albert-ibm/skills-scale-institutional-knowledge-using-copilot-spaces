# OctoAcme Personas — Expanded Roles

This document expands on the core roles defined in `octoacme-roles-and-personas.md` by adding five critical personas that are referenced throughout the project management processes but lack formal definitions.

---

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists ensure that all deliverables meet quality standards and acceptance criteria before release. They collaborate with developers and product teams to design comprehensive test strategies and execute testing activities across all stages of the project lifecycle.

### Responsibilities
- Design and execute comprehensive test plans aligned with acceptance criteria
- Automate tests for regression and critical user workflows
- Coordinate manual testing and user acceptance testing (UAT) efforts
- Report quality metrics, blockers, and test coverage status to the PM
- Participate in sprint reviews, release reviews, and pre-deployment verification
- Document test results, known issues, and defect reports
- Collaborate with developers to define testability requirements during planning
- Maintain test scripts, environments, and automation infrastructure

### Goals
- Ensure customer satisfaction through high-quality, defect-free releases
- Reduce production defects and support burden
- Maintain test coverage aligned with product risk and complexity
- Enable fast, confident delivery through automation

### Interactions with Other Roles
- **Developers**: Collaborate on acceptance criteria clarity, test requirements, and debugging failed tests
- **Product Manager**: Validate that quality meets product standards; align test priorities with release schedules
- **Project Manager**: Report quality status, identify schedule risks due to defects, and coordinate UAT timing
- **Release Manager**: Conduct pre-deployment smoke tests and verify readiness to production
- **Technical Lead**: Discuss test architecture, automation frameworks, and technical testing challenges

### Typical Communication
- Sprint planning and definition of done refinement
- Daily standups for blocker escalation and test status
- Quality dashboards and test reports (weekly or sprint-based)
- Post-release retrospectives focused on quality outcomes

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, strategic priorities, and organizational constraints. They provide direction, approve key project decisions, allocate resources, and receive regular status updates to ensure alignment with business objectives.

### Responsibilities
- Review and approve the Project One-pager and business case
- Participate in project initiation and decision gates (go/no-go)
- Provide business context, success metrics, and strategic priorities
- Escalate organizational and external blockers that affect delivery
- Receive and review monthly or milestone-based status reports
- Make final prioritization and scope trade-off decisions
- Champion the project internally and secure continued resource allocation
- Provide feedback on feature viability and business impact

### Goals
- Ensure project alignment with organizational strategy and business objectives
- Maximize return on investment (ROI) and minimize wasteful spend
- Reduce scope creep and timeline risk through clear governance
- Enable successful stakeholder adoption and change management

### Interactions with Other Roles
- **Project Manager**: Receives escalations, approvals, and status updates; provides steering and guidance
- **Product Manager**: Aligns on business success metrics and priority trade-offs
- **Developers & Delivery Team**: Occasional check-ins on feasibility; feedback on demos and releases
- **Sponsor (if different)**: Escalates critical decisions or resource conflicts

### Typical Communication
- Project kickoff and approval meetings
- Monthly stakeholder updates (status, risks, upcoming decisions)
- Decision and escalation emails
- Release announcements and user communication
- Ad-hoc meetings for scope changes or strategic shifts

---

## Security Lead / Officer

### Role Summary
Security Leads ensure that all deliverables meet security standards, compliance requirements, and organizational policies. They integrate security practices into the development and deployment lifecycle, lead incident response for security issues, and maintain organizational security posture.

### Responsibilities
- Configure and monitor security scanning tools in CI/CD pipelines
- Review security design and threat models during planning
- Conduct code reviews for security-sensitive changes
- Respond to and triage security incidents and vulnerabilities
- Track and verify compliance with regulatory requirements and audits
- Provide security guidance and training to the development team
- Maintain incident playbooks and escalation procedures
- Document and publish security advisories and patches
- Participate in release reviews to verify security controls

### Goals
- Prevent security breaches, data loss, and regulatory violations
- Maintain compliance with organizational and regulatory security standards (SOC2, GDPR, HIPAA, etc.)
- Reduce security-related production incidents and mean-time-to-detection (MTTD)
- Enable secure-by-design development practices

### Interactions with Other Roles
- **Developers**: Guidance on secure coding practices, review of security-sensitive changes
- **Product Manager**: Alert on security trade-offs; advise on privacy and data handling
- **Project Manager**: Report security risks, incident impact, and compliance timelines
- **Release Manager**: Pre-deployment security verification and incident response coordination
- **QA/Testing Specialist**: Coordinate security testing and vulnerability verification

### Typical Communication
- Weekly syncs on security scanning results and vulnerability trends
- Security incident notifications and updates (real-time escalation required)
- Code review participation for security-related features
- Compliance and audit reporting (quarterly or annual)
- Security training and awareness communications

---

## Release Manager / DevOps Engineer

### Role Summary
Release Managers and DevOps Engineers orchestrate the deployment process, manage infrastructure and environments, and ensure reliable, repeatable releases to production. They are responsible for minimizing deployment risk and reducing downtime.

### Responsibilities
- Design, build, and maintain deployment pipelines and automation
- Manage infrastructure, containerization, and environment configurations
- Schedule deployment windows and coordinate cross-team deployment timing
- Execute pre-deployment and post-deployment verification procedures
- Manage backups, disaster recovery, and rollback procedures
- Monitor deployment health, application metrics, and incident response
- Document deployment procedures, runbooks, and troubleshooting guides
- Collaborate with security on deployment security controls
- Optimize deployment speed and reliability through continuous improvement

### Goals
- Enable fast, reliable, and repeatable releases to production
- Minimize deployment-related incidents, rollbacks, and downtime
- Provide operational visibility and observability for all production systems
- Reduce manual intervention and operational toil through automation

### Interactions with Other Roles
- **Developers**: Coordinate on deployable artifacts, environment setup, and deployment requirements
- **Product Manager**: Align on release schedules and feature readiness
- **Project Manager**: Report on deployment readiness and coordinate release timing
- **QA/Testing Specialist**: Pre-deployment smoke tests and production verification
- **Security Lead**: Integrate security controls into deployment pipeline
- **On-Call Engineers**: Incident response and rollback execution

### Typical Communication
- Release planning and pre-deployment reviews (weekly or per-release)
- Deployment coordination and status updates (real-time during deploys)
- Incident response and post-mortem analysis (as needed)
- Infrastructure and operational metrics reporting (weekly dashboards)
- Deployment procedures and runbook documentation updates

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical guidance, make strategic design decisions, and ensure that implementations align with long-term technical vision and architectural principles. They mentor the team and reduce technical risk through foresight and design rigor.

### Responsibilities
- Participate in technical design reviews and architecture planning
- Guide developers on architectural patterns, design approaches, and technical best practices
- Identify and mitigate technical risks and dependencies early
- Collaborate with Product Manager on technical feasibility and trade-offs
- Mentor and coach developers on technical excellence and code quality
- Review and approve significant technical changes and architectural decisions
- Maintain technical documentation and architecture decision logs
- Evaluate and recommend new technologies, tools, and frameworks
- Participate in retrospectives to identify technical process improvements

### Goals
- Ensure scalable, maintainable, performant, and secure systems
- Reduce technical debt and rework through upfront design and planning
- Enable knowledge sharing and continuous team growth
- Minimize production incidents caused by architectural issues

### Interactions with Other Roles
- **Developers**: Technical mentorship, design review, and pair programming support
- **Product Manager**: Feasibility assessment and technical trade-off discussion
- **Project Manager**: Risk identification and timeline impact of technical decisions
- **QA/Testing Specialist**: Define testability requirements and test strategy
- **Security Lead**: Security architecture review and threat mitigation
- **Release Manager**: Review deployment architecture and operability

### Typical Communication
- Technical design discussions and code reviews (ongoing)
- Sprint planning and estimation participation
- Architecture decision records (ADRs) and design documentation
- Retrospectives and lessons learned sessions
- Mentoring sessions and technical office hours

---

## Role Interaction Matrix: Across the Project Lifecycle

| Lifecycle Phase | Key Interactions |
|---|---|
| **Initiation** | Sponsor → PM (approval); PdM ↔ Stakeholders (alignment); TL assists with feasibility |
| **Planning** | PM ↔ PdM (backlog refinement); TL + QA define DoD; Security reviews design |
| **Execution** | Devs ↔ QA (acceptance); TL mentors; PM removes blockers; RM assists with CI/CD |
| **Release** | QA ↔ RM (pre-flight); Security verifies; PdM ↔ Stakeholders (announcement) |
| **Retrospective** | PM facilitates; all roles contribute learnings; TL captures technical lessons |

---

## How to Use These Personas

1. **Persona Prompts for Copilot Spaces**: Reference these personas when setting up role-specific guidance in your Copilot Space.
2. **Project Staffing**: Use these definitions when allocating people to projects or roles.
3. **Process Documentation**: Link from existing process docs (e.g., `octoacme-execution-and-tracking.md`) to clarify which roles are involved.
4. **Scenario-Based Training**: Use these personas to frame scenarios and interactions in onboarding or skills exercises.
5. **Cross-Functional Alignment**: Share this document to clarify role boundaries and reduce confusion during project execution.

---

## Next Steps

- [ ] Review these expanded personas with your delivery teams
- [ ] Update existing process documents to explicitly reference these roles
- [ ] Create a role interaction matrix as a visual reference (e.g., RACI chart)
- [ ] Add persona prompts to the Copilot Space for role-specific guidance
- [ ] Incorporate these definitions into project checklists and onboarding materials
