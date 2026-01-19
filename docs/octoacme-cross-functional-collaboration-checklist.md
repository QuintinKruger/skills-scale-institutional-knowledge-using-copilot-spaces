# OctoAcme — Cross-Functional Collaboration Checklist

## Purpose
Ensure effective collaboration and handoffs across all project roles, particularly when engaging specialized team members. Use this checklist to identify which roles need to be involved at different project phases and what deliverables they need from each other.

## When to use
- During project initiation to identify required roles
- At the start of each sprint or milestone to plan cross-functional coordination
- When experiencing handoff issues or communication gaps
- During onboarding of new team members to clarify collaboration points

---

## Project Initiation Phase

### Core Team Assembly
- [ ] **Project Manager** assigned and responsible for coordination
- [ ] **Product Manager** identified for product vision and priorities
- [ ] **Developer(s)** assigned with appropriate skills for the work
- [ ] **Stakeholder Representative(s)** identified and engaged

### Specialized Roles Assessment
- [ ] **UX Designer** — Required if user interface or experience changes are involved
- [ ] **QA Engineer** — Required for feature delivery; engaged early for test planning
- [ ] **DevOps Engineer** — Required for infrastructure, deployment, or scaling needs
- [ ] **Security Lead** — Required for features handling sensitive data or external integrations
- [ ] **Data Analyst** — Required if metrics, tracking, or data-driven decisions are needed

### Initial Alignment
- [ ] All required roles have reviewed the Project One-pager
- [ ] Each role understands their responsibilities and deliverables
- [ ] Communication channels and meeting cadences established
- [ ] Dependencies between roles identified and documented

---

## Planning Phase

### Design & Requirements
- [ ] **UX Designer** provides wireframes/prototypes for review (if applicable)
- [ ] **Product Manager** and **UX Designer** align on user workflows
- [ ] **Security Lead** reviews design for security requirements (if applicable)
- [ ] **Data Analyst** defines metrics and instrumentation needs (if applicable)

### Technical Planning
- [ ] **Developers** review designs for feasibility and estimate effort
- [ ] **DevOps Engineer** assesses infrastructure and deployment requirements
- [ ] **Security Lead** provides security acceptance criteria (if applicable)
- [ ] **QA Engineer** begins test plan development based on acceptance criteria

### Documentation & Readiness
- [ ] All roles have contributed to and reviewed acceptance criteria
- [ ] Dependencies and handoff points between roles are documented
- [ ] Risk register includes concerns from all specialized roles
- [ ] Definition of Done includes quality, security, and deployment gates

---

## Execution Phase

### Development Collaboration
- [ ] **Developers** consult **UX Designer** during implementation for clarifications
- [ ] **Developers** implement instrumentation as defined by **Data Analyst**
- [ ] **Security Lead** conducts security review of code changes (if applicable)
- [ ] **DevOps Engineer** supports local development environment setup

### Quality & Testing
- [ ] **QA Engineer** reviews completed features against acceptance criteria
- [ ] **Developers** work with **QA Engineer** to reproduce and fix defects
- [ ] **DevOps Engineer** ensures test environments match production configuration
- [ ] **UX Designer** validates implementation matches design intent

### Pre-Release Validation
- [ ] **QA Engineer** signs off on test completion and quality gates
- [ ] **Security Lead** approves security scan results and remediation (if applicable)
- [ ] **DevOps Engineer** confirms deployment readiness and rollback plan
- [ ] **Product Manager** validates feature meets requirements

---

## Release Phase

### Deployment Coordination
- [ ] **DevOps Engineer** executes deployment following runbook
- [ ] **Developers** available for troubleshooting during deployment window
- [ ] **QA Engineer** conducts smoke tests in production environment
- [ ] **Project Manager** communicates release status to stakeholders

### Post-Release Monitoring
- [ ] **DevOps Engineer** monitors system health and error rates
- [ ] **Data Analyst** validates metrics and tracking are working correctly
- [ ] **QA Engineer** monitors for production defects or user-reported issues
- [ ] **Product Manager** reviews early adoption and feedback signals

---

## Retrospective & Continuous Improvement

### Cross-Functional Review
- [ ] All involved roles participate in retrospective
- [ ] Handoff pain points between roles are identified
- [ ] Communication effectiveness across roles is assessed
- [ ] Action items assigned with owners from appropriate roles

### Process Improvement
- [ ] Lessons learned documented for future projects
- [ ] Process improvements identified for cross-functional collaboration
- [ ] Updated role responsibilities or interaction patterns captured
- [ ] Knowledge shared with broader organization

---

## Role-Specific Onboarding Checklist

### When a New Team Member Joins
- [ ] New member reviews [Roles and Personas](octoacme-roles-and-personas.md) documentation
- [ ] Introductions scheduled with key collaborators from other roles
- [ ] Role-specific responsibilities and deliverables clarified
- [ ] Communication channels and meeting invites confirmed
- [ ] Access to necessary tools, systems, and documentation verified
- [ ] First collaboration task assigned with a peer for shadowing/mentorship
- [ ] Understanding of interaction patterns with other roles validated

---

## Common Cross-Functional Collaboration Patterns

### UX Designer ↔ Developer
- Early design review for feasibility feedback
- Iterative check-ins during implementation
- Final review before feature completion

### Developer ↔ QA Engineer
- Acceptance criteria refinement during planning
- Feature demo before formal QA testing
- Collaborative defect triage and resolution

### DevOps Engineer ↔ Developer
- Infrastructure requirements during planning
- Deployment runbook review before release
- Post-incident collaboration on root cause

### Security Lead ↔ Developer
- Threat modeling during design phase
- Security code review before PR merge
- Vulnerability remediation pairing when needed

### Data Analyst ↔ Product Manager
- Metric definition during planning
- Regular data review sessions post-release
- Experimentation design and analysis

### Stakeholder Representative ↔ Project Manager
- Weekly status updates and milestone reviews
- Requirements clarification as needed
- Escalation coordination for issues

---

## Tips for Effective Cross-Functional Collaboration

- **Involve roles early**: Bring specialized roles into planning, not just execution
- **Define clear handoffs**: Document what each role needs from others and when
- **Over-communicate**: Assume good intent and proactively share updates
- **Use asynchronous documentation**: Not everyone can attend every meeting
- **Respect expertise**: Trust each role to know their domain best
- **Close the loop**: Always confirm understanding of requirements and feedback
- **Celebrate together**: Recognize cross-functional wins and contributions

---

*Use this checklist in conjunction with other OctoAcme project management guides to ensure smooth collaboration across all project roles.*
