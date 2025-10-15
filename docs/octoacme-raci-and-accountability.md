# OctoAcme — RACI Matrix and Accountability Framework

## Purpose
Define clear accountability and decision rights across roles using RACI (Responsible, Accountable, Consulted, Informed) matrices to eliminate ambiguity and improve project execution.

## When to Use
- At project kickoff to clarify roles and responsibilities
- When confusion exists about who owns a decision or deliverable
- During retrospectives when accountability issues are identified
- When onboarding new team members to a project

---

## RACI Definitions

- **R (Responsible)**: The person(s) who does the work to complete the task. Multiple people can be Responsible.
- **A (Accountable)**: The person ultimately answerable for correct completion. Only ONE person should be Accountable per task.
- **C (Consulted)**: People whose opinions are sought, typically subject matter experts. Two-way communication.
- **I (Informed)**: People who are kept up-to-date on progress. One-way communication.

### Guidelines
- Every task must have exactly ONE Accountable role
- Multiple roles can be Responsible
- Minimize the number of Consulted roles (avoid analysis paralysis)
- Limit Informed roles to those who truly need to know

---

## Project Lifecycle RACI Matrix

| Activity | Product Manager | Project Manager | Developer | Scrum Master | UX Designer | DevOps Engineer | Security Lead | Customer Success |
|----------|----------------|-----------------|-----------|--------------|-------------|-----------------|---------------|------------------|
| **Initiation Phase** |
| Define problem statement | A | C | I | I | C | I | I | C |
| Create project one-pager | R | A | I | I | I | I | I | C |
| Stakeholder alignment | C | A | I | I | I | I | I | C |
| Initial risk identification | C | A | C | I | I | C | C | I |
| Resource allocation | C | A | I | R | I | I | I | I |
| **Planning Phase** |
| Define product requirements | A | C | C | I | R | I | C | C |
| Create design specifications | C | I | C | I | A | I | I | C |
| Technical architecture | C | C | A | I | C | R | C | I |
| Sprint/iteration planning | C | C | R | A | C | C | I | I |
| Risk and dependency mapping | C | A | C | C | C | C | C | I |
| Define acceptance criteria | A | C | C | I | C | I | C | C |
| **Execution Phase** |
| Feature implementation | C | I | A | C | I | C | I | I |
| Code reviews | I | I | A/R | I | I | I | C | I |
| Design implementation | C | I | R | I | A | I | I | I |
| Security reviews | I | I | C | I | I | C | A | I |
| Infrastructure changes | I | C | C | I | I | A | C | I |
| Daily standups | I | I | R | A | R | R | I | I |
| Sprint demos | C | C | R | A | R | I | I | C |
| Status reporting | C | A | C | C | C | C | I | I |
| Blocker resolution | C | A | R | R | C | C | C | I |
| **Testing & Quality** |
| Unit/integration testing | C | I | A | I | I | C | I | I |
| Usability testing | C | I | I | C | A | I | I | C |
| Security testing | C | I | C | I | I | C | A | I |
| Performance testing | C | I | R | I | I | A | I | I |
| **Release Phase** |
| Release planning | C | A | C | C | I | R | C | C |
| Deployment execution | I | C | C | I | I | A | C | I |
| Release communication | C | C | I | I | I | I | I | A |
| Customer onboarding | A | I | I | I | C | I | I | R |
| **Retrospective & Improvement** |
| Retrospective facilitation | C | C | R | A | R | R | R | C |
| Action item tracking | C | A | C | C | C | C | C | I |
| Process improvements | C | A | C | R | C | C | C | I |

---

## Activity-Specific RACI Templates

### User Story Development

| Activity | Product Manager | UX Designer | Developer | Security Lead | Customer Success |
|----------|----------------|-------------|-----------|---------------|------------------|
| Story definition | A | C | C | I | C |
| Acceptance criteria | A | C | C | C | C |
| Design mockups | C | A | C | I | I |
| Technical design | C | C | A | C | I |
| Security review | I | I | C | A | I |
| Implementation | C | I | A | I | I |
| Design QA | C | A | C | I | I |
| Story acceptance | A | C | C | I | I |

### Incident Response

| Activity | Developer | DevOps Engineer | Project Manager | Security Lead | Customer Success |
|----------|-----------|-----------------|-----------------|---------------|------------------|
| Incident detection | R | R | I | I | I |
| Triage | R | A | C | C | I |
| Fix implementation | A | R | I | C | I |
| Communication (internal) | I | C | A | I | C |
| Communication (customer) | I | C | C | C | A |
| Postmortem | R | R | C | C | I |
| Action items | R | R | A | C | I |

### Security Review

| Activity | Developer | DevOps Engineer | Project Manager | Security Lead | Product Manager |
|----------|-----------|-----------------|-----------------|---------------|-----------------|
| Request security review | A | I | C | I | C |
| Threat modeling | C | C | I | A | C |
| Code security scan | R | C | I | A | I |
| Infrastructure review | C | R | I | A | I |
| Findings remediation | A | C | C | C | C |
| Sign-off | C | I | I | A | C |

### Release Management

| Activity | Developer | DevOps Engineer | Project Manager | Product Manager | Customer Success |
|----------|-----------|-----------------|-----------------|-----------------|------------------|
| Release planning | C | C | A | C | C |
| Release notes | R | C | C | A | C |
| Deployment prep | R | A | C | I | I |
| Deployment execution | C | A | C | I | I |
| Post-deploy verification | R | A | C | I | I |
| Customer communication | I | I | C | C | A |
| Success metrics tracking | C | I | I | A | C |

---

## Creating Your Own RACI Matrix

### Steps to Build a RACI

1. **List Activities**: Break down the project or process into key activities/deliverables
2. **Identify Roles**: List all roles involved in these activities
3. **Assign RACI**: For each activity, assign RACI designations to roles
4. **Validate**: 
   - Each activity has exactly ONE Accountable
   - No role is overloaded with As (accountability)
   - No activity has too many Cs (decision paralysis)
5. **Review with Team**: Get team agreement on the assignments
6. **Document and Share**: Make the RACI visible and accessible
7. **Update as Needed**: Revise when roles or scope changes

### RACI Matrix Template

| Activity / Deliverable | Role 1 | Role 2 | Role 3 | Role 4 | Role 5 |
|------------------------|--------|--------|--------|--------|--------|
| [Activity 1] | | | | | |
| [Activity 2] | | | | | |
| [Activity 3] | | | | | |

---

## Accountability Best Practices

### Clear Accountability Means:

1. **Single Point of Accountability**: One person owns the outcome (Accountable role)
2. **Defined Scope**: Clear boundaries of what each role is responsible for
3. **Authority to Act**: Accountable person has authority to make decisions within scope
4. **Visibility**: Status and progress are transparent
5. **Consequences**: Success and failures are acknowledged

### When Accountability is Unclear:

**Symptoms:**
- "I thought someone else was doing that"
- Missed deadlines with no clear owner
- Duplicated effort across team members
- Decisions stalled waiting for approval
- Finger-pointing when things go wrong

**Solutions:**
- Create or review RACI matrix for the area
- Explicitly assign accountability in project tracking
- Clarify decision rights in team meetings
- Document ownership in issue descriptions
- Escalate to Project Manager for clarification

### Accountability vs. Blame

**Accountability culture:**
- Focus on outcomes and learning
- Psychological safety to raise issues
- Blameless postmortems
- Shared ownership of team success
- Celebrate wins and learn from failures

**Blame culture (avoid):**
- Focus on finding fault
- Hiding problems until they escalate
- Postmortems that point fingers
- Individuals protect themselves over team
- Failures are punished, not learned from

---

## Decision Rights Framework

Different decisions require different levels of accountability. Use this framework alongside RACI.

### Level 1: Individual Decisions
- **Who**: Individual contributor (Developer, Designer, etc.)
- **Scope**: Day-to-day technical or design choices
- **Examples**: Variable naming, button placement, test approach
- **Process**: Make decision, document in work item
- **Timeline**: Immediate

### Level 2: Team Decisions
- **Who**: Delivery team (facilitated by Scrum Master)
- **Scope**: Process, quality standards, sprint commitments
- **Examples**: Definition of Done, ceremony format, sprint capacity
- **Process**: Discuss in team meeting, document in team wiki
- **Timeline**: Within current sprint

### Level 3: Project Decisions
- **Who**: Project Manager + Product Manager
- **Scope**: Scope, timeline, resource trade-offs
- **Examples**: Feature prioritization, release dates, resource allocation
- **Process**: PM/PdM alignment, document in project charter
- **Timeline**: Within 1 week

### Level 4: Strategic Decisions
- **Who**: Product Lead + Sponsors
- **Scope**: Product strategy, major investments, go/no-go
- **Examples**: New product lines, major technology shifts, budget approval
- **Process**: Business case, stakeholder review, decision memo
- **Timeline**: As required, typically weeks

---

## Accountability in Meetings

Ensure every meeting has clear accountability:

**Meeting Owner (Accountable)**
- Schedules and runs the meeting
- Ensures agenda is prepared and shared
- Facilitates discussion and decision-making
- Documents decisions and action items
- Follows up on action items from previous meeting

**Action Items Format**
Every action item should have:
- **Description**: What needs to be done
- **Accountable**: Who will ensure it's done (ONE person)
- **Responsible**: Who will do the work (can be same as Accountable)
- **Due Date**: When it will be complete
- **Status**: Current state (Not Started, In Progress, Blocked, Complete)

**Example:**
- **Description**: Update API documentation with new endpoints
- **Accountable**: Developer (Jane)
- **Due Date**: End of sprint (Friday)
- **Status**: In Progress

---

## Quarterly RACI Review

Conduct a quarterly review of RACI matrices:

1. **Review Effectiveness**
   - Were accountabilities clear?
   - Were there conflicts or gaps?
   - Did the RACI reflect actual practice?

2. **Update for Changes**
   - New roles added to team
   - Organizational changes
   - Process improvements from retrospectives

3. **Simplify**
   - Remove outdated activities
   - Combine similar responsibilities
   - Reduce unnecessary consultation requirements

4. **Communicate**
   - Share updated RACI with team
   - Review in onboarding
   - Reference in project documentation

---

## Common RACI Pitfalls and Solutions

### Pitfall: Too Many Accountable
- **Problem**: Multiple As for one activity leads to diffused responsibility
- **Solution**: Designate ONE Accountable, others are Responsible or Consulted

### Pitfall: No Accountable
- **Problem**: Activity has Rs but no A, unclear who owns outcome
- **Solution**: Assign an Accountable role, escalate to PM if unclear

### Pitfall: Consultation Overload
- **Problem**: Too many Cs slow down progress
- **Solution**: Limit to 2-3 Cs per activity, move others to Informed

### Pitfall: RACI Never Updated
- **Problem**: Matrix becomes stale and doesn't reflect reality
- **Solution**: Review quarterly and after major changes

### Pitfall: RACI Without Authority
- **Problem**: Accountable role doesn't have authority to make decisions
- **Solution**: Align authority with accountability, escalate if needed

---

## Using RACI with Project Boards

Integrate RACI into issue/task tracking:

**Issue Template Fields:**
- Accountable: [Role/Person]
- Responsible: [Role(s)/People]
- Consulted: [Role(s)/People]
- Informed: [Role(s)/People]

**Project Board Labels:**
- `accountability:dev` - Developer accountable
- `accountability:pm` - Project Manager accountable
- `accountability:product` - Product Manager accountable
- `accountability:ux` - UX Designer accountable
- `accountability:devops` - DevOps Engineer accountable
- `accountability:security` - Security Lead accountable

This makes it easy to filter tasks by accountability and ensure balanced distribution.
