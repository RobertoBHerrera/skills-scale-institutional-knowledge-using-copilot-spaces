# OctoAcme — Decision Log

## Purpose
Capture and track important decisions made during project planning and execution to maintain a clear record of rationale, trade-offs, and ownership.

## When to Create a Decision Record
Create a decision record for:
- **Architectural decisions**: technology choices, design patterns, major refactorings
- **Scope changes**: adding/removing features, changing requirements
- **Timeline adjustments**: milestone changes, release date shifts
- **Trade-offs**: decisions where alternatives were considered and rejected
- **Process changes**: significant modifications to team workflows or practices

## Required Fields

| Field | Description |
|-------|-------------|
| **Date** | When the decision was made |
| **Decision ID** | Unique identifier (e.g., DEC-001, DEC-002) |
| **Decision** | Brief statement of what was decided |
| **Context** | Background and problem being addressed |
| **Options Considered** | Alternative approaches evaluated |
| **Decision Drivers** | Key factors that influenced the decision |
| **Consequences** | Expected outcomes, benefits, and trade-offs |
| **Owner** | Person accountable for the decision |
| **Status** | Proposed, Accepted, Superseded, Deprecated |

## Where Decision Records Live
- Store decision records as markdown files in `docs/decisions/` directory
- Link to decision records from:
  - Project planning documents
  - Architecture documentation
  - Sprint retrospectives
  - Related issues and PRs

## Decision Record Template

Copy and paste this template to create a new decision record:

```markdown
# Decision Record: [Decision ID] - [Brief Title]

**Date:** YYYY-MM-DD  
**Status:** [Proposed | Accepted | Superseded | Deprecated]  
**Owner:** [Name/Role]

## Decision
[Clear statement of what was decided]

## Context
[What is the background? What problem are we solving? What are the constraints?]

## Options Considered
1. **Option A**: [Description]
   - Pros: [List benefits]
   - Cons: [List drawbacks]

2. **Option B**: [Description]
   - Pros: [List benefits]
   - Cons: [List drawbacks]

3. **Option C**: [Description]
   - Pros: [List benefits]
   - Cons: [List drawbacks]

## Decision Drivers
- [Key factor 1]
- [Key factor 2]
- [Key factor 3]

## Consequences
**Positive:**
- [Expected benefit 1]
- [Expected benefit 2]

**Negative/Trade-offs:**
- [Trade-off 1]
- [Trade-off 2]

**Risks:**
- [Risk 1 and mitigation]
- [Risk 2 and mitigation]

## Related Decisions
- [Link to related decision records]

## Notes
[Additional context, follow-up items, or references]
```

## Quick Decision Table Format

For lightweight decisions, use this simplified table format in planning docs:

| ID | Date | Decision | Context | Owner | Status |
|----|------|----------|---------|-------|--------|
| DEC-001 | 2024-03-15 | Use GraphQL API | Need flexible data fetching for mobile app | Tech Lead | Accepted |
| DEC-002 | 2024-03-18 | Delay feature X to v2 | Scope management for on-time release | PM | Accepted |
| DEC-003 | 2024-03-20 | Adopt continuous deployment | Reduce release cycle time | DevOps Lead | Proposed |

## Best Practices
- **Be concise**: Decision records should be scannable and focused
- **Update status**: Mark decisions as superseded when circumstances change
- **Link liberally**: Reference decision records in PRs, issues, and planning docs
- **Review regularly**: Revisit decisions during retrospectives to validate outcomes
- **Version control**: Keep all decision records in git for full history

## Related Docs
- [Project Planning](./octoacme-project-planning.md) - Reference decisions during planning
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Link decisions in PRs
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Review decision outcomes
