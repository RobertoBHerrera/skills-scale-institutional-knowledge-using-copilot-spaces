# OctoAcme — Project Kickoff Guide

## Purpose
Provide a structured approach for launching a project with clear alignment, shared understanding, and actionable artifacts.

## When to Use
After a project has been approved during initiation and is ready to move into planning and execution.

## Kickoff Goals
- Align all team members and stakeholders on project goals and scope
- Establish roles, responsibilities, and communication norms
- Create initial project artifacts (backlog, RAID log, timeline)
- Build team rapport and psychological safety
- Set expectations for delivery and success

## Pre-Kickoff Checklist

Complete these items **before** the kickoff meeting:

- [ ] **Project One-pager finalized**: Problem statement, goals, success metrics documented
- [ ] **Stakeholder list confirmed**: All key stakeholders identified and invited
- [ ] **Team roster complete**: All team members assigned and available
- [ ] **Meeting scheduled**: 90-120 minutes blocked on team calendars
- [ ] **Logistics confirmed**: Meeting room/video link, collaboration tools ready
- [ ] **Pre-read distributed**: Send project one-pager and agenda 24-48 hours in advance
- [ ] **Initial backlog drafted**: High-level epics or features identified (can be rough)
- [ ] **Decision log created**: Empty template ready for tracking decisions

## Kickoff Meeting Agenda

**Duration:** 90-120 minutes  
**Attendees:** Core delivery team + key stakeholders

### 1. Welcome & Introductions (10 min)
- Round-table introductions: name, role, what you're excited about
- Review agenda and meeting goals
- Establish ground rules (cameras on, questions encouraged, etc.)

### 2. Project Overview (15 min)
**Owner:** Product Manager

- Present project one-pager:
  - Problem statement and business context
  - Objectives and key results (OKRs) or success metrics
  - Target customers/users and their needs
  - High-level scope (in-scope, out-of-scope, open questions)
- Explain strategic importance and expected impact

### 3. Roles & Responsibilities (10 min)
**Owner:** Project Manager

- Introduce core team roles:
  - Project Manager: coordination, scheduling, risk management
  - Product Manager: scope, priorities, acceptance criteria
  - Tech Lead: architecture, technical decisions, code quality
  - Developers: implementation, testing, documentation
  - QA/Testing: test strategy, validation, quality assurance
  - Designer: UX/UI, user research (if applicable)
- Clarify decision-making authority
- Identify stakeholder roles (approvers, informed, consulted)

### 4. Timeline & Milestones (15 min)
**Owner:** Project Manager

- Review high-level timeline and key milestones
- Identify sprint/iteration cadence (e.g., 2-week sprints)
- Highlight critical dates and dependencies
- Discuss release strategy and deployment windows
- Set expectations for flexibility vs. fixed deadlines

### 5. Initial Backlog & Scope (20 min)
**Owner:** Product Manager + Team

- Walk through high-level features or epics
- Discuss technical approach and open questions
- Collaborative exercise: ask team to identify:
  - Missing requirements
  - Technical risks or unknowns
  - Dependencies on other teams or systems
- Quick prioritization discussion (what's must-have vs. nice-to-have)

### 6. RAID Log - Initial Capture (15 min)
**Owner:** Project Manager + Team

- Review RAID framework (Risks, Assumptions, Issues, Dependencies)
- Collaborative exercise: capture initial entries:
  - **Risks:** What could go wrong? What keeps you up at night?
  - **Assumptions:** What are we assuming to be true?
  - **Issues:** Any known blockers or concerns?
  - **Dependencies:** What do we rely on from others?
- Assign owners to top risks and dependencies

### 7. Team Norms & Communication (10 min)
**Owner:** Project Manager

- Establish working agreements:
  - Daily standup time and format
  - Sprint planning and review cadence
  - Code review expectations and SLAs
  - How to escalate blockers
- Define communication channels:
  - Primary: Slack channel or Teams chat
  - Status updates: Email, wiki, or dashboard
  - Urgent issues: On-call rotation or direct contact
- Set documentation standards:
  - Where project docs live (repo, wiki, etc.)
  - How to use project board or issue tracker

### 8. Definition of Ready & Done (10 min)
**Owner:** Tech Lead / Project Manager

- Review OctoAcme DoR and DoD standards
- Discuss any team-specific additions or modifications
- Agree on must-have vs. optional items for this project
- Document customizations in project README

### 9. Q&A and Next Steps (10 min)
**Owner:** Project Manager

- Open floor for questions
- Confirm immediate next steps:
  - Who does what by when
  - Next meeting (sprint planning, backlog refinement)
  - First demo or checkpoint date
- Assign action items with owners and due dates

### 10. Closing (5 min)
**Owner:** Project Manager

- Recap key decisions made during kickoff
- Confirm everyone knows how to access artifacts
- Express appreciation and build enthusiasm
- Optional: Icebreaker or team-building activity

## Kickoff Meeting Template

Use this template for your kickoff invitation:

```markdown
## Project Kickoff: [Project Name]

**Date/Time:** [Date] at [Time]  
**Duration:** 90-120 minutes  
**Location:** [Meeting room or video link]

**Attendees:**
- [List core team members]
- [List key stakeholders]

**Pre-Read (please review before the meeting):**
- [Link to Project One-pager]
- [Link to initial backlog or epic list]

**Agenda:**
1. Introductions & Icebreaker (10 min)
2. Project Overview (15 min)
3. Roles & Responsibilities (10 min)
4. Timeline & Milestones (15 min)
5. Initial Backlog Review (20 min)
6. RAID Log Capture (15 min)
7. Team Norms & Communication (10 min)
8. Definition of Ready & Done (10 min)
9. Q&A & Next Steps (10 min)
10. Closing (5 min)

**Objectives:**
- Align on project goals and scope
- Establish team roles and communication norms
- Identify initial risks and dependencies
- Commit to next steps

**Please bring:**
- Questions or concerns about the project
- Ideas for risks or dependencies we should track
- Your calendar to schedule recurring meetings
```

## Expected Outputs / Artifacts

By the end of the kickoff, the team should have:

### Required Artifacts
- [ ] **Project Charter/One-pager**: Finalized and shared with team
- [ ] **Initial Backlog**: High-level epics or features in project board
- [ ] **RAID Log**: Initial risks, assumptions, issues, dependencies captured
- [ ] **Team Roster**: Roles and responsibilities documented
- [ ] **Communication Cadence**: Meeting schedule and channels defined
- [ ] **Decision Log**: Template created, any kickoff decisions recorded
- [ ] **Definition of Ready & Done**: Team-specific version documented

### Optional Artifacts
- [ ] **High-level architecture diagram**: If technical complexity warrants
- [ ] **Stakeholder communication plan**: Who gets updates, how often, what format
- [ ] **Success metrics dashboard**: Where to track OKRs or KPIs
- [ ] **Team working agreements**: Documented norms and expectations

## Post-Kickoff Actions

Within **1 week** of the kickoff:

- [ ] **Distribute meeting notes**: Share notes and action items with all attendees
- [ ] **Set up project infrastructure**:
  - Create or configure project board
  - Set up repo and documentation structure
  - Configure CI/CD pipeline (if needed)
- [ ] **Schedule recurring meetings**:
  - Daily standups
  - Sprint planning and retrospectives
  - Weekly PM/PdM sync
- [ ] **Refine initial backlog**: Break epics into stories with acceptance criteria
- [ ] **Engage dependency owners**: Reach out to teams you depend on
- [ ] **Complete DoR for sprint 1 items**: Ensure first batch of work is ready
- [ ] **Announce project launch**: Communicate to broader organization

## Kickoff Checklist Summary

### Before Kickoff
- [ ] Project one-pager finalized
- [ ] Team and stakeholders identified
- [ ] Meeting scheduled with agenda sent
- [ ] Pre-read materials distributed

### During Kickoff
- [ ] Project overview presented
- [ ] Roles and responsibilities clarified
- [ ] Timeline and milestones reviewed
- [ ] Initial backlog discussed
- [ ] RAID log started
- [ ] Communication norms established
- [ ] DoR/DoD agreed upon

### After Kickoff
- [ ] Meeting notes distributed
- [ ] Action items assigned and tracked
- [ ] Project infrastructure set up
- [ ] Recurring meetings scheduled
- [ ] Sprint 1 planning initiated

## Virtual Kickoff Tips

For remote or hybrid teams:

- **Use collaboration tools**: Miro, Mural, or Google Jamboard for interactive exercises
- **Breakout rooms**: For RAID brainstorming or team discussions
- **Cameras on**: Build rapport and engagement
- **Record the meeting**: For team members who can't attend or future reference
- **Visual aids**: Share screen with slides or live documents
- **Async component**: Consider a pre-kickoff survey to gather input
- **Follow-up**: Send recap video or summary for asynchronous review

## Kickoff Anti-Patterns to Avoid

❌ **Don't:**
- Skip kickoff to "save time" — you'll lose alignment later
- Make it a one-way presentation with no team input
- Overload with too much detail — keep it high-level
- Ignore team concerns or questions
- Schedule it for too short a time (< 60 min is rarely enough)
- Forget to document decisions and next steps

✅ **Do:**
- Make it interactive and collaborative
- Create space for questions and concerns
- Keep energy positive and enthusiastic
- Focus on alignment over perfection
- Follow up promptly with notes and actions
- Use kickoff to build team cohesion

## Measuring Kickoff Success

A successful kickoff results in:

- ✅ All team members can articulate project goals and success metrics
- ✅ Everyone knows their role and who to contact for what
- ✅ Initial risks and dependencies are identified and owned
- ✅ Team has confidence in the plan and feels heard
- ✅ Clear next steps with owners and deadlines
- ✅ Positive team energy and excitement to start

## Sample Kickoff Notes Template

```markdown
# [Project Name] Kickoff Notes

**Date:** [Date]  
**Attendees:** [List participants]

## Key Decisions
- [Decision 1]
- [Decision 2]

## Risks Identified
- [Risk 1 - Owner: Person A]
- [Risk 2 - Owner: Person B]

## Dependencies
- [Dependency 1 - Contact: Team X]
- [Dependency 2 - Contact: Team Y]

## Action Items
| Action | Owner | Due Date |
|--------|-------|----------|
| [Action 1] | [Name] | [Date] |
| [Action 2] | [Name] | [Date] |

## Next Meetings
- Sprint Planning: [Date/Time]
- Daily Standup: [Schedule]
- Sprint Review: [Date/Time]

## Questions / Open Issues
- [Question 1 - To be resolved by: Date]
- [Question 2 - To be resolved by: Date]
```

## Related Docs
- [Project Initiation](./octoacme-project-initiation.md) - Pre-kickoff preparation
- [Project Planning](./octoacme-project-planning.md) - Detailed planning after kickoff
- [RAID Log](./octoacme-raid-log.md) - Template for tracking risks and dependencies
- [Definition of Ready & Done](./octoacme-definition-of-ready-and-done.md) - Standards to establish
- [Decision Log](./octoacme-decision-log.md) - Document decisions made during kickoff
- [Roles & Personas](./octoacme-roles-and-personas.md) - Understanding team roles
