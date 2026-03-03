# OctoAcme — Definition of Ready & Definition of Done

## Purpose
Establish clear, consistent standards for when work is ready to start (DoR) and when it's truly complete (DoD).

## Definition of Ready (DoR)

### Purpose
Ensure backlog items are well-defined and actionable before the team commits to them in sprint planning.

### Minimum DoR Checklist

A backlog item is "Ready" when:

- [ ] **Clear title and description**: The what and why are understandable
- [ ] **Acceptance criteria defined**: Specific, testable conditions for success
- [ ] **Dependencies identified**: Any blockers or prerequisites are known
- [ ] **Estimated**: Team has provided a size estimate (story points or T-shirt size)
- [ ] **Prioritized**: Product Manager has assigned a priority level
- [ ] **Fits in sprint**: Work can be completed within one sprint/iteration

### Optional DoR Items

For more mature teams or complex work:

- [ ] **Design/mockups available**: For UI work, visual designs are ready
- [ ] **Technical approach outlined**: High-level implementation plan exists
- [ ] **Test approach defined**: QA strategy is clear
- [ ] **Performance criteria specified**: For performance-sensitive features
- [ ] **Security review completed**: For features handling sensitive data
- [ ] **API contracts defined**: For integration work

### DoR Quick Reference Table

| Category | Minimum | Optional |
|----------|---------|----------|
| **Description** | Title, description, acceptance criteria | User stories, detailed scenarios |
| **Dependencies** | Known blockers identified | Dependency owners contacted |
| **Estimation** | Story points or T-shirt size | Confidence level noted |
| **Design** | N/A | Mockups, wireframes available |
| **Technical** | N/A | Architecture notes, API specs |
| **Testing** | N/A | Test cases outlined |

### When to Check DoR
- During backlog refinement sessions
- Before sprint planning begins
- When pulling items into "Ready" column on project board

### What to Do if DoR Not Met
- Move item back to backlog
- Schedule refinement session to address gaps
- Assign owner to gather missing information
- Don't commit to incomplete work in sprint planning

## Definition of Done (DoD)

### Purpose
Ensure consistent quality and completeness for all work items before they're considered complete.

### Minimum DoD Checklist

Work is "Done" when:

- [ ] **Code complete**: All code written and committed
- [ ] **Acceptance criteria met**: All criteria from the story are satisfied
- [ ] **Code reviewed**: At least one peer approval on PR
- [ ] **Tests passing**: All automated tests (unit, integration) pass in CI
- [ ] **Documentation updated**: README, API docs, or inline comments as needed
- [ ] **No known defects**: No open bugs related to this work
- [ ] **Merged to main branch**: Code is integrated (not just in feature branch)
- [ ] **Deployed to staging/test environment**: Available for validation

### Optional DoD Items

Depending on team maturity and project needs:

- [ ] **Manual QA completed**: Tested by QA team member
- [ ] **Performance tested**: Meets performance benchmarks
- [ ] **Security scanned**: No new vulnerabilities introduced
- [ ] **Accessibility tested**: Meets WCAG standards (for UI work)
- [ ] **Cross-browser tested**: Works in supported browsers (for web work)
- [ ] **Monitoring/alerts configured**: Observability in place for new features
- [ ] **Feature flags configured**: Toggle mechanism for controlled rollout
- [ ] **Release notes drafted**: User-facing changes documented
- [ ] **Training materials updated**: Internal docs for support/sales updated
- [ ] **Deployed to production**: Live and available to users

### DoD by Work Type

Different types of work may have specific DoD requirements:

#### For Features/User Stories
```markdown
- [ ] Acceptance criteria validated by Product Manager
- [ ] User-facing documentation updated
- [ ] Analytics/tracking implemented (if applicable)
- [ ] Feature announced to stakeholders
```

#### For Bug Fixes
```markdown
- [ ] Root cause identified and documented
- [ ] Fix verified in the reported environment
- [ ] Regression test added to prevent recurrence
- [ ] Issue reporter notified of resolution
```

#### For Technical Debt/Refactoring
```markdown
- [ ] No functional changes or regression
- [ ] Performance impact measured (should be neutral or improved)
- [ ] Technical documentation updated
- [ ] Team briefed on changes
```

#### For Documentation
```markdown
- [ ] Peer reviewed for accuracy
- [ ] Examples tested and verified
- [ ] Links validated (no broken links)
- [ ] Added to documentation index/table of contents
```

### DoD Quick Reference Table

| Area | Minimum | Optional/Advanced |
|------|---------|-------------------|
| **Code** | Written, committed, reviewed | Refactored, optimized |
| **Testing** | Unit tests pass in CI | Integration, E2E, manual QA, performance |
| **Review** | 1 approval | 2 approvals, specific reviewer types |
| **Integration** | Merged to main | Deployed to staging, production |
| **Documentation** | Inline comments, README updates | API docs, runbooks, training materials |
| **Quality** | No known defects | Security scan, accessibility check |
| **Validation** | Acceptance criteria met | Product/stakeholder sign-off |

### When to Check DoD
- Before moving work to "Done" column
- During PR review
- In sprint review/demo
- Before marking an issue as closed

### What to Do if DoD Not Met
- Keep item in "In Review" or "In Progress" status
- Create checklist of remaining DoD items
- Assign owner to complete outstanding work
- Don't close or move to Done until all criteria met

## Tailoring DoR and DoD

### For Your Team
Teams should:
1. Review these standards during project kickoff
2. Agree on which optional items to include
3. Document team-specific DoR/DoD in project README
4. Revisit and adjust during retrospectives

### Example Team Customization
```markdown
## Our Team's DoD (Team Alpha)

**Standard DoD:**
- All minimum items from OctoAcme DoD
- Security scan passing (we handle PII)
- Deployed to staging AND production
- Feature flag configured for all new features

**Our Additional Items:**
- Slack notification to #releases channel
- Demo recorded for async stakeholder review
```

## Integration with Other Processes

### Sprint Planning
- Only pull items that meet DoR
- Reference DoD when estimating capacity
- Plan testing and review time to meet DoD

### Daily Standups
- Mention DoD progress: "Working on tests to meet DoD"
- Flag DoD blockers: "Waiting on design review for DoR"

### Code Reviews
- Use DoD as review checklist
- Don't approve PRs that don't meet DoD
- Add DoD checklist to PR template

### Sprint Review/Demo
- Demo should show DoD has been met
- Product Manager validates acceptance criteria
- Team confirms all DoD items complete

### Retrospectives
- Review if DoR/DoD are being followed
- Discuss if standards need adjustment
- Celebrate improved compliance

## Benefits of DoR and DoD

### Definition of Ready Benefits
- Reduces sprint disruptions and scope creep
- Improves estimation accuracy
- Ensures team has what they need to succeed
- Increases team velocity and predictability

### Definition of Done Benefits
- Ensures consistent quality across all work
- Reduces technical debt accumulation
- Makes "done" unambiguous
- Builds customer and stakeholder trust
- Enables confident releases

## Common Pitfalls to Avoid

### For DoR
- ❌ Making DoR so strict that nothing is ever ready
- ❌ Skipping DoR check because "we're in a hurry"
- ❌ Product Manager defining acceptance criteria alone (involve developers)
- ✅ Balance rigor with practicality
- ✅ Refine collaboratively as a team

### For DoD
- ❌ Calling work "done" when it's really just "code complete"
- ❌ Making DoD so extensive that nothing ever finishes
- ❌ Different DoD for different team members
- ✅ Make DoD achievable within a sprint
- ✅ Apply DoD consistently across all work

## Templates

### DoR Checklist Template (Markdown)
```markdown
## Definition of Ready Checklist

- [ ] Clear title and description
- [ ] Acceptance criteria defined
- [ ] Dependencies identified
- [ ] Estimated (story points/T-shirt size)
- [ ] Prioritized by Product Manager
- [ ] Fits within one sprint
```

### DoD Checklist Template (Markdown)
```markdown
## Definition of Done Checklist

- [ ] Code complete and committed
- [ ] Acceptance criteria met
- [ ] Code reviewed (1+ approval)
- [ ] All tests passing in CI
- [ ] Documentation updated
- [ ] No known defects
- [ ] Merged to main branch
- [ ] Deployed to staging
```

### PR Template with DoD
```markdown
## Description
[Description of changes]

## Related Issue
Closes #[issue number]

## Definition of Done
- [ ] Acceptance criteria met
- [ ] Code reviewed
- [ ] Tests passing
- [ ] Documentation updated
- [ ] No known defects
- [ ] Ready to merge

## Additional Notes
[Any other context]
```

## Related Docs
- [Project Planning](./octoacme-project-planning.md) - Use DoR during backlog refinement
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Apply DoD during development
- [Project Kickoff](./octoacme-project-kickoff.md) - Define team-specific DoR/DoD
- [Release & Deployment](./octoacme-release-and-deployment.md) - Extended DoD for releases
