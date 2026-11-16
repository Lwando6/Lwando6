# Agile Team Charter — CareerCraft

[← Back to PRP370 Assessment 2](./)

## 1. Project identity

| Item | Description |
|---|---|
| Product | CareerCraft SA |
| Product type | South Africa-first digital career development platform |
| Project team | Lwandile Mangali, Sello Makhunyane, Livhuwani Madhavha (spelling to confirm against logbook) and Lerato Motsweni |
| Assessment | PRP370 — Project Presentation 3, Assessment 2 |
| Repository | [Lwando6/CareerCraft](https://github.com/Lwando6/CareerCraft) |
| Live application | [careercraft-sa.netlify.app](https://careercraft-sa.netlify.app) |
| Evidence source | [CareerCraft commit history](https://github.com/Lwando6/CareerCraft/commits/main) |

## 2. Product purpose and vision

CareerCraft aims to help students and graduates maintain reusable career information and turn it into career documents and professional content. The repository describes the product as a South Africa-first platform for creating recruiter-ready CVs, portfolios, LinkedIn content and application documents.

The project responds to a practical problem: early-career job seekers often need to prepare and update several career materials for different opportunities. CareerCraft brings related workflows into one platform, including profile information, CV creation, GitHub project selection and AI-assisted career content.

## 3. Scope

### Product capabilities evidenced in the repository

- Account registration, authentication and user profiles.
- Modular CV creation, saved CVs and resume template selection.
- GitHub project selection for CV/portfolio content.
- AI-assisted LinkedIn profile and post tools.
- Career prompt and document-generation workflows.
- Membership and subscription access-control implementation.
- Personal branding guidance.

These capabilities are supported by repository files and commit messages. A code commit demonstrates that a change was recorded; it does not, by itself, prove that every user journey is fully tested or operating correctly in production.

### Boundaries and constraints

- CareerCraft was developed as a team project. The supplied CareerCraft Agile Team Charter identifies four team members and assigns primary roles. The team charter source uses the spelling “Livhuwani Madhavha”, while the separate team logbook uses “Livhuwani Madavha”; confirm the correct spelling with the team before final submission.
- CareerCraft is an evolving product. Features must be labelled accurately as implemented, in progress or planned.
- AI-generated career content must be reviewed by the user and must not invent qualifications, work experience or achievements.
- Secrets and API credentials must not be committed to the public repository.
- Authentication, payment and subscription decisions require appropriate server-side checks and access controls.
- Time, technical complexity, integration dependencies and available resources influence the order in which work can be delivered.

## 4. Individual working agreements

The supplied CareerCraft Agile Team Charter records shared responsibilities, communication practices, working agreements, a definition of ready/done and risk responses. The principles below summarise those source artefacts. Confirm that the team still agrees with them before treating this page as the approved current charter.

| Principle | Working agreement | How I can demonstrate it |
|---|---|---|
| User value | Prioritise features that solve a clear career-preparation problem. | Link backlog items to user needs. |
| Incremental delivery | Break large features into smaller changes that can be reviewed. | Git commits and version history. |
| Transparency | Record what is implemented, in progress and planned. | Backlog status and dated logbook. |
| Quality | Check user journeys, errors and edge cases before treating work as complete. | Test notes, screenshots and issue records. |
| Security and privacy | Keep secrets out of source control and protect user data. | Configuration, server-side functions and security review. |
| Accuracy | AI-generated CV and LinkedIn content must remain grounded in user-provided facts. | Prompt rules and manual review. |
| Continuous improvement | Use defects and feedback to guide the next changes. | Bug-fix commits and retrospective notes. |

## 5. Roles and responsibilities

The source Agile Team Charter assigns the following primary roles. These are team responsibilities, not claims that every member completed every task. Confirm the names and role assignments with the team before approval.

| Responsibility | My contribution |
|---|---|
| Lwandile Mangali — Product Owner and Project Manager | Own product vision and backlog; prioritise user value; coordinate sprints; approve increments; manage stakeholders and project risks. |
| Sello Makhunyane — Lead Developer and Technical Coordinator | Guide technical implementation; integrate front-end and back-end work; review code; support deployment, security and defect resolution. |
| Livhuwani Madhavha — UX/UI Designer and Front-end Developer | Map user journeys; create accessible interfaces; maintain visual consistency; implement responsive components and usability improvements. |
| Lerato Motsweni — Business Analyst and Quality Assurance Lead | Refine requirements and acceptance criteria; maintain traceability; coordinate testing; document defects, evidence and review outcomes. |

## 6. Definition of done

A backlog item should not be labelled complete solely because a page or code file exists. Before calling a feature done, I should verify that:

1. The intended user need and acceptance criteria are addressed.
2. The relevant workflow functions in the intended environment.
3. Expected and invalid inputs are handled appropriately.
4. Authentication, access control and privacy implications have been considered.
5. The change does not knowingly break related journeys.
6. Relevant evidence, test notes or a commit link is recorded.
7. Known limitations are documented honestly.

## 7. Evidence — 10%

The following repository artefacts provide initial evidence of project scope and individual development activity.

| Evidence ID | Artefact | What it supports |
|---|---|---|
| ATC-01 | Supplied CareerCraft Agile Team Charter (2026) | Team purpose, vision, success definition, scope boundaries, role allocation, shared responsibilities, risk management and approval section. Upload the original PDF/DOCX to the evidence folder. |
| ATC-02 | [CareerCraft README](https://github.com/Lwando6/CareerCraft/blob/main/README.md) | Product purpose, core capabilities, technology and project structure. |
| ATC-03 | [Initial project commit](https://github.com/Lwando6/CareerCraft/commit/4528a411b97ea62db31ebd793fc8ca4cb1a427fb) | Initial repository setup. |
| ATC-04 | [Supabase authentication changes](https://github.com/Lwando6/CareerCraft/commit/5afc69b7cf0311729d714b5f0ae70706cfb96a41) | Authentication-related implementation activity. |
| ATC-05 | [CareerCraft project history](https://github.com/Lwando6/CareerCraft/commits/main) | Dated record of incremental changes. |

**Additional evidence to add:** a screenshot or export of the product's current user journey, a project planning artefact, and any actual working notes used to guide the work.

## 8. Reflection — 10%

### Reflection draft for personal review

CareerCraft has required me to think beyond building individual web pages and consider how separate features contribute to one coherent product. The repository history shows development across authentication, CV creation, GitHub portfolio integration, AI-assisted LinkedIn tools and subscription access. This demonstrates that the product scope expanded through a sequence of changes rather than being delivered as one isolated feature.

One important lesson from this project is the need to balance feature development with reliability and user trust. For a career platform, inaccurate AI-generated information could negatively affect a job seeker's application. Authentication, privacy, subscription enforcement and server-side verification are also important because the platform handles user information and paid access.

The Git history gives me a useful record of implementation activity, but I recognise that a commit alone is not proof of a fully tested feature. My working definition of done therefore needs to include acceptance criteria, testing and evidence of the user journey, not only code changes.

**Before submission:** revise this draft so it accurately describes your own decisions, challenges and learning. Add a specific example of a feature you personally tested, a problem you encountered and how you responded.

## 9. Connection to other artefacts

The product purpose informs the user stories. The user stories are grouped and prioritised in the Product Backlog. Selected work should then be planned as a Sprint Backlog with a sprint goal and measurable tasks. The Agile Logbook records dated progress and learning, while the evidence register links claims to actual artefacts.

---
[← Portfolio home](./)
