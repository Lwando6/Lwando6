# Sprint Backlog — CareerCraft

[← Back to PRP370 Assessment 2](./)

## 1. Source and evidence approach

This page is based on the existing **CareerCraft Agile Team Logbook, 1 June–30 September 2026** (version 1.0, dated 27 October 2026), together with the CareerCraft GitHub commit history.

The source logbook records four initiation weeks followed by 14 delivery sprints. It explicitly distinguishes:
- **Documented:** taken from supplied daily stand-ups, taskboards and sprint walkthroughs.
- **Reconstructed:** created from milestone continuity and sprint history; must be checked against Trello, Git, Figma, lecturer feedback, meeting notes and deployment records.
- **To verify:** an evidence type is identified but the actual file or link is not embedded.

The fact that Trello was used partially does not mean every sprint has a complete Trello record. This page preserves the source logbook's evidence labels and does not claim that every sprint card or ceremony is independently verified.

## 2. Sprint overview

| Sprint | Period | Sprint focus / goal | Source logbook status |
|---|---|---|---|
| 1 | 30 Jun–3 Jul 2026 | Project framing: define the primary problem, target audience, learner outcome and initial feature map. | Reconstructed — confirm against project evidence |
| 2 | 7–10 Jul 2026 | Business model and pitch preparation: develop the business/marketing proposition and investor-style presentation. | Reconstructed — confirm against project evidence |
| 3 | 14–17 Jul 2026 | Investor pitch and business-plan evidence: finalise and deliver the pitch, strengthen market and competitor evidence. | Documented in supplied logbook |
| 4 | 21–24 Jul 2026 | Backlog refinement and sprint readiness: translate lecturer feedback into a prioritised, owned, implementation-ready backlog. | Documented in supplied logbook |
| 5 | 28–31 Jul 2026 | User-interface prototype and accessibility redesign: design core Figma screens and revise the visual system after lecturer feedback. | Documented in supplied logbook |
| 6 | 4–7 Aug 2026 | Prototype showcase and brand improvements: demonstrate the prototype and implement feedback on branding, Free Tier, visual tone and links. | Documented in supplied logbook |
| 7 | 11–14 Aug 2026 | Brand system and responsive design readiness: formalise brand rules, audit mobile layouts and prepare reusable style tokens. | Reconstructed — confirm against project evidence |
| 8 | 18–21 Aug 2026 | Front-end foundation and navigation: establish the multi-page structure and consistent navigation across core journeys. | Reconstructed — confirm against project evidence |
| 9 | 25–28 Aug 2026 | Authentication and career-profile foundation: enable account access and establish user-owned career profile data. | Reconstructed — confirm against project evidence |
| 10 | 1–4 Sep 2026 | Modular CV editor and template workflow: create/update CVs through modular sections and selectable layouts. | Reconstructed — confirm against project evidence |
| 11 | 7–11 Sep 2026 | CV persistence and profile retrieval: connect CV editing to Supabase so users can save and retrieve documents. | Reconstructed — confirm against project evidence |
| 12 | 14–18 Sep 2026 | LinkedIn profile and post tools: prototype profile makeover and photo-optional post generation through hosted AI functions. | Reconstructed — confirm against project evidence |
| 13 | 21–25 Sep 2026 | AI integration hardening: validate the Gemini provider integration, response parsing, safe logs and error handling. | Reconstructed — confirm against project evidence |
| 14 | 28–30 Sep 2026 | Subscription entitlements and portfolio integration: connect GitHub project selection to CVs and define plan-access/payment-ready flows. | Reconstructed from September implementation evidence — team confirmation required |

**Important:** A reconstructed sprint entry is a useful planning/history record, not proof that every listed task was completed exactly as written. Confirm its dates, owners, task statuses and review outcome against original records before final submission.

## 3. Detailed sprint taskboards

### Sprint 3 — Investor pitch and business-plan evidence

**Period:** 14–17 July 2026  
**Status:** Documented in supplied logbook  
**Goal:** Finalise and deliver the investor-style pitch, then strengthen Deliverable 2 with verified market and competitor evidence.

| Work item | Recorded owner(s) |
|---|---|
| Confirm slide order, speaking roles and section ownership | Lwandile |
| Refine visual sequence and presentation flow | Livhuwani |
| Finalise financial projections and supporting assumptions | Lerato |
| Check slides, timing cues and technical readiness | Sello |
| Deliver panel presentation and begin follow-up research | Whole team |

**Recorded increment:** Final 16-slide pitch deck, Deliverable 2 submission, investor-style pitch delivered on 15 July, market/competitor research notes and pitch retrospective.

### Sprint 4 — Backlog refinement and sprint readiness

**Period:** 21–24 July 2026  
**Status:** Documented in supplied logbook  
**Goal:** Translate lecturer feedback into a prioritised, owned and implementation-ready Product Backlog.

| Work item | Recorded owner(s) |
|---|---|
| Review lecturer feedback | Whole team |
| Rewrite unclear user stories and task descriptions | Lwandile and Lerato |
| Confirm technical implementation ownership | Sello |
| Identify design inputs and resources for the next sprint | Livhuwani |
| Resolve overlapping ownership and balance workloads | Whole team |

**Recorded increment:** Refined Product Backlog, updated priorities/statuses, assigned task ownership and implementation-ready design backlog.

**Trello reference in source logbook:** The 22 July entry identifies “Trello export; ownership record” as an evidence field. The export itself is not embedded in the source document or this repository yet. Add the actual export/screenshot if available.

### Sprint 5 — User-interface prototype and accessibility redesign

**Period:** 28–31 July 2026  
**Status:** Documented in supplied logbook  
**Goal:** Design the core CareerCraft experience in Figma, obtain lecturer feedback and revise the interface toward a brighter, accessible visual system.

| Work item | Recorded owner(s) |
|---|---|
| Wireframe dashboard and job-matching screens | Lwandile |
| Update job-matching and profile screens | Livhuwani |
| Update CV builder and dashboard components | Sello |
| Research colour contrast and accessible palette guidance | Lerato |
| Consolidate screens and coordinate lecturer review | Whole team |

**Recorded review outcome:** The lecturer considered the dark theme too heavy; the team revised the palette and completed an internal walkthrough.

**Recorded increment:** Low-fidelity wireframes, interactive Figma prototype, brighter revised palette, colour-contrast reference guide and updated prototyping backlog.

### Sprint 6 — Prototype showcase and brand improvements

**Period:** 4–7 August 2026  
**Status:** Documented in supplied logbook  
**Goal:** Demonstrate the website prototype and implement lecturer feedback on branding, pricing access, visual tone and functional links.

| Work item | Recorded owner(s) |
|---|---|
| Update remaining Figma screens with the bright palette | Livhuwani |
| Design and finalise CareerCraft logo | Lerato with team review |
| Build Free Tier section and outline its limits | Sello |
| Draft Brand Guideline and connect GitHub buttons | Lwandile |
| Complete full-team walkthrough | Whole team |

**Recorded increment:** First-class prototype showcase, bright colour system, CareerCraft logo, Free Tier option, Brand Guideline and functional GitHub repository links.

### Sprints 1–2 and 7–14

The existing source logbook contains sprint goals, taskboards, owners, risks and expected increments for these periods too, but labels them reconstructed and requiring team confirmation. Use the Sprint Overview above as the index; consult the original logbook and compare it against dated Trello, GitHub, Figma and deployment records before marking any task complete.

## 4. CareerCraft GitHub implementation cross-check

The following later code commits provide a separate implementation trail. They do not prove that the work was planned or completed in a particular sprint unless dates and scope are corroborated by the original sprint records.

| Date | Repository change | Related product area |
|---|---|---|
| 14 Sep 2026 | [Initial platform/authentication/resume work](https://github.com/Lwando6/CareerCraft/commits/main?since=2026-09-14T00:00:00Z&until=2026-09-15T00:00:00Z) | Authentication, CV editor |
| 15 Sep 2026 | [Modular My CV and prompt builder](https://github.com/Lwando6/CareerCraft/commit/e0ff6c914cd4bcacb3db4ac0993ac19db55d5d76) | CV workflow |
| 15 Sep 2026 | [LinkedIn profile audit and post generator](https://github.com/Lwando6/CareerCraft/commit/46c80a12313f50030a488c3f963d38c9bc5418f0) | LinkedIn tools |
| 16 Sep 2026 | [CV saving and template access](https://github.com/Lwando6/CareerCraft/commit/91b42a0a38bcd0ecf49ea8b1296f174cac0e5169) | CV persistence |
| 16 Sep 2026 | [GitHub projects in CVs](https://github.com/Lwando6/CareerCraft/commit/8bfe1ebec19e8bc1d96fce0281d71d3e7c080aea) | Portfolio integration |
| 22 Sep 2026 | [GitHub project selection refinement](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) | Portfolio-to-CV journey |
| 28 Sep 2026 | [Subscription access enforcement](https://github.com/Lwando6/CareerCraft/commit/1eda674abfab99b9c89bcb12dbb527c22bb897f1) | Plan entitlements |
| 28 Sep 2026 | [Career document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36) | AI document workflow |

## 5. Trello evidence — partial use

You confirmed that Trello was used partially. The portfolio should therefore say exactly that: Trello was used for some planning/taskboard activity, while the available records do not yet establish a complete board history for all 14 sprints.

| Evidence ID | What to attach | Current status |
|---|---|---|
| TR-01 | Trello board screenshot showing board name, lists and cards | To add |
| TR-02 | Export or screenshots of Sprint 4 backlog refinement/ownership around 22 July | Referenced by source logbook; actual artefact not yet attached |
| TR-03 | Any available Sprint 3, 5 or 6 taskboard screenshots | To add if available |
| TR-04 | Trello activity/card history with dates and members, if available | To add if available |
| TR-05 | Any later/earlier cards that link sprint work to CareerCraft implementation | To add if available |

Do not create retrospective Trello cards and present them as original historical records. If you recreate a board now for clarity, label it **reconstructed from the project logbook and Git history** and keep the original evidence separate.

## 6. Proposed sprint plan for remaining verification work

This is a current proposed plan, not a historical sprint from June–September 2026.

**Sprint goal:** Close the evidence gaps and verify the most important CareerCraft user journeys before final portfolio submission.

| Task ID | Task | Acceptance / completion evidence | Status |
|---|---|---|---|
| EV-01 | Export or screenshot the existing Trello board and relevant cards. | Original board name, lists, card titles and visible dates/owners captured. | To do |
| EV-02 | Confirm which source-logbook sprints have Trello records. | Each sprint labelled documented, partially evidenced or reconstructed. | To do |
| EV-03 | Link original Figma prototype and brand artefacts. | Working Figma links or dated exports attached. | To do |
| EV-04 | Link CareerCraft commits to the relevant backlog items. | Commit links support implementation activity without overstating testing. | In progress |
| EV-05 | Capture actual product screenshots and test results. | Dated screenshots/test cases show expected and actual results. | To do |
| EV-06 | Ask the team to confirm reconstructed entries and owners. | Confirmation notes or corrected records attached. | To do |

## 7. Evidence — 10%

Evidence to include for this criterion:

1. Sprint taskboard/export or screenshots, with card titles, owners, dates and status where available.
2. Sprint goals and selected tasks for each sprint.
3. Evidence of completed increments, such as Figma frames, pitch deck, source commits or working product screenshots.
4. Review and retrospective records, with acceptance criteria marked Met, Partially Met or Carried Over only where confirmed.
5. Clear labels for reconstructed and unverified entries.

## 8. Reflection — 10%

### Reflection draft — review and personalise

CareerCraft's sprint records show a progression from problem framing and business planning into backlog refinement, prototyping, brand development and technical implementation. The documented July and early-August sprints show how lecturer feedback influenced the backlog and design direction. For example, the feedback that the dark prototype was too heavy led to a brighter palette and further attention to contrast and readability.

The later reconstructed sprint records describe the intended technical progression into navigation, authentication, CV editing and persistence, LinkedIn tools, AI integration and subscription/portfolio workflows. These records help explain the product's development, but I need to verify them against original Trello activity, Figma versions and GitHub commits before presenting every detail as confirmed.

My use of Trello was partial. This means I should not imply that every task, daily coordination entry or sprint retrospective was captured in Trello. An improvement is to keep one consistent taskboard for each sprint, link each card to its user story and commit/design evidence, and capture review and retrospective outcomes at the end of the sprint.

**Personalise before submission:** explain which Trello activities you personally used, what was tracked outside Trello, one real blocker you experienced and how the team addressed it. Confirm the sprint entries with the other team members before signing off the reconstructed sections.

## 9. Final verification checklist

- [ ] Confirm the team member names, roles and responsibilities.
- [ ] Attach the original Trello board screenshot/export that is available.
- [ ] Verify Sprint 4's referenced 22 July Trello export/ownership record, if it can be recovered.
- [ ] Confirm reconstructed sprint dates, task owners and outcomes with the team.
- [ ] Add Figma links/screenshots for prototype and brand work.
- [ ] Add relevant CareerCraft commit links and product screenshots.
- [ ] Mark acceptance criteria Met, Partially Met or Carried Over based on actual evidence.
- [ ] Complete the reflection in my own words.
- [ ] Remove any statement that cannot be supported.

---
[← Portfolio home](./)
