# Project Overview
## RentSell — Property Sales and Rental Management System

---

## Document Information

| Field | Detail |
|---|---|
| Project Title | RentSell — Property Sales and Rental Management System |
| Document Type | Project Overview (Description, Objectives, Scope) |
| Author | Abdul Wares Momand — Product Owner |
| Team Size | 4 members (Product Owner, Scrum Master, Developer) |
| Total Sprints | 5 sprints × 4 days = 20 days |
| Version | 1.0 |
| Last Updated | 8/10/2026 |
| Repository | https://github.com/AbdulWaresmomand/hello_world/new/main |

---

## 1. Project Description

**RentSell** is a web-based Property Sales and Rental Management System 
that allows users to buy, sell, rent, and manage properties and 
belongings — including **homes, rooms, cars, bikes, and other items**.

The system connects **owners and sellers** with **buyers and renters** 
in a single digital marketplace. Users can create accounts, publish 
listings with photos and details, browse and search available items, 
filter by category and purpose (sale or rent), send inquiries, save 
favorites, and manage their own listings. Administrators can review 
reported listings and moderate content to keep the marketplace safe 
and trustworthy.

The project is delivered using the **Scrum framework** across **5 
four-day sprints** (20 days total), with a **3-person team**: one 
Product Owner, one Scrum Master, and one Developer.

The platform replaces manual, paper-based dealership and rental 
processes with a centralized, transparent, and accessible digital 
system that works on any modern browser.

---

## 2. Project Objectives

The RentSell system aims to achieve the following objectives:

### 2.1 Primary Objectives

1. **Enable secure user accounts** — Allow visitors to register, log 
   in/out, and update their profiles safely.

2. **Empower owners to publish listings** — Provide a simple way for 
   owners to create listings with title, category, purpose (sale/rent), 
   price, location, and photos.

3. **Provide a public marketplace** — Let visitors browse, search, and 
   view listing details without needing an account.

4. **Support advanced discovery** — Enable filtering by category, 
   purpose, price range, and location so users find relevant items fast.

5. **Facilitate communication** — Allow buyers to send inquiries and 
   owners to view and reply in a conversation thread.

6. **Give owners full listing control** — Let owners view, edit, delete, 
   and update the availability (Available / Sold / Rented) of their own 
   listings.

7. **Enable personal features** — Allow registered users to save 
   favorite listings for later.

8. **Provide moderation tools** — Allow users to report listings and 
   administrators to review reports and remove inappropriate content.

### 2.2 Process Objectives

9. **Apply Scrum in practice** — Deliver the system through 5 sprints 
   with proper planning, daily stand-ups, reviews, and retrospectives.

10. **Maintain full documentation** — Keep the Product Backlog, user 
    stories, requirements, diagrams, meeting minutes, and test results 
    in a shared GitHub repository.

11. **Ensure traceability** — Link every requirement to a user story, 
    sprint, and test so nothing is lost.

12. **Deliver a working system** — Produce a tested, demonstrable 
    product by Day 20 that meets the agreed Definition of Done.

---

## 3. Project Scope

### 3.1 In Scope

The following features and capabilities **are included** in this release:

#### User Management
- Visitor registration (name, email, phone, password)
- Login and logout
- Session expiry after inactivity
- Profile update (name, phone, email, password)

#### Listings
- Create listings (title, category, purpose, price, location)
- Upload listing photos (JPG/PNG, size-limited)
- Browse available listings publicly
- View full listing details with image gallery
- Edit listings (owner-only)
- Delete listings (owner-only, with confirmation)
- Update availability (Available / Sold / Rented)

#### Discovery
- Keyword search (title + description)
- Filter by category and purpose (sale/rent)
- Filter by price range and location
- Combined filters with reset option

#### Communication
- Send inquiries from listing detail pages
- View received inquiries (owner inbox)
- Reply to inquiries in a conversation thread

#### Personal Features
- Save and remove favorite listings
- Favorites persist across sessions
- Prevent duplicate favorites

#### Moderation
- Report listings with a reason
- Admin review of reports (Pending / Resolved)
- Dismiss report or remove/hide listing
- Log all moderation actions

#### Technical & Process
- Role-based access control (Visitor, Registered User, Owner, Admin)
- Responsive web UI
- Daily backups and basic security (hashed passwords, HTTPS in production)
- Full Scrum documentation on GitHub

### 3.2 Out of Scope

The following features **are NOT included** in this release:

- Real payment gateway integration (only mocked if at all)
- Live chat or chatbot support
- Native mobile applications (iOS/Android)
- AI-based price recommendations
- Multi-language / localization support
- Advanced analytics or business intelligence dashboards
- Email marketing or push notifications
- Third-party calendar integration
- Video uploads for listings
- Digital contract signing

These items may be considered for future releases but are excluded 
from the current 20-day scope.

### 3.3 Scope Boundaries

| Boundary | Detail |
|---|---|
| **Time** | 20 days (5 sprints × 4 days) |
| **Team** | 4 members (PO, SM, 2 Developer) |
| **Platform** | Web application (browser-based) |
| **Users** | Visitor, Registered User, Owner, Administrator |
| **Delivery** | Working system + full Scrum documentation on GitHub |
| **Technology** | Any language/database chosen by the developer |

---

## 4. Product Goal

> *"To build a working Property Sales and Rental Management System 
> that allows users to publish, browse, and manage listings for 
> properties and belongings — with search, filtering, inquiries, 
> favorites, and moderation — delivered in 20 days across 5 sprints 
> using Scrum."*

---

## 5. Success Criteria

The project will be considered successful when:

1. ✅ All 20 user stories are addressed (Done or honestly disclosed as deferred)
2. ✅ Core flows work end-to-end:
   - Register → Log in → Publish listing → Browse → Search → Inquire → Reply → Update availability
3. ✅ All 5 sprints have planning, daily, review, and retrospective records
4. ✅ Requirements specification includes FR and NFR
5. ✅ Use case and sequence diagrams are readable and aligned
6. ✅ Testing evidence exists for accepted stories
7. ✅ Repository is complete and accessible to the instructor
8. ✅ Final review honestly discloses delivered scope and limitations

---

## 6. Assumptions and Constraints

### 6.1 Assumptions
- Team members are available daily for stand-ups
- Instructor accepts a 3-person team
- Users have internet access and modern browsers
- Email service is available (or mocked) for notifications
- Meeting recordings are accessible to the instructor

### 6.2 Constraints
- **Timeline:** 20 days (5 sprints × 4 days)
- **Team size:** 3 members
- **Budget:** Academic project — no paid third-party services
- **Tools:** GitHub, Excel, Word/Markdown, draw.io, meeting app with recording
- **Documentation:** Standard Scrum templates required
- **Submission:** All artifacts on GitHub

---

## 7. Deliverables

| # | Deliverable | Location |
|---|---|---|
| 1 | Project Overview (this document) | `docs/project-overview.md` |
| 2 | Team Roles | `docs/team-roles.md` |
| 3 | Product Backlog (20 user stories) | `scrum/product-backlog/user-stories.md` |
| 4 | Product Backlog (Excel) | `scrum/product-backlog/product-backlog.xlsx` |
| 5 | Sprint Backlogs (5) | `scrum/sprint-N/sprint-backlog.md` |
| 6 | Sprint Planning minutes (5) | `scrum/sprint-N/meetings/planning.md` |
| 7 | Daily Scrum minutes (20) | `scrum/sprint-N/meetings/daily-day-N.md` |
| 8 | Sprint Review minutes (5) | `scrum/sprint-N/meetings/review.md` |
| 9 | Retrospective minutes (5) | `scrum/sprint-N/meetings/retrospective.md` |
| 10 | System Requirements Specification | `docs/system-requirements-specification.md` |
| 11 | Use Case Diagram | `docs/diagrams/use-case.png` |
| 12 | Sequence Diagrams | `docs/diagrams/sequence-N.png` |
| 13 | Test Results | `docs/testing/test-results.md` |
| 14 | Final Review | `docs/final-review.md` |
| 15 | Meeting Recordings | `recordings/sprint-N/*.mp4` |
| 16 | Source Code | `/src` or team-chosen folder |

---

## 8. Change Log

| Version | Date | Author | Change |
|---|---|---|---|
| 1.0 | [Insert Date] | [Your Name] | Initial project overview created |

---

## 9. Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Product Owner | Abdul Wares Momand | _________ |8/10/2026|
| Scrum Master | Ali Reza Haidari| _________ | 8/10/2026|
| Developers | Abdul Moqtader Sohail, Bibi Hadisa Aryan | _________ | 8/10/2026 |

