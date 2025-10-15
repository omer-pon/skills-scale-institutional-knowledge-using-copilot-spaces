# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Define how different roles collaborate effectively across functional boundaries to deliver successful projects with clear accountability and efficient communication.

## When to Use
Reference this guide when coordinating work across multiple roles, planning cross-functional initiatives, or clarifying collaboration patterns.

---

## Core Collaboration Principles

1. **Shared Ownership**: Everyone is responsible for project success, not just their individual contributions
2. **Early Involvement**: Include relevant roles early in planning to identify dependencies and risks
3. **Clear Handoffs**: Define clear handoff points and deliverables between roles
4. **Transparent Communication**: Use shared channels and documentation for visibility
5. **Mutual Respect**: Value each role's expertise and perspective

---

## Common Collaboration Patterns

### Feature Development Flow

**Typical Sequence:**
1. **Product Manager** defines feature requirements and success metrics.
2. **UX Designer** creates user flows and design specifications.
3. **Security Lead** reviews for security implications.
4. **Developers** implement feature with design and security guidance.
5. **DevOps Engineer** ensures CI/CD pipeline supports deployment.
6. **Project Manager** coordinates timeline, dependencies, and status updates.
7. **Customer Success Manager** validates with customer needs and prepares for rollout.

**Key Touchpoints:**
- Kickoff meeting with all roles present
- Design review (PM, UX, Developers, Security)
- Security review (Security Lead, Developers, DevOps)
- Implementation review (Developers, PM, UX)
- Pre-release planning (PM, DevOps, Customer Success)

### Incident Response Flow

**Typical Sequence:**
1. **DevOps Engineer** or Developer detects and triages incident.
2. **Project Manager** coordinates communication and status updates.
3. **Developers** and **DevOps Engineers** implement fixes.
4. **Security Lead** involved if security-related.
5. **Customer Success Manager** communicates with affected customers.
6. **Scrum Master** facilitates blameless postmortem.

**Key Touchpoints:**
- Incident declaration and triage call
- Hourly status updates during active incident
- Customer communication (coordinated through Customer Success)
- Post-incident retrospective (all involved roles)
- Action items tracked by Project Manager

### Sprint Planning Flow

**Typical Sequence:**
1. **Product Manager** prioritizes backlog items.
2. **UX Designer** provides design readiness status.
3. **Security Lead** flags any security work needed.
4. **Developers** estimate effort and identify technical dependencies.
5. **DevOps Engineer** confirms infrastructure and deployment capacity.
6. **Scrum Master** facilitates planning meeting.
7. **Project Manager** confirms resource availability and dependencies.

**Key Touchpoints:**
- Backlog refinement (PM, UX, Developers, Security)
- Sprint planning meeting (all delivery team roles)
- Dependency mapping (PM coordinates with other teams)
- Capacity planning (Scrum Master, PM)

---

## Role Interaction Matrix

### Who Works Most Closely With Whom

| Role | Primary Collaborators | Secondary Collaborators |
|------|----------------------|-------------------------|
| **Developer** | Scrum Master, DevOps, UX Designer | Product Manager, Security Lead, Project Manager |
| **Product Manager** | UX Designer, Project Manager, Developers | Customer Success, Security Lead, Scrum Master |
| **Project Manager** | Product Manager, Scrum Master, All roles | Stakeholders, External teams |
| **Scrum Master** | Developers, Project Manager | Product Manager, DevOps |
| **UX Designer** | Product Manager, Developers | Customer Success, Project Manager |
| **DevOps Engineer** | Developers, Security Lead | Project Manager, Scrum Master |
| **Customer Success Manager** | Product Manager, UX Designer | Project Manager, Developers |
| **Security Lead** | DevOps Engineer, Developers | Product Manager, Project Manager |

---

## Collaboration Best Practices

### Meetings and Synchronization

**Daily Standups (15 min)**
- Attendees: Developers, Scrum Master, optionally PM and DevOps
- Focus: Progress, blockers, quick coordination
- Not for: Deep technical discussions or planning

**Weekly Cross-Functional Sync (30-45 min)**
- Attendees: PM, Product Manager, Scrum Master, Tech Lead, DevOps
- Focus: Progress toward milestones, dependencies, risks, decisions
- Deliverable: Updated risk register and status report

**Sprint Planning (1-2 hours)**
- Attendees: Full delivery team (Developers, Scrum Master, PM, Product Manager, UX, DevOps)
- Focus: Commit to sprint work, clarify acceptance criteria, identify dependencies
- Deliverable: Sprint backlog with estimates

**Sprint Review/Demo (1 hour)**
- Attendees: Delivery team + stakeholders + Customer Success
- Focus: Demonstrate completed work, gather feedback
- Deliverable: Feedback for backlog refinement

**Retrospective (45-60 min)**
- Attendees: Delivery team (Developers, Scrum Master, PM, DevOps, UX)
- Focus: Process improvements, team health
- Deliverable: Action items with owners

### Documentation Handoffs

**Product to Design**
- **From Product Manager**: Feature requirements, user stories, success metrics
- **To UX Designer**: Design brief with context, goals, and constraints
- **Expected Turnaround**: Defined in planning, typically 1-2 sprints
- **Validation**: Design review with PM, Developers, and stakeholders

**Design to Development**
- **From UX Designer**: Design specifications, prototypes, assets, style guide references
- **To Developers**: Design handoff with measurements, interactions, and edge cases
- **Expected Turnaround**: Implementation in committed sprint
- **Validation**: Design review of implementation, iterative refinement

**Development to DevOps**
- **From Developers**: Deployment requirements, configuration needs, dependencies
- **To DevOps Engineer**: Deployment plan, infrastructure changes needed
- **Expected Turnaround**: Infrastructure ready before deployment window
- **Validation**: Successful staging deployment and smoke tests

**Any Role to Customer Success**
- **From Product/Engineering**: Feature launch details, known issues, customer-facing documentation
- **To Customer Success Manager**: Release notes, FAQ, training materials, rollout plan
- **Expected Turnaround**: 1 week before customer-facing launch
- **Validation**: Customer Success readiness confirmation

---

## Escalation and Decision-Making

### When to Escalate Cross-Functionally

- **Technical blocker** affecting multiple teams → Developer/DevOps → PM → Product Lead
- **Design disagreement** on approach → UX Designer + Developers → Product Manager
- **Scope or priority conflict** → PM + Product Manager → Product Lead + Sponsors
- **Security risk** identified → Security Lead → PM → Product Lead + Security leadership
- **Customer escalation** requiring engineering → Customer Success → PM → Developers/DevOps
- **Resource constraint** affecting delivery → PM → Product Lead + Resource managers

### Cross-Functional Decision Framework

**Type 1 Decisions (Reversible, Low Impact)**
- Made by: Individual role owner
- Examples: Implementation details, tool choices, minor UX adjustments
- Communication: Document in PR, design notes, or project board
- Timeline: Immediate

**Type 2 Decisions (Reversible, High Impact)**
- Made by: Role owner with consultation
- Examples: Architecture patterns, major design changes, sprint priorities
- Communication: Discuss in team meeting, document in decision log
- Timeline: Within 1-2 days

**Type 3 Decisions (Difficult to Reverse, High Impact)**
- Made by: PM + Product Manager + relevant stakeholders
- Examples: Technology choices, major scope changes, release timelines
- Communication: Written decision document with rationale, stakeholder alignment meeting
- Timeline: Within 1 week, with urgent escalation path if needed

---

## Communication Channels

### Synchronous
- **Urgent blockers**: Direct message or call to role owner, escalate to PM if unresponsive
- **Quick questions**: Team chat channel
- **Coordination**: Daily standup or ad-hoc sync call
- **Complex discussions**: Scheduled meeting with relevant roles

### Asynchronous
- **Status updates**: Weekly status template in project board or docs
- **Decisions**: Document in decision log or project charter
- **Handoffs**: Use templates (design specs, deployment plans, release notes)
- **Feedback**: PR comments, design review comments, recorded demos

---

## Cross-Functional Templates

### Cross-Functional Kickoff Template

**Project Name:**
**Objective:**
**Success Metrics:**

**Role Assignments:**
- Product Manager:
- Project Manager:
- Tech Lead:
- UX Designer:
- DevOps Engineer:
- Security Lead:
- Customer Success Manager:
- Scrum Master:

**Key Milestones:**
1. [Date] - [Milestone]
2. [Date] - [Milestone]

**Dependencies:**
- Internal:
- External:

**Risks:**
- [Risk] - Owner: [Role] - Mitigation: [Plan]

**Communication Plan:**
- Standups: [Frequency]
- Status updates: [Frequency and format]
- Stakeholder briefings: [Frequency]

### Collaboration Checkpoint Template

Use this weekly to ensure cross-functional alignment:

**Week of:** [Date]

**Accomplishments:**
- [Role]: [Key accomplishment]

**Next Week Plans:**
- [Role]: [Key focus]

**Cross-Functional Blockers:**
- [Blocker] - Needs: [Role] - By: [Date]

**Decisions Needed:**
- [Decision] - Owners: [Roles involved] - By: [Date]

**Risks/Dependencies:**
- [Risk/Dependency] - Status: [Update]

---

## Measuring Collaboration Effectiveness

Track these indicators during retrospectives:

- **Handoff Smoothness**: How clear and complete were handoffs between roles?
- **Communication Quality**: Was information shared proactively and clearly?
- **Blocker Resolution Time**: How quickly were cross-functional blockers resolved?
- **Decision Velocity**: How efficiently were cross-functional decisions made?
- **Role Clarity**: Were responsibilities and expectations clear?

Use feedback to continuously improve collaboration patterns.
