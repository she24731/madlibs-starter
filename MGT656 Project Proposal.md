# **Project Proposal(order based on preference)**

## **Idea 1: Yale Newcomer Survival Guide**

### **Tagline**

A one-stop platform to help Yale newcomers quickly adapt to life in New Haven — from housing and food to classes and campus life.

### **Major User Journeys**

As a new student:  
 \- I log in to the platform and browse practical tips organized by categories (housing, transportation, food, academics, etc.).  
 \- I bookmark my favorite posts for later reference.  
 \- I search for “where to buy furniture” or “how to register for courses,” and instantly find curated student-contributed answers.

As a returning student (content contributor):  
 \- I can submit my own guides, tips, or photos to help newcomers.  
 \- I can edit or update outdated information.

As an admin:  
 \- I review and approve user-submitted content before it’s published.  
 \- I can manage users, categorize posts, and remove irrelevant or outdated content.

### **Core Features (MVP: 3–5)**

1\. Category-based content display – Organized by topics (Housing, Food, Transport, Study, etc.) with a search function.  
 2\. User authentication system – New students, contributors, and admins can log in with different privileges.  
 3\. Content submission and review system – Contributors can create or edit guides, and admins approve before publication.  
 4\. Bookmark/Favorite feature – Users can save useful posts for later.  
 5\. (Optional for later) Comment or upvote system for user engagement.

### **Why This Project Fits**

• Tractable: The project can be built within one semester as a CMS-style web application using Django \+ PostgreSQL.  
 • Amenable to course technologies: Uses standard MVC framework, database, and HTML/CSS frontend (server-side rendering).  
 • Valuable & Fun: This project directly benefits Yale newcomers — including the developer — by providing real, helpful content for daily campus life.

### **Additional Idea References (for instructor review)**

If time allows, this project could later expand into:  
 \- A map-based view showing key locations (cafes, gyms, supermarkets).  
 \- A Q\&A section connecting new and experienced students.  
 However, for this semester, we will focus on building the MVP with user authentication, categorized content, and submission workflow.

### **Feasibility Summary**

| Evaluation Criteria | Assessment |
| :---- | :---- |
| Tractable | ✓ Realistic scope for one semester |
| Amenable to Course Tech | ✓ Django / PostgreSQL / HTML/CSS stack |
| Valuable/Fun | ✓ High — solves real student needs and personally meaningful |

## **Idea 2: Hangout borderline**

### **Tagline**

*A community event platform where international students host hangouts to bridge cultures and make friends abroad.*

---

### **Major User Journeys**

**As a new international student:**

* I sign up with my university email and basic profile (passport, name, origin country, native languages, photo, current country, ethnicity).  
* International students can host events such as dining together, study group, grocery shopping, sports, museums, traveling, etc. The event information must include pictures, location, fee, participants, transportation, as detailed as possible.  
* I browse upcoming events by category—food, study, sports, travel, museums—and see event details (time, location, cost, transportation).  
* I(both international and domestic students) request participation by swiping left/right, and later receive confirmation from the host if approved by the host.  
* After the event, I can score and write a review for the host

**As a host (international student):**

* I create an event with pictures, description, and logistics.

* I review applicants’ short profiles and accept or reject them by swiping left/right

* Once pairing succeeds, I must request applicants to provide necessary information such as intention, willing to help, etc...

* After the event, I can view feedback and increase my “host credibility score.”

**As an admin:**

* I verify that hosts are international students (passport/university ID).

* I moderate inappropriate content or fake events when flagged by users.

---

### **Core Features (MVP)**

1. **User Accounts & Profiles** — Secure login/signup with “international student” verification flag.

2. **Event Creation & Browsing** — Hosts create detailed listings; participants can filter and view events.

3. **Join & Approval Workflow** — Participants request to join; hosts approve/decline via dashboard.

4. **Feedback System (Phase 2\)** — Participants rate hosts; hosts build reputation over time.

5. (TBD) Swipe-style interface or complex real-time chat—planned for later sprint.

---

### **Why It Meets Evaluation Criteria**

**1️⃣ Tractable** – The MVP uses standard CRUD operations (users, events, reviews) and can be built within one semester using Django or Rails. The swiping UI and analytics are deferred to future versions.

**2️⃣ Amenable to Course Technologies** – Well-suited for a backend MVC framework with a relational database (PostgreSQL / SQLite) and simple server-rendered HTML/CSS/JS frontend.

**3️⃣ Valuable / Fun / Impactful** – Addresses a real community need: helping international and domestic students connect across cultural lines. It’s practical, inclusive, and personally meaningful.

**Idea 3: AI Interview Coach**

### **Tagline**

An interactive AI-powered platform to help students practice and improve their interview performance — anytime, anywhere.

### **Major User Journeys**

**As a student preparing for interviews:**

* I log in to the platform and select my target module (e.g., *Finance*, *Product Management*, *Software Engineering*).

* I practice behavioral or technical interview questions through video recording.

* After completing the session, I receive instant AI feedback on my performance (eye contact, filler words, confidence level, clarity, etc.).

**As a returning user:**

* I can review my previous recordings, track my progress, and identify improvement areas.

* I can practice new question sets or switch to different modules.

**As an admin or instructor:**

* I can upload or update interview question sets by category.

* I can review AI performance reports and adjust feedback parameters.

### **Core Features (MVP: 3–5)**

1. **Category-based module system** – Users choose a track such as *Finance*, *Product Management*, or *Software Engineering*.

2. **Video recording & playback** – Allows students to record mock interviews directly on the platform.

3. **AI-powered feedback** – Detects facial expressions, eye contact, speaking pace, and provides improvement suggestions.

4. **User dashboard & progress tracking** – Stores practice history and visualizes progress over time.

5. *(Optional for later)* Peer review or instructor feedback integration for collaborative learning.

### **Why This Project Fits**

* **Tractable:** The MVP can be built within one semester using standard web technologies with basic AI/ML integrations (e.g., OpenAI API, MediaPipe, or facial expression libraries).

* **Amenable to course technologies:** Backend with Django \+ PostgreSQL, frontend with HTML/CSS/JS, and Python-based AI feedback module.

* **Valuable & Fun:** Provides real-world benefits for students preparing for internship and full-time job interviews. It’s both educational and personally useful.

### **Additional Idea References (for instructor review)**

If time allows, the project could later expand to include:

* A personalized interview question generator based on user background.

* Real-time speech analysis with sentiment scoring.

* Integration with LinkedIn or resume uploads to generate customized mock interviews.

### **Feasibility Summary**

| Evaluation Criteria | Assessment |
| ----- | ----- |
| **Tractable** | ✓ Realistic MVP scope for one semester |
| **Amenable to Course Tech** | ✓ Django / PostgreSQL / HTML/CSS / AI API stack |
| **Valuable/Fun** | ✓ High — directly helps students with career development |

