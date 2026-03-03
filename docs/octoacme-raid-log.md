# OctoAcme — RAID Log

## Purpose
Provide a single, actionable template for tracking Risks, Assumptions, Issues, and Dependencies (RAID) throughout the project lifecycle.

## What is RAID?

- **Risks**: Potential problems that may impact the project (not yet happened)
- **Assumptions**: Things we believe to be true but haven't validated
- **Issues**: Active problems currently blocking or impacting delivery
- **Dependencies**: External factors or work that must be completed for success

## When to Use
- Create a RAID log during project initiation or kickoff
- Review and update weekly during team syncs and standups
- Escalate high-priority items according to the escalation path
- Reference in status reports and stakeholder communications

## RAID Log Template

Copy and paste this table into your project documentation:

```markdown
## Risks

| ID | Description | Impact | Likelihood | Owner | Mitigation Plan | Status | Last Updated |
|----|-------------|--------|------------|-------|-----------------|--------|--------------|
| R-001 | Example: Third-party API rate limits may affect performance | High | Medium | Tech Lead | Implement caching and retry logic | Active | 2024-03-15 |
| R-002 | | | | | | | |

**Impact/Likelihood Scale:** High, Medium, Low

## Assumptions

| ID | Description | Validation Needed | Owner | Status | Last Updated |
|----|-------------|-------------------|-------|--------|--------------|
| A-001 | Example: Users have reliable internet connectivity | Test with low-bandwidth scenarios | QA Lead | Validated | 2024-03-10 |
| A-002 | | | | | |

**Status:** Not Validated, In Progress, Validated, Invalidated

## Issues

| ID | Description | Impact | Owner | Action Plan | Target Resolution | Status | Last Updated |
|----|-------------|--------|-------|-------------|-------------------|--------|--------------|
| I-001 | Example: Database migration script failing in staging | High | DevOps | Reviewing logs, will patch schema | 2024-03-16 | In Progress | 2024-03-15 |
| I-002 | | | | | | | |

**Impact:** Critical, High, Medium, Low  
**Status:** New, In Progress, Resolved, Blocked

## Dependencies

| ID | Description | Type | Dependent Team/System | Owner | Expected Date | Status | Last Updated |
|----|-------------|------|----------------------|-------|---------------|--------|--------------|
| D-001 | Example: Authentication service upgrade from Platform team | External | Platform Team | PM | 2024-03-20 | On Track | 2024-03-15 |
| D-002 | | | | | | | |

**Type:** Internal, External, Technical, Business  
**Status:** Not Started, In Progress, Complete, Blocked, At Risk
```

## Usage Guidance

### For Risks
1. **Identify early**: Capture risks during planning and throughout execution
2. **Assess impact and likelihood**: Use consistent scales (High/Medium/Low)
3. **Assign ownership**: Each risk needs a clear owner to monitor and mitigate
4. **Create mitigation plans**: Define specific actions to reduce probability or impact
5. **Monitor regularly**: Review in weekly syncs and update status

### For Assumptions
1. **Make implicit assumptions explicit**: Document what you're assuming to be true
2. **Prioritize validation**: Test critical assumptions as early as possible
3. **Track validation status**: Update when assumptions are confirmed or invalidated
4. **Adjust plans**: If assumptions are invalidated, update project scope or approach

### For Issues
1. **Log immediately**: Don't wait for weekly syncs to capture blocking issues
2. **Triage impact**: Assess severity to prioritize resolution efforts
3. **Assign clear ownership**: Ensure someone is accountable for resolution
4. **Set target dates**: Create urgency and enable tracking
5. **Update frequently**: Keep status current for visibility

### For Dependencies
1. **Identify cross-team dependencies**: Map out what your project relies on
2. **Engage early**: Contact dependent teams as soon as dependencies are known
3. **Track progress**: Regular check-ins with dependency owners
4. **Flag at-risk dependencies**: Escalate when dependencies may miss target dates
5. **Plan contingencies**: Have backup plans for critical dependencies

## Escalation Process

### Level 1: Team-Level Triage
- **When**: Any new item added to RAID log
- **Who**: Team discusses in daily standup or weekly sync
- **Outcome**: Assign owner, create action plan, set status

### Level 2: PM/Product Lead Escalation
- **When**: High-impact risks, blocked issues, at-risk dependencies
- **Who**: PM escalates to Product Lead and relevant stakeholders
- **Outcome**: Additional resources, priority changes, or scope adjustments

### Level 3: Sponsor/Executive Escalation
- **When**: Business-critical items that can't be resolved at Level 2
- **Who**: Product Lead escalates to sponsor or executive team
- **Outcome**: Executive decisions, budget changes, or strategic pivots

## Status Reporting

### Weekly Update Format
Include RAID summary in weekly status reports:

```markdown
### RAID Summary (as of [date])
- **Risks**: [X active, Y mitigated] - Top risk: [brief description]
- **Assumptions**: [X validated, Y pending] - Key assumption to validate: [description]
- **Issues**: [X open, Y resolved this week] - Critical issue: [description]
- **Dependencies**: [X on track, Y at risk] - At-risk dependency: [description]
```

### Monthly Stakeholder Updates
Provide high-level RAID overview:
- Count of active vs. resolved items by category
- Top 3 risks and mitigation status
- Any critical dependencies or blocking issues
- Trend analysis (improving, stable, or degrading)

## Integration with Other Processes

### Project Kickoff
- Create initial RAID log with known risks and dependencies
- Document key assumptions that need validation
- Reference RAID log in kickoff artifacts

### Sprint Planning
- Review RAID log before planning to ensure awareness
- Consider risks when estimating and committing to work
- Plan work to validate critical assumptions

### Daily Standups
- Report any new issues or blockers to RAID log
- Update status of active items
- Flag items needing escalation

### Retrospectives
- Review how well RAID items were managed
- Identify patterns (e.g., recurring risks)
- Create action items to improve RAID process

## Best Practices
- **Keep it current**: Update at least weekly, more frequently for active issues
- **Be specific**: Vague descriptions don't help; include concrete details
- **Assign ownership**: Every item needs a named owner
- **Review trends**: Look for patterns in risks and issues over time
- **Celebrate closures**: Acknowledge when risks are mitigated or issues resolved
- **Don't let it grow unbounded**: Archive or close resolved items regularly

## RAID Log Checklist
- [ ] RAID log created and accessible to all team members
- [ ] Initial risks and dependencies identified during planning
- [ ] Owners assigned to all active items
- [ ] Review cadence established (weekly minimum)
- [ ] Escalation criteria defined and communicated
- [ ] Integration with status reporting confirmed

## Related Docs
- [Project Initiation](./octoacme-project-initiation.md) - Create initial RAID log
- [Project Planning](./octoacme-project-planning.md) - Reference RAID in planning
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Update RAID during execution
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk-specific guidance
- [Project Kickoff](./octoacme-project-kickoff.md) - RAID log as kickoff output
