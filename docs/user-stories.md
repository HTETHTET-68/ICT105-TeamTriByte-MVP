# Lab 04 - User Stories and Acceptance Criteria

## User Story Format

> **As a** [user role], **I want to** [goal/action], **so that** [benefit/value].

---

## User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|---|---|---|---|---|---|---|
| US-01 | Incoming International Student | As an incoming international student, I want to view dormitory and cafeteria listings in one platform, so that I can explore campus living options before I arrive in Thailand. | FR-01 | Must | Given the user opens HallPass, when they access the homepage, then dormitory and cafeteria listings are displayed with names, photos, and brief descriptions. | Homepage screenshot |
| US-02 | First-Year Student (Pre-Arrival) | As a first-year student who hasn't moved in yet, I want to read dormitory reviews written by current residents, so that I can choose accommodation that suits my lifestyle and budget. | FR-02 | Must | Given a dormitory listing is selected, when the detail page opens, then student-written reviews, star ratings, and an average score are displayed. | Dorm review page screenshot |
| US-03 | Student Living On Campus | As a student living on campus, I want to read cafeteria reviews and food recommendations, so that I can discover where to eat without wasting time and money on bad meals. | FR-03 | Must | Given a cafeteria is selected, when the detail page opens, then food reviews, ratings, and recommended dishes are displayed. | Cafeteria review page screenshot |
| US-04 | Student (Any) | As a student, I want to search for specific dormitories or cafeterias by name or keyword, so that I can quickly find information about a place I already have in mind. | FR-04 | Must | Given a search keyword is entered, when the search is submitted, then a list of matching dormitories and/or cafeterias is displayed. | Search results screenshot |
| US-05 | Student Comparing Options | As a student comparing multiple housing options, I want to filter dormitories by criteria such as price range, distance, or room type, so that I can narrow down choices that fit my needs. | FR-05 | Must | Given the filter panel is opened, when one or more filters are applied, then only listings matching the selected criteria are shown. | Filter UI demo |
| US-06 | Exchange Student (New to Campus) | As an exchange student arriving mid-semester, I want to read campus survival guides covering daily life, transport, and local tips, so that I can adapt quickly without relying entirely on word-of-mouth. | FR-06 | Should | Given the Survival Guide section is accessed, when a topic is selected, then a structured guide with practical tips is displayed. | Guide page screenshot |
| US-07 | Student Quickly Scanning Listings | As a student scanning multiple listings, I want to see an average rating score on each dorm and cafeteria card, so that I can compare quality at a glance without opening every page. | FR-07 | Must | Given the listings page is displayed, when browsing, then each card shows a visible average star rating. | Listings page screenshot |
| US-08 | Verified Student Contributor | As a student who has lived in a dorm or eaten at a cafeteria, I want to submit my own review and rating, so that I can help future students make better-informed decisions. | FR-08 | Could | Given the review submission form is completed and submitted, when the form is sent, then the review is saved and appears on the relevant listing page. | Review submission demo |
| US-09 | Returning Student (Sophomore/Junior) | As a returning student planning housing for next semester, I want to bookmark dorms and cafeterias I'm interested in, so that I can easily revisit and compare my shortlisted options later. | FR-09 | Could | Given a user clicks the bookmark icon on a listing, when they navigate to their saved items page, then all bookmarked listings appear. | Saved items screenshot |

---

## Acceptance Criteria Checklist

A good acceptance criterion should be:

- **Testable** — can be verified with a clear pass/fail outcome
- **Observable** — visible and demonstrable in the final prototype
- **Connected to a requirement** — maps to a functional requirement (FR-XX)
- **Connected to user evidence** — supported by a screenshot or demo
- **Not too vague** — specific enough that two people would agree on the result

---

## Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
|---|---|---|
| US-10 | Real-time peer chat system is outside MVP scope | Add after the core review and community system is stable |
| US-11 | AI-powered dorm/cafeteria recommendation engine requires sufficient review data to train on | Add after a meaningful volume of student reviews has been collected |
| US-12 | Booking or reservation system for dorm rooms is not part of the MVP | Add in a future expansion phase once the platform has an established user base |
