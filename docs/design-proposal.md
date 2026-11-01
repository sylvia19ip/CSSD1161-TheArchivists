# Team Design Document (with Figma)

**Course:** CSSD1161 — Communication & Teamwork in Software Development  
**Team:** The Archivists • **Repo:** _GitHub URL_ • **Term:** Fall 2026
**Version:** 0.1 • **Last Updated:** 2026-11-01

---

## 0) Revision History
| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 0.1 | 2026-11-01 | Sylvia Ip | Initial draft |

---

## 1) Project Overview
**1.1 Problem Statement**  
Visual comic/manga/manhua/manhwa readers lack a centralized platform to both read and manage their series. Existing options, such as WEBTOON and other comic reading sites, suffer from unintuitive UI, heavy monetization, and large amounts of advertising. 

**1.2 Users & Context**  
- Primary users: Readers and creators of comics
- User needs:
  - Allow users to discover new series and search for content matching their preferences.
  - Allow users to filter for specific genres
  - Allow users to track and save their reading progress
- Context & constraints: 
  - Due to being a comic display site, support for vision-impaired users is limited. A space for alt text for every image will be provided.
  - The product will be served for mobile users.
  - Depending on how the media is licensed, users may either require internet connectivity to use the product or be able to download the media onto their own devices

**1.3 Value Proposition**  
Many existing reading platforms have issues such as inaccurate genre categorization, inefficient use of screen space, and difficulty returning to previously read chapters. Our goal is to address these problems by creating an intuitive interface that allows users to browse multiple series, filter through different genres and tags, and keep track of their reading progress. The application will include a list-style interface displaying information such as the title, author, genre, and cover image of each series. We also plan to include a personal bookshelf and a recent reads feature that allows users to return to where they left off. Our main target audience consists of manga/manhwa readers who follow multiple series. We also want to consider the needs of content creators who upload their work.

**1.4 Goals & Non‑Goals**  
- **Goals (in-scope):** 
  - Be able to browse through chapters
  - Be able to upload comics to read
- **Non‑Goals (out-of-scope):**
  - Filtering of tags
  - Internet connectivity features
  - Long-term storage of data (ex. logins, saving progress)
---

## 2) Requirements
**2.1 User Stories (MoSCoW priority)**  
_List at least 6; include ID and priority._
| ID | As a… | I want… | So that… | Priority (M/S/C/W) |
|---|---|---|---|---|
| US-1 |person who wants to try new series|to know what other people enjoy|I can read high quality stories | C|
| US-2 |person who wants to find a specific series|to search with both title and tags|I can find my preferred media|S|
| US-3 |person who is reading a series in progress|to be notified of new chapter releases| I can stay caught up on the stories I enjoy|C|
| US-4 |person who lacks a lot of free time|to be able to quickly return from where I left off|I can make the best use of my spare time|M|
| US-5 |person who is interested in uploading my work|people to be able to discover my work|so that more people can read it|M|
| US-6 |person who is following multiple series|to be able to save all of them|I don't lose track of what I'm reading|M|

**2.2 Acceptance Criteria (Given/When/Then)**  
_Trace to user stories._
- **US-1:**  
  - **Acceptance Criterion 1:** Given that I'm looking for a new series, when I search for most popular, then series which are both recently popular and all-time popular appear.
  - **Acceptance Criterion 2:** Given that I've enjoyed a series, when I want to support the author, then I can like or support the series.
- **US-2**
  - **Acceptance Criterion 1:** Given that I'm looking for a specific series, when I search by "Comedy" and "Completed", then I should be able to find series that are of the comedy genre and are a completed series.
  - **Acceptance Criterion 2:** Given that I'm searching for a new series, when I filter by a tag, then there should not be any mislabeled titles.
- **US-3**
  - **Acceptance Criterion 1:** Given that when a series I'm interested in uploads a new chapter, then I should get a notification about it.
  - **Acceptance Criterion 2:** Given that I'm interested in other works by the same author, when they upload a new work, then I should recommend it.

**2.3 Assumptions & Constraints**  
- _Tech limits, time, skills, devices, data, privacy._
- No user information will be collected or stored.
- Due to all development being on Figma, as well as time constraints, only requirements marked as M or S will be actively developed.
- Due to all development being on Figma, as well as the nature of this project, no comics will be added to this prototype.
- Users will be using a mobile device to navigate this product.
- Due to a lack of mobile development experience, this will not be a real mobile app. 
---

## 3) Figma Design
> Provide **view-only Figma links** and 2–3 **exported screenshots** per key screen.

**3.1 Figma Links**  
- **Design file:** _https://www.figma.com/file/…_  
- **Prototype (Present mode):** _https://www.figma.com/proto/…_  
- **Design System / Components (optional):** _https://www.figma.com/file/…_

**3.2 Screen Inventory**
| Screen ID | Name | Purpose | Status (Draft/Final) | Link |
|---|---|---|---|---|
| S-1 |  |  |  |  |
| S-2 |  |  |  |  |

**3.3 User Flows**  
_Attach Figma flow(s) and list success criteria for each flow._

**3.4 Accessibility in Design**  
- Color contrast (target WCAG 2.1 AA)  
- Keyboard focus order indicated  
- Labels, hints, and error messaging specified

> **Paste 2–3 key Figma screenshots below (export PNGs)**
![Home screen](./imgs/home.png)
![Task flow](./imgs/flow.png)

---

## 4) Information Architecture & Data
**4.1 Sitemap / Navigation**  
_Draw or link a simple diagram (can be Figma)._

**4.2 Content / Data Model**  
| Entity | Key Fields | Notes |
|---|---|---|
| User | id, name, email |  |
| Item | id, title, tags |  |

---

## 5) UI Specifications
**5.1 Layouts per Screen**  
_For each screen, specify: layout, spacing, breakpoints, and annotations._

**5.2 Style Guide**
- **Colors:** _Hex codes with roles (Primary, Background, Text, Error, etc.)_
- **Typography:** _Heading sizes, body text, line-height_
- **Iconography:** _Set used and sizes_
- **Components:** _Buttons, inputs, cards, alerts (states: default/hover/focus/disabled/error)_

---

## 6) Interaction Design
**6.1 States & Behaviours**  
- Loading, empty, success, error states with visuals and messaging  
- Keyboard interactions and focus management

**6.2 Microcopy**  
_Errors, empty states, tooltips, button labels._

---

## 7) System Overview (Lightweight)
**7.1 Architecture (if applicable)**  
- Client (framework), optional server/API, storage (if any)  
- Diagram (image or ASCII)

**7.2 External Services / APIs (if any)**  
| Service | Purpose | Auth | Notes |
|---|---|---|---|

---

## 8) GitHub Workflow (Course Conventions)
- **Repository:** _URL_ • **Default Branch:** `main`  
- **Branching:** `feature/xyz-123`, small PRs (< 200 lines), request review  
- **Issues & Milestones:** link each PR to an issue; use labels (feature/bug/docs)  
- **PR Checklist:** lint passes, screenshots (if UI), tests (if any), clear description

---

## 9) Testing Plan
**9.1 Usability Checks (3 participants)**  
- Short task script, success criteria, and observations template.

**9.2 Functional Checks (Happy/Edge Paths)**  
| Case ID | Story | Steps | Expected |
|---|---|---|---|
| TC-1 | US-1 |  |  |

---

## 10) Accessibility & Inclusion
- Keyboard-only use possible on key flows  
- Alt text for images; form labels; error messaging helps recovery  
- Language plain and inclusive (grade ~8–10)

---

## 11) Risks & Mitigations
| Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|
|  |  |  |  |

---

## 12) Milestones & Schedule
| Milestone | Date | Deliverable |
|---|---|---|
| Design Freeze |  | Figma screens & flows |
| MVP Build |  |  |
| Demo |  |  |

---

## 13) Submission Checklist
- [ ] Figma links (design + prototype)  
- [ ] 2–3 screenshots per key screen  
- [ ] User stories + acceptance criteria  
- [ ] Screen inventory & flows  
- [ ] Style guide & interaction states  
- [ ] GitHub repo URL and PR/Issue links  
- [ ] Usability + functional check results  
- [ ] Accessibility notes  
- [ ] Risks & timeline

---

## Appendix
**A) Glossary**  
**B) AI‑Assistance Disclosure** (_tools used and how_)  
**C) References**
