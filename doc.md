
# PROJECT CHARTER: CampusConnect Mobile Application

**Date:** October 24, 2025  
**Sponsor:** Dr. Ahmed Shalaby, University Dean of Student Affairs  
**Project Manager:** Ahmed Shaaban  

---

## 1. Executive Summary & Business Case
The University currently relies on four disparate legacy systems for student services (Grades, News, Transit, and Course Registration). Feedback from the Student Union indicates that 40% of students find the current systems difficult to navigate on mobile devices, leading to missed registration deadlines and lower engagement. The CampusConnect project will consolidate these services into a single, unified iOS and Android mobile application to improve accessibility and the student experience.

## 2. Project Goal
To design, develop, and launch a fully functional mobile portal (CampusConnect) that allows students to access critical university services via single sign-on (SSO) by the start of the Fall Semester.

## 3. Project Objectives (Success Criteria)
* **Adoption:** Achieve 1,500 unique student downloads within 30 days of launch.
* **Performance:** App load time must be under 3 seconds on 4G/5G networks.
* **Reliability:** 99.9% uptime during the course registration period.
* **Budget:** Complete the project within the allocated $50,000 budget.

## 4. High-Level Scope
* **In-Scope:** Native iOS/Android development, SSO Integration, Gradebook, Bus Tracker, Course Registration, News Feed, and UAT (50 students).
* **Out-of-Scope:** Web/Desktop redesign, Tuition payments (Phase 2), Faculty/Staff interface.

## 5. High-Level Budget
| Category | Allocation |
| :--- | :--- |
| Personnel | $30,000 |
| Software/Licenses | $10,000 |
| Marketing/Training | $5,000 |
| Contingency Reserve (10%) | $5,000 |
| **Total Authorization** | **$50,000 USD** |

---

## 6. Requirements Traceability Matrix (RTM)



| Req ID | Requirement Description | Priority | WBS ID | Test Case ID | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| REQ-001 | Authentication (SSO) | High | 3.1 | TC-AUTH-01 | Active |
| REQ-002 | Gradebook Integration | High | 3.2 | TC-ACAD-05 | Active |
| REQ-003 | Course Registration | High | 3.3 | TC-REG-02 | Active |
| REQ-004 | Campus Map (GPS) | Medium | 3.4 | TC-MAP-08 | Active |
| REQ-005 | Push Notifications | Medium | 3.5 | TC-NOTIF-10 | Active |
| REQ-006 | Performance (<3s) | High | 4.2 | TC-PERF-01 | Active |
| REQ-007 | Privacy (TLS 1.3) | High | 2.2 | TC-SEC-03 | Active |

---

## 7. Work Breakdown Structure (WBS)
1.  **1.0 Project Management** (Charter, PMP, Reporting, Closure)
2.  **2.0 Requirements & Design** (Stakeholder Interviews, UI/UX Wireframes, Architecture)
3.  **3.0 Development** (SSO Module, Academic Module, Campus Services, Backend Setup)
4.  **4.0 Testing** (Unit, SIT, Performance, UAT, Bug Fixing)
5.  **5.0 Deployment & Launch** (App Store Submission, Marketing, Go-Live Support)

---

## 8. Activity List & Network Diagram Logic

| Activity ID | WBS Ref | Activity Name | Predecessors | Relationship |
| :--- | :--- | :--- | :--- | :--- |
| A-1 | 2.1.1 | Stakeholder Interviews | Start | - |
| A-2 | 2.2.1 | Design UX Wireframes | A-1 | FS |
| A-3 | 2.3.1 | Define Database Schema | A-1 | FS |
| A-4 | 2.3.2 | Secure API Access | A-1 | FS |
| A-5 | 3.4.1 | Set Up Dev Environment | A-3 | FS |
| A-6 | 3.1.1 | Develop SSO Login | A-2, A-4, A-5 | FS |
| A-7 | 3.2.1 | Develop Gradebook | A-6 | FS |
| A-8 | 3.2.2 | Develop Registration | A-6 | FS |
| A-9 | 3.3.1 | Develop Campus Maps | A-5 | FS |
| A-10 | 4.1.0 | Integration Testing | A-7, A-8, A-9 | FS |
| A-11 | 4.4.0 | Conduct UAT (Beta) | A-10 | FS |
| A-12 | 5.1.0 | Submit to App Stores | A-11 | FS |
| A-13 | 5.2.2 | Launch Marketing | A-12 | FS |



---

## 9. Gantt Chart (Schedule Data)

| Activity ID | Activity Name | Start Date | End Date | Duration |
| :--- | :--- | :--- | :--- | :--- |
| A-1 | Stakeholder Interviews | M1, W1 | M1, W2 | 2 Weeks |
| A-2 | Design UX Wireframes | M1, W3 | M2, W1 | 3 Weeks |
| A-6 | Develop SSO Login | M2, W2 | M2, W4 | 3 Weeks |
| A-7 | Develop Gradebook | M3, W1 | M3, W4 | 4 Weeks |
| A-8 | Develop Registration | M4, W1 | M4, W4 | 4 Weeks |
| A-10 | Integration Testing | M5, W1 | M5, W2 | 2 Weeks |
| A-11 | Conduct UAT (Beta) | M5, W3 | M5, W4 | 2 Weeks |
| A-12 | Submit to App Stores | M6, W1 | M6, W2 | 2 Weeks |
| A-13 | Launch Marketing | M6, W3 | M6, W4 | 2 Weeks |
