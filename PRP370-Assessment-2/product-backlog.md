# Product Backlog — CareerCraft

[← Back to PRP370 Assessment 2](./)

## 1. Product goal

Help South African students and graduates organise reusable career information and turn it into professional CVs, portfolios, LinkedIn content and application documents through one accessible platform.

The backlog below is based on the current CareerCraft repository structure, README and dated commit history. Priority labels are a retrospective proposed ordering for this portfolio, not a claim that a formal prioritisation workshop or Trello process took place.

## 2. Product backlog

| Priority | Backlog ID | Item | Related story | Status supported by repository | Evidence |
|---|---|---|---|---|---|
| Must | PB-01 | Account registration, login and user profile access. | US-01 | Implemented in repository; live security and account tests required. | [Authentication commit](https://github.com/Lwando6/CareerCraft/commit/5afc69b7cf0311729d714b5f0ae70706cfb96a41) |
| Must | PB-02 | Create and edit CV content through a modular resume editor. | US-02 | Implemented in repository; validate complete export and editing journey. | [Resume editor commit](https://github.com/Lwando6/CareerCraft/commit/7d62fd42a68199ee7ed520a85470f9e18390e20a) |
| Must | PB-03 | Save and retrieve user CVs. | US-03 | Implementation recorded; verify persistence and account isolation. | [CV save/template commit](https://github.com/Lwando6/CareerCraft/commit/91b42a0a38bcd0ecf49ea8b1296f174cac0e5169) |
| Should | PB-04 | Provide selectable resume layouts and designs. | US-04 | Layout changes recorded in repository; verify rendering on devices. | [Resume layouts](https://github.com/Lwando6/CareerCraft/commit/469df84181bd9a7345c13dcf30bc5e6aecc06bbe) |
| Should | PB-05 | Allow users to select GitHub projects for career portfolios and CVs. | US-05 | Implementation and refinement recorded. | [Project selection](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) |
| Should | PB-06 | Provide AI-assisted LinkedIn profile review. | US-06 | Implementation recorded; output quality and reliability require testing. | [LinkedIn tools](https://github.com/Lwando6/CareerCraft/commit/46c80a12313f50030a488c3f963d38c9bc5418f0) |
| Should | PB-07 | Generate LinkedIn post drafts with optional imagery. | US-07 | Text-only workflow recorded; test generation and saved history. | [Text-only post support](https://github.com/Lwando6/CareerCraft/commit/a85d0d34ac4d4d6d2ce3ab102aeb9c0cc66078fc) |
| Should | PB-08 | Generate career documents from improved prompts. | US-08 | Implementation recorded; review factual accuracy and edge cases. | [Career document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36) |
| Must | PB-09 | Enforce membership and subscription entitlements. | US-09 | Access-control code and database migrations recorded; end-to-end payment/access tests required. | [Subscription access commit](https://github.com/Lwando6/CareerCraft/commit/1eda674abfab99b9c89bcb12dbb527c22bb897f1) |
| Could | PB-10 | Improve accessibility, responsive behaviour and consistency across journeys. | Multiple | Some responsive and visual refinements recorded; broader usability testing still needed. | [Responsive journey commit](https://github.com/Lwando6/CareerCraft/commit/4e256dd3ec8970a3d353446050723b1e2d796319) |
| Could | PB-11 | Expand user testing and regression testing across the complete platform. | Multiple | Further evidence required. | [TO ADD: test record] |
| Could | PB-12 | Improve onboarding and help users understand available tools and plans. | Multiple | Further evidence required. | [TO ADD: feedback or usability record] |

## 3. Prioritisation rationale

For this assessment, the proposed priority ordering uses the following reasoning:

- **Must:** foundational capabilities needed for a usable and trustworthy career platform, such as authentication, CV creation, saving and subscription access control.
- **Should:** valuable career workflows that extend the usefulness of the platform, such as GitHub project selection and LinkedIn/document assistance.
- **Could:** improvements that strengthen usability, onboarding and quality but can be sequenced after core journeys.

This is a reasoned retrospective prioritisation. If a different method such as MoSCoW was actually used during development, attach the original planning artefact and update this section to reflect it.

## 4. Backlog refinement visible in Git history

| Date | Refinement / development activity | Why it matters |
|---|---|---|
| 15 Sep 2026 | Replaced the Tech CV concept with modular My CV and a prompt builder. | Shows a change in the way CV creation was structured. |
| 16 Sep 2026 | Updated CV saving, template access and AI provider integration. | Shows refinement of persistence, design access and AI integration. |
| 22 Sep 2026 | Added a step to show selected portfolio projects before adding them to a CV. | Shows refinement of the GitHub project selection journey. |
| 28 Sep 2026 | Added custom resume starting options, tiered layouts and career document generation. | Shows expansion and refinement of document workflows. |

Links:
- [15 September modular My CV commit](https://github.com/Lwando6/CareerCraft/commit/e0ff6c914cd4bcacb3db4ac0993ac19db55d5d76)
- [16 September CV saving and AI change](https://github.com/Lwando6/CareerCraft/commit/91b42a0a38bcd0ecf49ea8b1296f174cac0e5169)
- [22 September project selection refinement](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2)
- [28 September document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36)

## 5. Evidence — 10%

| Evidence ID | Artefact | What it demonstrates |
|---|---|---|
| PB-E01 | [CareerCraft README](https://github.com/Lwando6/CareerCraft/blob/main/README.md) | Product purpose, scope and technology. |
| PB-E02 | [CareerCraft commit history](https://github.com/Lwando6/CareerCraft/commits/main) | Incremental development and dated changes. |
| PB-E03 | [GitHub project selection refinement](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) | Evidence of iterative change to a product feature. |
| PB-E04 | [Subscription entitlement implementation](https://github.com/Lwando6/CareerCraft/commit/1eda674abfab99b9c89bcb12dbb527c22bb897f1) | Evidence of access-control work. |

**Additional evidence to add:** screenshot/export of the actual product backlog or Trello board, including dates and priority order if available.

## 6. Reflection — 10%

### Reflection draft for personal review

The CareerCraft product backlog helps organise a broad product vision into individual features that can be developed and reviewed. The repository shows that development covered several connected areas, including authentication, CV management, GitHub project selection, LinkedIn assistance and subscription controls.

An important learning point is that priority should not be based only on which feature is interesting to build. Foundational capabilities such as authentication and reliable CV saving affect whether users can trust the platform. Additional AI and portfolio features increase value, but they depend on a stable core experience.

The commit history also shows that backlog items can change as a workflow becomes clearer. For example, the GitHub project selection journey was refined to show selected projects before adding them to a CV. This is evidence of iteration, although the commit history does not reveal the original user feedback or formal reason for the change. I should include those details only if I have the original notes or can accurately explain the decision from my own experience.

**Before submission:** add one example of a feature you deliberately delayed or reprioritised, why you made that choice, and what trade-off it involved.

## 7. Connection to sprint planning

The Sprint Backlog should select a manageable subset of these items for a defined sprint goal. Use the PB identifiers above so the lecturer can trace each selected item back to its user story and the evidence of implementation.

---
[← Portfolio home](./)
