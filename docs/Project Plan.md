# **CSIS 2430 — Project Plan (Plan \+ Trace)**

## **1\) Project Information**

* Course / Term: CSIS 2430  Fall Semester
* Project: Project 1 (Team2)  
* Team Name: Full Time Club  
* Start Date: 2026-09-19  
* Due Date: 2026-10-04  
* Checkpoint Date (mid-project): 2026-09-20

## **2\) Team & Roles (assigned for this project)**

Roles are assigned per project and rotate between projects.

| Team Member | Role (Implementation / Verification / Communications) | Primary Responsibilities (1–2 bullets) | Availability / Notes |
| :---- | :---- | :---- | :---- |
| Josh Painter | Implementation Lead | Owns core algorithm implementation; integrates modules; maintains main branch health. | Weeknights and Saturdays |
| Tiffani Roberson | Verification Lead | Creates test plan; edge cases; validates outputs; documents verification evidence. | Weeknights and Saturdays |
| Rafael Gutierrez | Communications Lead | Assembles report/video; ensures run instructions; tracks deliverables; merges documentation. | Weeknights and Saturdays |

## **3\) Repository & Access (Required for Projects 1–4)**

* Platform: GitHub  
* Repository URL: https://github.com/Zallzeron/Project\_1\_CS\_2430  
* Instructor invited as viewer by checkpoint?: Yes — invited 2026-09-19  
* Repo Structure Requirement (summary): Include /docs with UML/diagram, and design notes.

## **4\) Milestones (Timeline)**

| Milestone | Target Date | Owner | Definition of Done | Status (NS/IP/D) | Evidence Link / Pointer |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Repo set up \+ skeleton running | 2026-09-19 | Josh | Repo created;  | D | Github URL |
| Core implementation complete | 2026-10-04 | Josh | all four sorting algorithms implemented and producing results | D | /Project_1_CS_2430/src/projectone/ |
| Verification complete | 2026-10-04 | Josh/Rafael |  | D | /Project_1_CS_2430/src/projectone/ |
| Report/video draft complete | 2026-10-04 | Team | Team recording completed | D | Recording |
| Final integration \+ submission | 2026-10-04 | Team | Final reviews completed | D | GitHub repository |

## **5\) Task Backlog (Assignments \+ Status)**

| ID | Task | Owner | Due Date | Status (NS/IP/D) | Evidence Link / Pointer | Notes / Dependencies |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | Create repository and created main skeleton | Josh | 2026-09-20 | D | /Project_1_CS_2430/src/projectone/ | Repository created |
| 2 | Draft Design Notes for project  in /docs | Rafael | 2026-09-20 | D | /docs/proj_1_design-notes.md | Design notes completed |
| 3 | Draft UML/module diagram in /docs | Josh | 09-20-2026 | D | /docs/Project One.png | UML completed |
| 4 | Implement core data structures and parsing | Josh | 2026-10-04 | D | /Project_1_CS_2430/src/projectone/ | Sorting implementation completed |
| 5 | Define verification plan (tests \+ edge cases) | Tiffani | 2026-10-04 | D |  |  |
| 6 | Implement edge-case tests \+ expected outputs | Team | 2026-10-04 | D | docs/test-results.md |  |
| 8 | Checkpoint package: update plan \+ docs \+ invite verification | Team | 2026-09-20 | D | /docs |  |
| 9 | Report draft (problem/design/verification/results) | Team | 2026-10-04 | D | Final Report |  |
| 10 | Final polish: run instructions \+ release tag | Team | 2026-10-04 | D | README.md | README completed |

## **6\) Verification Plan**

* Correctness checks / tests to run

* Unit tests for core functions (parsing, core algorithm steps).  
* Golden-file tests: compare outputs to expected results on provided sample inputs.  
* Negative tests: invalid inputs produce clear error messages.

* Edge cases to verify

* Empty/near-empty input (minimum size).  
* Maximum size input within assignment constraints.  
* Duplicate or conflicting entries (as applicable to the project spec).

* Expected vs. actual outputs (where applicable)

* Document expected outputs for at least 3 representative test cases in docs/test-results.md.  
* Include screenshots or terminal output snippets if tooling is minimal.

* Performance checks (if required by the project)

* Run on increasing input sizes and record runtime (basic timing).  
* Confirm no unnecessary O(n^2) loops on hot paths where avoidable.

## **7\) Risks / Blockers**

| Risk / Blocker | Impact | Mitigation Plan | Owner | Status |
| :---- | :---- | :---- | :---- | :---- |
| |  |  |  |  |
|  |  |  |  | |
|  | | |  |  |

## **8\) Update Log**

| Date | Summary of Update (what changed / what completed) | Blockers / Resolutions | Link(s) |
| :---- | :---- | :---- | :---- |
| 2026-09-19 | Repo created; | None | https://github.com/Zallzeron/Project\_1\_CS\_2430 |
| 2026-09-19 | Main documentation, artifacts and skeleton created and uploaded |  | /docs |
| 2026-09-20 | Small updates on Project Plan and project documentation | | /docs |
| 2026-09-24 | Completed Part One of the project implementation | | /src/projectone/ |
| 2026-09-29 | Added Shaker Sort and implemented its exchange counter | | /src/projectone/Shaker.java |
| 2026-09-30 | Updated sorting algorithms and began implementing the Driver | | /src/projectone/ |
| 2026-10-01 | Completed the main project implementation | | /src/projectone/ |
| 2026-10-04 | Reviewed and cleaned up sorting implementations | | /src/projectone/ |
