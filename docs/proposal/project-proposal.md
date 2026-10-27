
# Team Project Proposal

**Course:** CSSD1161 — Communication & Teamwork in Software Development

**Team Name:** The Archivists

**Project Title:** Manga/Manhwa Reading Application

**Team Members:**
- Prahalad Prasanna — prasprah@my.yorku.ca
- Alyssa Brown — alyb08@my.yorku.ca
- Sylvia Ip — sylviaip@my.yorku.ca
- Iven Yu — iven16@my.yorku.ca

---

## 1. Executive Summary

Our team, The Archivists, is developing a manga/manhwa reading application focused on making the reading experience more convenient and efficient. Many existing reading platforms have issues such as inaccurate genre categorization, inefficient use of screen space, and difficulty returning to previously read chapters. Our goal is to address these problems by creating an intuitive interface that allows users to browse multiple series, filter through different genres and tags, and keep track of their reading progress. The application will include a list-style interface displaying information such as the title, author, genre, and cover image of each series. We also plan to include a personal bookshelf and a recent reads feature that allows users to return to where they left off. Our main target audience consists of manga/manhwa readers who follow multiple series, although we also want to consider the needs of content creators who upload their work. By the end of the course, our goal is to deliver a prototype demonstrating the main browsing, filtering, and reading progress features.

---

## 2. Problem Space & Proto-Persona

### 2.1 Proto-Persona

**Name:** General Manga/Manhwa Reader

**Age:** Not specified

**Role/Context:** Manga/Manhwa Reader

**Goals:**
- Quickly find manga/manhwa series that match their interests.
- Browse through multiple series at once without inefficient navigation.
- Easily return to the chapter where they previously left off.
- Keep track of currently reading and completed series.
- Read conveniently on mobile devices.

**Frustrations/Pain Points:**
- Heavy monetization on some reading platforms.
- Inaccurate genre categorization and lack of advanced filters.
- Unable to browse through many different series at once due to inefficient use of space.
- Restrictive posting requirements for creators.
- Difficulty finding chapters where the user left off.

**Environment/Constraints:**
- Lack of adaptability to different screen sizes, especially on mobile devices.
- Large cover panels and unresponsive UI prevent smooth browsing.
- Readers may have limited time to read and need to return to their previous chapters quickly.
- Users may not always have access to a stable internet connection.

### 2.2 Problem Statement

How might we help the reader quickly find their preferred content in an efficient manner despite an unintuitive UI and difficulty returning to previous content?

Our project focuses on improving the browsing and reading experience by providing a more organized interface, advanced filtering options, and a way for users to easily continue reading where they left off.

### 2.3 Creative Problem Solving (CPS)

#### Clarify — Key Facts and Assumptions

Our team identified three main problems that affect the manga/manhwa reading experience.

**1. Inaccurate genre categorization/Lack of advanced filters**

- Books are sometimes incorrectly categorized under different genre sections.
- Genres provided are extremely broad and do not help narrow down search results.
- A lack of advanced filtering makes it difficult for users to find specific types of series.

**2. Unable to browse through many different series at once due to inefficient use of space**

- Lack of adaptability to different screen sizes, especially on mobile.
- Large cover panels and unresponsive UI prevent smooth browsing.
- Inefficient layouts make browsing multiple series more difficult than necessary.

**3. Difficult to find chapters where the user left off**

- When opening a new book or series, the most recent chapters may appear first, making it difficult to get to the beginning.
- Users may have difficulty returning to the chapter where they previously stopped reading.
- Readers following multiple series need a convenient way to keep track of their progress.

We believe addressing these problems will make the application more convenient for readers and improve the overall user experience.

#### Ideate — Candidate Approaches

During Lab 2, our team came up with four main ideas for the application.

**Idea A: List-Style UI**

A list-style interface containing the title, author, genre, and cover picture of each series. This would be combined with a personal bookshelf for current reads and a pop-up for most recent reads that opens to the page where the user left off.

**Idea B: Advanced Filters**

Advanced filtering options including genre, keywords, status (completed/incomplete), tropes, similar series, and a larger selection of filterable tags.

**Idea C: Reading Progress Section**

A separate section on the home page that allows users to pick up where they left off. This would display details such as current progress, page number, and next/previous chapter.

**Idea D: Offline Reading**

An offline download option that allows users to access reading material without requiring a constant internet connection.

Following our prototype testing, we also identified two additional improvements worth considering:

**Idea E: Clearer Navigation**

Improve settings labels and add recognizable icons to buttons to make the interface more intuitive.

**Idea F: Organized Filtering Categories**

Organize different tags into categories so users can browse and find filtering options more easily.

#### Converge — Selected Solution

Our team selected a combination of Idea A and Idea B as the main concept for the project.

The selected concept is to create an intuitive UI with list options that allow users to view more series at once, as well as options to filter by various tags. The application will separate different sections clearly, allowing users to have an online home library experience.

We chose this concept because it is practical to prototype and makes it more convenient for users to read whatever they want, whenever they want.

Other ideas, such as offline downloads and additional functionality, may be considered later depending on the time and resources available.

---

## 3. Validation with Mini-Personas

Our team developed two mini-personas during Lab 2 to better understand the needs of readers and content creators.

### Mini-Persona A: Jordan — Frequent Reader

**Role/Context:** Frequent reader

**Goals:**
- Able to read on the go, does not have time to read continuously for long periods of time.
- Switch between multiple series and retain reading progress.
- Discover new series, especially those similar to what he already enjoys.
- Avoid seeing series he does not like.

**Pain Points:**
- Unable to get back to the chapter where he left off.
- Too much time spent navigating UI, losing reading time.
- Cannot find new series he is interested in reading.

**Quote:**

"I don't have a lot of time in the day to read, so I want to make the most of it."

**Validation:**

Jordan's needs support our initial idea of creating a more efficient browsing experience. Since he has limited time to read and follows multiple series, features such as a personal bookshelf and recent reads section would make it easier for him to return to previous chapters. His interest in discovering similar series also supports the need for improved filtering and content discovery.

### Mini-Persona B: Alexia — Content Creator

**Role/Context:** Content creator who wants to upload work and reach interested readers.

**Goals:**
- Quick and concise creator upload experience with low upload constraints.
- Able to reach the target audience.

**Pain Points:**
- Strict constraints on upload quality, image size, and sectioning.
- Improper filtering and monetized or popularity-based promotion lead to books not being found by readers.

**Quote:**

"I want to make sure that my works are found by people who enjoy them."

**Validation:**

Alexia's needs show that the application should also consider the experience of content creators. An intuitive uploading process and accurate categorization would make it easier for creators to publish their work and reach readers who are interested in it. While our main focus is improving the reading experience, these requirements help us consider how the application could support both readers and creators.

### Prototype Testing Feedback

During Lab 2, our team conducted a peer test to evaluate the initial prototype.

**Task Given to Peer:**

Search, then open and read a chapter of a series.

**Observed Confusion Points:**

The participant had difficulty browsing through different tags.

**What Was Easy:**

Getting back to their previous series and finding new series.

**What Was Confusing:**

Settings inside reader mode were not descriptive enough.

**Three Planned Changes:**
- Make labels for settings clearer.
- Add icons for each button to make navigation more intuitive.
- Add categories for different tags to make them easier to find.

This feedback helped us identify areas of the interface that need further refinement. Our next goal is to improve these aspects while keeping the application simple and easy to navigate.

---

## 4. Users, Requirements & Acceptance Criteria

**Primary User:** Manga/Manhwa Reader

**Secondary Stakeholders:** Content creators who upload and share their work.

### 4.1 User Stories (EPIC → Stories)

#### EPIC 1: Content Discovery

Allow users to discover new series and search for content matching their preferences.

**User Story 1:**

As someone who is interested in trying out new series, I want to know what other people think is the best so that I can read good stories.

**User Story 2:**

As someone who wants to find a specific series, I want to be able to search with very specific and niche filters to find my preferred media.

#### EPIC 2: Reading Experience and Progress

Allow users to follow multiple series while keeping track of their reading progress and new chapter releases.

**User Story 3:**

As someone who doesn't have a lot of time to read, I want to be able to quickly jump back in where I left off.

**User Story 4:**

As someone who is actively following a series, I want to know when a new chapter is out.

#### EPIC 3: Content Uploading

Allow creators to upload their work and make it easier for readers to discover it.

**User Story 5:**

As someone who is interested in uploading my work onto this site, I want people to easily find my work.

### 4.2 Acceptance Criteria (Given/When/Then)

#### Story 1: Content Discovery

- **Acceptance Criterion 1:** Given that I'm looking for a new series, when I search for most popular, then series which are both recently popular and all-time popular appear.
- **Acceptance Criterion 2:** Given that I've enjoyed a series, when I want to support the author, then I can like or support the series.

#### Story 2: Advanced Filtering

- **Acceptance Criterion 1:** Given that I'm looking for a specific series, when I search by "Comedy" and "Completed", then I should be able to find series that are of the comedy genre and are a completed series.
- **Acceptance Criterion 2:** Given that I'm searching for a new series, when I filter by a tag, then there should not be any mislabeled titles.

#### Story 3: Reading Progress

- **Acceptance Criterion 1:** Given that I'm entering the app, when I go into my series, then I can easily find the chapter I left off.
- **Acceptance Criterion 2:** Given that I'm reading multiple series at once, when I'm switching between them, then my reading progress for both should be saved.

#### Story 4: New Chapter Updates

- **Acceptance Criterion 1:** Given that when a series I'm interested in uploads a new chapter, then I should get a notification about it.
- **Acceptance Criterion 2:** Given that I'm interested in other works by the same author, when they upload a new work, then I should recommend it.

#### Story 5: Creator Uploading

- **Acceptance Criterion 1:** Given that I have a new chapter to upload, when I go through the uploading process, then the process should be quick and intuitive.
- **Acceptance Criterion 2:** Given that I am posting a new work, when I upload it, then I can add tags to make my series more discoverable.

### 4.3 Non-Functional Requirements

#### Accessibility and Usability

- The product MUST be simple because a simple user experience leads to a larger user base and better ability for feedback in the future.
- The interface should adapt to different screen sizes, especially mobile devices.
- Navigation elements, buttons, and settings should be clear and easy to understand.

#### Performance

- The product MUST load within 0.5 seconds with a good connection to prevent user confusion on what to do next.
- The product MUST have an effective search engine because better searching leads to users finding things more easily.

#### Reliability and Content Quality

- The product SHOULD include a reader home library to allow the reader to view their recent reads, completed reads, and the books they last left.
- The product SHOULD have quality moderation for uploaded content because lower-quality content will result in a worse experience.
- The product SHOULD allow creators to easily upload content onto the app as long as they follow the specific guidelines, allowing new content to be added without inappropriate material.

#### Privacy and Security

To be determined based on the final application design and any user information the application will need to store.

### 4.4 Assumptions & Dependencies

- The application will primarily focus on mobile users.
- Figma will be used for prototyping and refining the application interface.
- Java is the planned development language for the mobile application.
- GitHub will be used to manage project documentation, collaboration, and development.
- The team will need to determine which mobile platforms the application will support.
- The implementation of more advanced features will depend on the project's available time and resources.
- The application design will continue to be refined based on prototype testing and user feedback.

---

## 5. Software Development Approach

**Approach:**

**Explain Why:**

**Preferred Technologies/Tools:**

---

## 6. Communication Plan

**Stand-ups:**

**Weekly Lab Brief:**

**Channels of Communication:**

**Conflict Resolution:**

---

## 7. Ethics, Privacy & AI Use

**Ethics:**

**Privacy:**

**AI Use:**
