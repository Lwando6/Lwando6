# Agile Logbook — CareerCraft

[← Back to PRP370 Assessment 2](./)

## 1. Purpose and evidence approach

This assessment also draws on the existing **CareerCraft Agile Team Logbook, 1 June–30 September 2026** (version 1.0, dated 27 October 2026), which records four initiation weeks and 14 delivery sprints. That source distinguishes documented entries from reconstructed entries and evidence still to verify. Trello was used partially; the source logbook refers to some Trello/taskboard artefacts, but not every sprint has a complete Trello export attached.

This page cross-references the source logbook with the dated CareerCraft GitHub commit history. Commit dates and messages demonstrate recorded code changes; they do not, by themselves, prove a daily stand-up, sprint ceremony, user test or acceptance result. Keep the source logbook's labels: **Documented**, **Reconstructed — confirm with project evidence**, and **To verify**. See the [Sprint Backlog](./sprint-backlog.md) for the 14-sprint index and evidence checklist.

## 2. Dated development records

### 14 September 2026 — Initial platform and core workflows

**Repository evidence:** [CareerCraft commits on 14 September](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-14T00:00:00Z&until=2026-09-15T00:00:00Z)

- **Recorded activity:** Initial repository and homepage; core application pages; authentication-related files and Supabase integration; resume editor and payment/subscription flow.
- **Related backlog items:** PB-01, PB-02, PB-09.
- **What this record demonstrates:** The initial product foundation and early focus on user access and career document creation.
- **Planning/stand-up record:** Not present in the commit history.
- **Learning/reflection to complete:** [Add what you found difficult while setting up the first connected workflows and how you addressed it.]

### 15 September 2026 — CV workflow and LinkedIn tools

**Repository evidence:**
- [Modular My CV and prompt builder](https://github.com/Lwando6/CareerCraft/commit/e0ff6c914cd4bcacb3db4ac0993ac19db55d5d76)
- [LinkedIn profile audit and post generator](https://github.com/Lwando6/CareerCraft/commit/46c80a12313f50030a488c3f963d38c9bc5418f0)
- [Text-only LinkedIn posts](https://github.com/Lwando6/CareerCraft/commit/a85d0d34ac4d4d6d2ce3ab102aeb9c0cc66078fc)

- **Recorded activity:** Restructuring the CV workflow into modular My CV and prompt-building functionality; adding LinkedIn profile and post-generation tools; supporting text-only post creation.
- **Related backlog items:** PB-02, PB-06, PB-07, PB-08.
- **What this record demonstrates:** Expansion from basic career pages into connected career-development workflows.
- **Planning/stand-up record:** Not present in the commit history.
- **Learning/reflection to complete:** [Explain why the modular CV approach was useful and what you learned while developing the LinkedIn tools.]

### 16 September 2026 — Integration refinement and portfolio functionality

**Repository evidence:**
- [CV saving, template access and AI migration](https://github.com/Lwando6/CareerCraft/commit/91b42a0a38bcd0ecf49ea8b1296f174cac0e5169)
- [GitHub projects added to CVs](https://github.com/Lwando6/CareerCraft/commit/8bfe1ebec19e8bc1d96fce0281d71d3e7c080aea)
- [AI integration and error-handling changes](https://github.com/Lwando6/CareerCraft/commit/68acd9cbd17a0e309cd12912083a8166794fec35)

- **Recorded activity:** Changes to CV saving and template access; GitHub project integration; AI provider and error-handling refinements.
- **Related backlog items:** PB-03, PB-04, PB-05, PB-08.
- **What this record demonstrates:** Work on persistence, external integrations and reliability.
- **Planning/stand-up record:** Not present in the commit history.
- **Learning/reflection to complete:** [Describe a specific integration issue you encountered, what you tried and the outcome.]

### 22 September 2026 — GitHub project selection refinement

**Repository evidence:** [Show selected portfolio projects before adding to CV](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2)

- **Recorded activity:** A refinement to the GitHub project selection flow.
- **Related backlog item:** PB-05.
- **What this record demonstrates:** Iterative refinement of a user journey rather than treating the first implementation as final.
- **Planning/stand-up record:** Not present in the commit history.
- **Learning/reflection to complete:** [Explain why showing selected projects before adding them matters to the user and whether you observed or anticipated this need.]

### 28 September 2026 — Resume options, document generation and subscription access

**Repository evidence:**
- [Subscription access enforcement](https://github.com/Lwando6/CareerCraft/commit/1eda674abfab99b9c89bcb12dbb527c22bb897f1)
- [Custom resume starting option](https://github.com/Lwando6/CareerCraft/commit/5aee2573b4404f2e2a5785fa0f6ce3af665cb8eb)
- [Tiered resume layouts](https://github.com/Lwando6/CareerCraft/commit/0601ba2549b7f82c6f85a95ac5c7557369b2df5)
- [AI career document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36)

- **Recorded activity:** Subscription entitlement work, custom resume creation options, additional resume layouts and prompt-based career document generation.
- **Related backlog items:** PB-04, PB-08, PB-09.
- **What this record demonstrates:** Continued product expansion and attention to monetisation/access rules.
- **Planning/stand-up record:** Not present in the commit history.
- **Learning/reflection to complete:** [Explain how you balanced new features with subscription rules and what you would test before release.]

## 3. Logbook summary

| Date | Recorded development focus | Related backlog items | Evidence |
|---|---|---|---|
| 14 Sep 2026 | Initial platform, authentication, resume editor and subscription flow | PB-01, PB-02, PB-09 | [Commits](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-14T00:00:00Z&until=2026-09-15T00:00:00Z) |
| 15 Sep 2026 | Modular CV, prompt builder and LinkedIn tools | PB-02, PB-06, PB-07, PB-08 | [Commits](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-15T00:00:00Z&until=2026-09-16T00:00:00Z) |
| 16 Sep 2026 | CV saving, templates, GitHub portfolio and AI refinement | PB-03, PB-04, PB-05, PB-08 | [Commits](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-16T00:00:00Z&until=2026-09-17T00:00:00Z) |
| 22 Sep 2026 | GitHub project selection refinement | PB-05 | [Commit](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) |
| 28 Sep 2026 | Resume layouts, document generation and subscription access | PB-04, PB-08, PB-09 | [Commits](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-28T00:00:00Z&until=2026-09-29T00:00:00Z) |

## 4. Evidence — 10%

The linked Git commits are primary evidence of dated repository changes. To strengthen the portfolio, add screenshots of the working application, actual task-board updates, testing notes and any sprint review/retrospective records that exist.

| Evidence ID | Artefact | What it demonstrates |
|---|---|---|
| AL-E01 | [Full CareerCraft commit history](https://github.com/Lwando6/CareerCraft/commits/main) | Chronology of repository changes. |
| AL-E02 | [15 September modular CV commit](https://github.com/Lwando6/CareerCraft/commit/e0ff6c914cd4bcacb3db4ac0993ac19db55d5d76) | A dated feature change. |
| AL-E03 | [22 September GitHub selection refinement](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) | A dated iteration of an existing workflow. |
| AL-E04 | [28 September career document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36) | A dated implementation milestone. |

## 5. Reflection — 10%

### Reflection draft for personal review

The commit history gives me a timeline of how CareerCraft developed across September 2026. It shows that I worked on several connected product areas and refined features over time. This record is useful because it makes the development process more visible than a final application demonstration alone.

The entries also show why a logbook should capture more than completed code. A commit can show what changed, but it does not explain the original problem, the alternatives considered, the time spent, the blocker encountered or whether the result was tested with a user. Those details are important for understanding my decision-making and learning.

Going forward, I should record the goal before each work session, the tasks selected, the result, any blockers and the next action. I should also keep sprint review and retrospective notes. This would make my planning more transparent and help me compare intended work with actual outcomes.

**Before submission:** add your own account of the challenges you faced, decisions you made and what you would do differently. The current repository history does not provide enough information to write those personal details on your behalf.

## 6. Retrospective prompts to complete

- What went well during the development period?
- What caused delays or required rework?
- Which feature changed most after initial implementation?
- What did I learn about breaking work into smaller tasks?
- What one process improvement will I apply next?

---
[← Portfolio home](./)


## 7. Project-level Agile logbook cross-reference

The source CareerCraft Agile Team Logbook records four initiation weeks followed by 14 delivery sprints. It describes daily coordination, sprint planning, reviews, retrospectives, impediments and evidence fields. The detailed sprint periods, goals and source evidence status are indexed in the [Sprint Backlog](./sprint-backlog.md).

### Source logbook evidence status

| Source classification | Meaning | How it is treated in this portfolio |
|---|---|---|
| Documented | Taken from supplied daily stand-ups, taskboards and sprint walkthroughs. | Retain the original record and attach the referenced evidence where available. |
| Reconstructed | Created from milestone continuity and detailed sprint history. | Confirm wording, owners, dates and evidence with the team before final submission. |
| To verify | An evidence type is identified but the file/link is not embedded. | Add the actual artefact or leave the evidence item clearly outstanding. |

### Trello usage

Trello was used partially. The source logbook references a Trello export and ownership record for the 22 July Sprint 4 backlog-refinement activity. The actual export is not embedded in the source logbook available for this portfolio, so it is listed as an outstanding evidence item rather than claimed as attached.

See [Trello Evidence — Partial Use](./trello-evidence.md) for the evidence register and upload checklist.

### Team and project context

The source logbook identifies:
- Lwandile Mangali — Product Owner and Project Manager.
- Sello Makhunyane — Lead Developer and Technical Coordinator.
- Livhuwani Madavha — UX/UI Designer and Front-end Developer.
- Lerato Motsweni — Business Analyst and Quality Assurance Lead.

These roles are reproduced from the source logbook. Confirm them with the team before final submission.

### Reflection note

The project logbook and source-code history provide complementary views. The Agile logbook describes planning, collaboration, review and retrospective activity; Git commits provide a separate record of code changes. Connecting the two makes the development process easier to trace, but a code commit should not be treated as proof that a sprint ceremony or user test happened.

**Before submission:** add personal details about your actual Trello use, what was recorded elsewhere, a real blocker and what you learned from the team's planning and review process.
