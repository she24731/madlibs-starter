# Sprint 1 Review  
**Date:** November 12, 2025  

---

## Sprint Goal  
Deliver a functional MVP skeleton deployed to staging.  
Users can log in, browse categories, and view sample posts with role-based access (Reader, Contributor, Admin).  

---

## Completed User Stories with Demo Notes  

All planned stories were successfully completed and deployed to staging:  

- **E1 (Auth & Roles)**  
  - Initialized Django project and settings  
  - Configured DuckDB and seeded data  
  - Implemented Auth + Groups  
  - Completed login/logout views and role-based permissions  

- **E2 (Categories)**  
  - Created Category model and admin seed  
  - Built Category Hub template (desktop)  
  - Displayed posts by category (view + template)  

- **E4 (Content)**  
  - Defined Post model including status field  

**Demo Notes:**  
- The authentication system works for all three user roles with appropriate permissions.  
- Category hub and navigation are functional, showing sample seeded posts.  
- Admin dashboard accessible for content review and basic management.  
- Staging deployment completed and verified by all team members.  

---

## Incomplete User Stories  

None — all planned user stories were completed within the sprint scope.  

---

## Metrics  

- **Planned Story Points:** 26  
- **Completed Story Points:** 26  
- **Velocity:** 26 story points  
- **Completion Rate:** 100%  

---

## Lessons Learned from First Development Sprint  

- **Database migration bug:** During initial setup, migration issues caused temporary data loss. The team restored the database successfully, though category data was briefly lost and had to be re-seeded.  
- Improved understanding of Django migrations and dependency handling between models.  
- Established workflow for future rollback and data validation during deployment.  

---

## Product Backlog Updates  

- No changes to the backlog were required.  
- All issues were resolved, and the team confirmed database stability for upcoming sprints.  
