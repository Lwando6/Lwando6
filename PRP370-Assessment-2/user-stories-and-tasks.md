# User Stories and Tasks — CareerCraft

[← Back to PRP370 Assessment 2](./)

## 1. Product context

CareerCraft is a South Africa-first career platform intended to help students and graduates organise reusable career information and produce CVs, portfolios, LinkedIn content and application documents.

The stories below are derived from the features and workflows represented in the CareerCraft repository. They describe intended user value; the status column distinguishes repository evidence from features that still require live verification.

## 2. User stories and acceptance criteria

| ID | User story | Acceptance criteria | Repository evidence / status |
|---|---|---|---|
| US-01 | As a job seeker, I want to register, sign in and manage my profile so that I can access my career information securely. | Registration and sign-in provide clear success/error feedback; protected areas require authentication; user data is associated with the correct account. | Authentication-related files and [14 Sep authentication commit](https://github.com/Lwando6/CareerCraft/commit/5afc69b7cf0311729d714b5f0ae70706cfb96a41). Live security behaviour still requires testing. |
| US-02 | As a job seeker, I want to create and edit a CV so that I can prepare a professional document for applications. | User can enter and edit relevant CV sections; selected layout is applied; output can be reviewed before use. | Resume editor and [14 Sep resume editor commit](https://github.com/Lwando6/CareerCraft/commit/7d62fd42a68199ee7ed520a85470f9e18390e20a). |
| US-03 | As a returning user, I want to save and retrieve my CVs so that I do not need to recreate them each time. | A saved CV is linked to the signed-in user; saved records can be retrieved and edited; access is not exposed to other users. | [16 Sep CV saving and template access commit](https://github.com/Lwando6/CareerCraft/commit/91b42a0a38bcd0ecf49ea8b1296f174cac0e5169). Verify with a live account test. |
| US-04 | As a job seeker, I want to choose a resume design so that I can present my experience in a suitable layout. | Available designs can be previewed and selected; chosen design is reflected in the CV output. | [28 Sep tiered resume layouts](https://github.com/Lwando6/CareerCraft/commit/0601ba2549b7f82c6f85a95ac5c7557369b2df5) and [sidebar designs](https://github.com/Lwando6/CareerCraft/commit/469df84181bd9a7345c13dcf30bc5e6aecc06bbe). |
| US-05 | As a job seeker, I want to select my GitHub projects for my CV or portfolio so that I can demonstrate practical work. | User can view available projects, select relevant ones and include chosen project information in a CV/portfolio. | [16 Sep GitHub projects commit](https://github.com/Lwando6/CareerCraft/commit/8bfe1ebec19e8bc1d96fce0281d71d3e7c080aea) and [22 Sep project selection commit](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2). |
| US-06 | As a job seeker, I want help reviewing my LinkedIn profile so that I can improve how I present myself professionally. | User can submit profile information for review; results are readable and relevant; user can review suggestions before applying them. | [15 Sep LinkedIn profile audit and post generator commit](https://github.com/Lwando6/CareerCraft/commit/46c80a12313f50030a488c3f963d38c9bc5418f0). |
| US-07 | As a job seeker, I want to generate LinkedIn post drafts with or without an image so that I can create professional content in a format that suits me. | User can request a text draft; image use is optional; generated content can be reviewed before publication. | [15 Sep text-only LinkedIn posts commit](https://github.com/Lwando6/CareerCraft/commit/a85d0d34ac4d4d6d2ce3ab102aeb9c0cc66078fc). |
| US-08 | As a job seeker, I want to generate career documents from prompts so that I can prepare application material more efficiently. | User can choose a document workflow, provide relevant details, generate a draft and review it for accuracy. | [28 Sep career document generation commit](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36). |
| US-09 | As a subscriber, I want access to match my membership so that the platform applies its stated subscription entitlements. | Access checks are applied consistently; restricted actions are not granted merely by hiding interface controls; server-side rules are checked. | [28 Sep subscription access commit](https://github.com/Lwando6/CareerCraft/commit/1eda674abfab99b9c89bcb12dbb527c22bb897f1). Requires end-to-end verification. |

## 3. Task breakdown

The following are task examples derived from the repository structure and implemented workflows. They are not presented as a historical Trello export.

| Task ID | Story | Task | Evidence / related files |
|---|---|---|---|
| T-01 | US-01 | Build registration and login interface. | `signup.html`, `login.html` |
| T-02 | US-01 | Connect authentication flows to Supabase. | `auth.js`, authentication commit |
| T-03 | US-02 | Build the resume editor interface. | `editor.html`, `resume-editor.js` |
| T-04 | US-03 | Implement save/retrieve behaviour for CV records. | CV saving commit; verify database behaviour |
| T-05 | US-04 | Add resume layout options and previews. | Resume design commits |
| T-06 | US-05 | Retrieve GitHub project information and present project choices. | `portfolio.js`, GitHub project commits |
| T-07 | US-06 | Implement LinkedIn profile review workflow. | `linkedin.html`, `linkedin-tools.js` |
| T-08 | US-07 | Support text-only LinkedIn post generation. | Text-only post commit |
| T-09 | US-08 | Build prompt-based career document generation. | `prompts.html`, `prompt-builder.js`, career prompt function |
| T-10 | US-09 | Apply subscription entitlement checks. | Supabase migrations and access-control implementation |

## 4. Evidence — 10%

| Evidence ID | Artefact | What it demonstrates |
|---|---|---|
| UST-01 | [Initial CareerCraft implementation](https://github.com/Lwando6/CareerCraft/commit/4528a411b97ea62db31ebd793fc8ca4cb1a427fb) | Starting point of the product repository. |
| UST-02 | [Modular My CV and prompt builder](https://github.com/Lwando6/CareerCraft/commit/e0ff6c914cd4bcacb3db4ac0993ac19db55d5d76) | Development of a reusable CV workflow. |
| UST-03 | [GitHub project selection](https://github.com/Lwando6/CareerCraft/commit/6e428094c0e942fe67107afbdf6bcf1689704dc2) | Refinement of portfolio project selection. |
| UST-04 | [LinkedIn profile audit and post generator](https://github.com/Lwando6/CareerCraft/commit/46c80a12313f50030a488c3f963d38c9bc5418f0) | Development of LinkedIn-related user workflows. |
| UST-05 | [Career document generation](https://github.com/Lwando6/CareerCraft/commit/b6e97ad52e64c4800dd562c25752cb3e11320e36) | Prompt-based document generation work. |

**Additional evidence to add:** screenshots of actual user stories/task cards if Trello or another board was used, plus screenshots showing the completed user journeys. Repository commits are useful evidence of code changes but do not replace visual evidence of the working product.

## 5. Reflection — 10%

### Reflection draft for personal review

Writing CareerCraft's features as user stories helps me view the platform from the perspective of the people who will use it. Instead of thinking only about pages or code files, I can describe the outcome a job seeker needs, such as saving a CV, selecting relevant GitHub projects or preparing a LinkedIn post.

Breaking stories into smaller tasks also makes the development work easier to reason about. For example, the GitHub portfolio workflow involves retrieving project information, showing project choices and allowing selected projects to be used in career materials. Treating this as one broad feature can hide the smaller steps and dependencies.

The repository history shows that some workflows were refined after their initial implementation. The GitHub project selection changes and the CV saving/template changes are examples of iterative development. A limitation in the current evidence is that the Git history does not show the original user interviews, formal story estimation or a Trello board. I should add those artefacts if I have them, rather than claim that they existed.

**Before submission:** personalise this reflection with one actual example of a user need you identified, how you decided on its acceptance criteria, and what changed after you tested or reviewed it.

## 6. Connection to the backlogs

The IDs in this document should be reused in the Product Backlog and Sprint Backlog. This makes it possible to trace a user need from its description, through prioritisation and task planning, to implementation evidence and reflection.

---
[← Portfolio home](./)
