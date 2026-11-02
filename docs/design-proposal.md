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

**1.4 Goals & Non-Goals**

- **Goals (in-scope):**
  - Create a clickable Figma prototype for a mobile manga/manhwa reading application.
  - Allow users to browse through series and chapters.
  - Demonstrate a basic comic upload interface.
  - Design a simple and intuitive navigation system.
  - Show example filtering and reading progress interfaces using sample data.

- **Non-Goals (out-of-scope):**
  - Fully functional genre and tag filtering.
  - Internet connectivity features or external APIs.
  - Long-term storage of user data, including logins and saved reading progress.
  - A fully developed mobile application.
  - A backend or database.
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
- **US-4:**
  - **Acceptance Criterion 1:** Given that I'm entering the app, when I go into my series, then I can easily find the chapter I left off.
  - **Acceptance Criterion 2:** Given that I'm reading multiple series at once, when I'm switching between them, then my reading progress for both should be saved.
- **US-5:**
  - **Acceptance Criterion 1:** Given that I have a new chapter to upload, when I go through the uploading process, then the process should be quick and intuitive.
  - **Acceptance Criterion 2:** Given that I am posting a new work, when I upload it, then I can add tags to make my series more discoverable.
- **US-6:**
  - **Acceptance Criterion 1:** Given that I'm following multiple series, when I open my bookshelf, then I can see all the series I have saved.
  - **Acceptance Criterion 2:** Given that I select a series from my bookshelf, when I open it, then I can view its chapters.

**2.3 Assumptions & Constraints**  
- _Tech limits, time, skills, devices, data, privacy._
- No user information will be collected or stored.
- Due to all development being on Figma, as well as time constraints, only requirements marked as M or S will be actively developed.
- Due to all development being on Figma, as well as the nature of this project, no comics will be added to this prototype.
- Users will be using a mobile device to navigate this product.
- Due to a lack of mobile development experience, this will not be a real mobile app. 
---


## 3) Figma Design

### 3.1 Figma Links

- **Design File:** [The Archivists - Figma Design](https://www.figma.com/design/HYUZvaq8RQHxSgLbzuAs99/The-Archivists?node-id=0-1&p=f)
- **Prototype (Present Mode):** [The Archivists - Figma Prototype](https://www.figma.com/proto/HYUZvaq8RQHxSgLbzuAs99/The-Archivists?node-id=4-246&t=bh6uxvd96HLrXGSq-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)
- **Design System / Components:** We use basic colours, buttons, and layouts consistently throughout the prototype.

### 3.2 Screen Inventory

Our Figma prototype contains six mobile screens designed to demonstrate the main features and layout of our manga/manhwa reading application.

| Screen ID | Name | Purpose | Status |
|---|---|---|---|
| S-1 | Home | Allows users to choose between the Reader and Creator sections of the application. | Draft |
| S-2 | Browse Series | Displays available manga/manhwa series with titles, genres, and chapter counts. | Draft |
| S-3 | Series Details | Shows information about a selected series, including its description and available chapters. | Draft |
| S-4 | Chapter Reader | Demonstrates the reading interface with sample comic panels and chapter navigation buttons. | Draft |
| S-5 | Creator Portal | Displays a basic form for entering comic information and uploading chapters. | Draft |
| S-6 | My Library | Shows saved series and recently read chapters using sample data. | Draft |

All six screens can be viewed in our [Figma Design File](https://www.figma.com/design/HYUZvaq8RQHxSgLbzuAs99/The-Archivists?node-id=0-1&p=f).

### 3.3 User Flows

The prototype is designed around three simple user flows to demonstrate how readers and creators would navigate the application.

**Flow 1: Browsing and Reading a Series**

1. User starts at the Home screen.
2. User selects "Browse Series" to enter the Reader Portal.
3. User chooses a series from the available list.
4. User views the series details and chapter list.
5. User selects "Start Reading" to open the Chapter Reader.

**Success Criteria:** The user can find a series, view its available chapters, and reach the reading screen.

**Flow 2: Accessing the Library**

1. User selects the Library tab from the bottom navigation.
2. User views the Continue Reading and Saved Series sections.
3. User identifies previously saved series and their last-read chapter.

**Success Criteria:** The user can locate saved series and identify their previous reading progress.

**Flow 3: Creator Uploading**

1. User starts at the Home screen.
2. User selects "Creator Portal."
3. User views the form for comic title, genre, description, and chapter information.
4. User views the comic file placeholder and Submit button.

**Success Criteria:** The user understands how comic information would be entered for uploading.

These flows describe the intended navigation of the application. Since this is a Figma prototype, actual file uploads, saved reading progress, and database functionality are outside the project's scope.

### 3.4 Accessibility in Design

Our team considered basic accessibility and usability principles when designing the prototype.

- **Colour Contrast:** Dark text on light backgrounds helps make content easier to read. Muted blue is used for primary buttons and selected navigation items.
- **Consistent Navigation:** A bottom navigation bar containing Home, Browse, Library, and Upload appears throughout the prototype.
- **Clear Labels:** Buttons and navigation items use simple labels such as "Browse Series," "Start Reading," "Creator Portal," and "Submit."
- **Readable Text:** Headings, descriptions, and button labels use consistent text sizes to distinguish different types of information.
- **Error Messaging:** The creator upload form includes labelled fields. Validation and error messages may be added in future revisions.
- **Keyboard Focus Order:** Keyboard navigation has not yet been implemented or tested in the Figma prototype.

### 3.5 Figma Screenshots

The following screenshots show the six main screens of our Figma prototype.

**Home Screen**

![Home Screen](../resources/design-document/home.png)

**Browse Series**

![Browse Series](../resources/design-document/browse.png)

**Series Details**

![Series Details](../resources/design-document/series-details.png)

**Chapter Reader**

![Chapter Reader](../resources/design-document/chapter-reader.png)

**Creator Portal**

![Creator Portal](../resources/design-document/creator-portal.png)

**My Library**

![My Library](../resources/design-document/library.png)


---


## 4) Information Architecture & Data

### 4.1 Navigation Structure

Our application is organized into six main screens. Users can navigate between the Reader and Creator sections from the Home screen. A bottom navigation bar provides access to Home, Browse, Library, and Upload.

The intended navigation structure is:

Home
- Browse Series
  - Series Details
    - Chapter Reader
- Creator Portal
- My Library
  - Series Details
    - Chapter Reader

The Browse screen allows users to explore available manga and manhwa. Selecting a series leads to its details page, where users can view chapters and begin reading.

The Library screen displays saved series and reading progress, while the Creator Portal provides a basic form for submitting comic information.

The navigation structure represents the intended user experience. Some interactions are demonstrated visually and may not be fully connected in the Figma prototype.

### 4.2 Data Structure

Our prototype uses sample information to demonstrate how manga/manhwa series and chapters would be displayed.

| Data | Information Stored | Purpose |
|---|---|---|
| Series | Title, genre, description, chapter count, cover image | Displays information about each manga/manhwa series. |
| Chapter | Chapter number, chapter title, comic panels | Organizes the reading content for a series. |
| Library | Saved series, last-read chapter | Demonstrates how users could access saved content and continue reading. |
| Creator Submission | Comic title, genre, description, chapter information | Demonstrates the information creators would enter when uploading a comic. |

All information shown in the Figma prototype is sample data. No actual database, user account system, or file storage has been implemented.

### 4.3 Sample Data

The prototype includes a small selection of fictional manga/manhwa series to demonstrate the browsing and reading experience.

Sample information includes:
- Series titles and genres displayed on the Browse screen.
- Series descriptions and chapter lists displayed on the Series Details screen.
- Placeholder comic panels displayed in the Chapter Reader.
- Saved series and reading progress displayed in My Library.
- Example input fields displayed in the Creator Portal.

These examples help demonstrate how the application would organize content without requiring real manga/manhwa uploads or a database.

### 4.4 Data Privacy

The current Figma prototype does not collect or store personal user information.

If the application were developed further, it would need to consider how user accounts, saved series, reading history, and creator submissions are stored and protected.

For the current project, all displayed data is fictional or placeholder content.


---


## 5) UI Specifications

### 5.1 Colour Scheme

Our application uses a simple colour scheme with light backgrounds, dark text, and blue buttons to maintain a clean and consistent appearance.

| Element | Colour | Hex Code |
|---|---|---|
| Background | Light Grey | `#F5F6F8` |
| Cards and Input Fields | White | `#FFFFFF` |
| Buttons | Muted Blue | `#4F6D9A` |
| Main Text | Dark Blue-Grey | `#273244` |

### 5.2 Typography

The prototype uses readable text with larger, bold headings for screen titles and section names. Smaller text is used for descriptions, genres, and chapter information. Button labels are kept short and clear.

### 5.3 Buttons and Navigation

The application uses buttons for actions such as browsing series, starting chapters, and submitting comic information.

A bottom navigation bar provides access to Home, Browse, Library, and Upload. Back buttons are also included on screens where users may need to return to a previous page.

### 5.4 Layout and Components

The prototype uses a consistent mobile layout with cards for series information, input fields for creator submissions, and placeholders for comic covers and panels.

Spacing and positioning are kept consistent across the six screens to make the application easy to navigate.

### 5.5 UI States and Feedback

Buttons and navigation items use simple visual styles. Blue highlights are used for selected navigation options.

Advanced features such as form validation, error messages, and upload confirmation are not implemented in the current Figma prototype.


---


## 6) Interaction Design

### 6.1 Main Interactions

The prototype demonstrates how readers and creators would interact with the application.

| Interaction | Expected Behaviour |
|---|---|
| Browse Series | Opens the Browse screen to explore available manga/manhwa. |
| Select Series | Opens the Series Details screen with a description and chapter list. |
| Start Reading | Opens the Chapter Reader to view comic panels. |
| Previous/Next Chapter | Represents moving between chapters. |
| Library | Displays saved series and reading progress. |
| Creator Portal | Displays a form for entering comic and chapter information. |

### 6.2 Navigation

A bottom navigation bar allows users to access Home, Browse, Library, and Upload. Back buttons are included on the Series Details and Chapter Reader screens.

The design aims to make navigation simple and consistent across all six screens.

### 6.3 Forms and Feedback

The Creator Portal includes fields for entering comic information and a Submit button. The Browse screen also includes a search bar.

These elements demonstrate the intended functionality but do not currently process user input. Features such as search results, form validation, and upload confirmations may be added in future development.

### 6.4 Prototype Limitations

The Figma prototype focuses on demonstrating screen layouts and user navigation. Features such as actual comic uploads, saved reading progress, and database storage are not implemented.


---


## 7) System Overview

### 7.1 System Architecture

The Archivists is a mobile application prototype designed in Figma. It demonstrates how readers can browse manga/manhwa, read chapters, and manage their library, while creators can submit comic information.

The prototype consists of six screens that represent the main features of the application. It focuses on interface design and navigation rather than backend functionality.

### 7.2 Tools and Technologies

| Tool | Purpose |
|---|---|
| Figma | Designing the application screens and demonstrating user interactions. |
| GitHub | Managing project files, documentation, and team collaboration. |
| GitHub Wiki | Organizing project information and progress updates. |

### 7.3 Data and Storage

The prototype uses fictional series information and placeholder images to demonstrate how content would appear.

No database, server, or user authentication system is implemented. Features such as saving reading progress, searching for comics, and uploading chapters are represented through the interface.

### 7.4 Future Development

If the project were developed into a functional application, additional components would be required for storing comic information, managing user accounts, saving reading progress, and processing creator uploads.

For the current project, our focus is on creating a clear and understandable prototype.


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
