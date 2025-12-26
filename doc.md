
# 1. PROJECT CHARTER

---

### 1.1 Project Name and Description

**Project Name:** CampusConnect Mobile Application  

**Description:**  
The University currently relies on multiple legacy systems to deliver student services such as Grades, Campus News, Transportation, and Course Registration. Feedback from the Student Union indicates that 40% of students struggle to use these systems on mobile devices, resulting in missed deadlines and reduced engagement.

The CampusConnect project aims to consolidate these services into a single, unified mobile application for iOS and Android platforms, improving accessibility, usability, and overall student experience.

---

### 1.2 Vision and Purpose (Objectives)

**Vision:**  
To provide students with a seamless, mobile-first digital platform that serves as a single point of access for all essential university services.

**Objectives:**  
- Improve accessibility and ease of use of university services for students.  
- Increase student engagement with digital services.  
- Reduce missed registration deadlines.  
- Deliver a secure, reliable, and high-performing mobile application within the approved budget and timeline.

---

### 1.3 Project Scope

**In Scope:**  
- Development of native mobile applications for iOS and Android.  
- Secure Single Sign-On (SSO) integration with the University authentication system.  
- Core application modules:
  - Gradebook View  
  - Live Campus Bus Tracker  
  - Course Registration System  
  - Campus News Feed  
- User Acceptance Testing (UAT) with a pilot group of 50 students.

**Out of Scope:**  
- Web-based (desktop) portal redesign.  
- Tuition payment processing (planned for Phase 2).  
- Faculty and staff system interfaces.

---

### 1.4 Key Stakeholders
- Project Sponsor: Dean of Student Affairs  
- University IT Department  
- Registrar’s Office  
- Transportation Office  
- Student Union  
- Students  
- Student Clubs and Organizations  
- Mobile Application Development Team  

---

### 1.5 Identified Risks and Constraints

**Identified Risks:**  
- Technical Risk: Legacy system APIs may have slow response times, requiring caching or middleware solutions.  
- Schedule Risk: Delays in Apple App Store or Google Play Store approval processes may affect the launch date.  
- Privacy and Compliance Risk: Handling sensitive student data requires strict compliance with FERPA and GDPR regulations.

**Constraints:**  
- Fixed project budget of $50,000 USD.  
- Mandatory launch before the start of the Fall Semester.  
- Compliance with university IT security and data protection standards.

---

### 1.6 Project Budget

**Total Authorized Budget:** $50,000 USD  

- Personnel Costs: $30,000  
- Software and Licensing: $10,000  
- Marketing and Training: $5,000  
- Contingency Reserve (10%): $5,000  

---

### 1.7 Project Team Roles and Responsibilities

- **Project Sponsor:**  
  Provides strategic direction, approves funding, and authorizes major project decisions.

- **Project Manager (Ahmed Shaban):**  
  Responsible for overall project planning, execution, monitoring, and control.

- **University IT Team:**  
  Provides infrastructure support, security compliance oversight, and deployment readiness.

- **Student Pilot Group:**  
  Participates in User Acceptance Testing and provides feedback prior to full application launch.

---

### 1.8 Project Timeline and Milestones

- Phase 1 (Month 1, Week 1): Project Charter approval  
- Phase 2 (Month 2, Week 2): Requirements and design approval  
- Phase 3 (Month 4, Week 4): Development completion  
- Phase 4 (Month 5, Week 2): Beta testing and UAT  
- Phase 5 (Month 6, Week 4): Final App Store release  

---

### 1.9 Performance Indicators for Success

- At least 1,500 unique student downloads within 30 days of launch.  
- Application load time under 3 seconds on 4G/5G networks.  
- 99.9% uptime during course registration periods.  
- Project completed within the approved $50,000 USD budget and planned schedule.

---

# PROJECT MANAGEMENT PLAN  
## CampusConnect Mobile Application

---

## 1. Overview

### 1.1 Purpose
This Project Management Plan (PMP) defines how the CampusConnect project will be planned, executed, monitored, controlled, and closed.

### 1.2 Scope and Objectives
The plan applies to all project phases and ensures delivery within scope, schedule, and budget.

### 1.3 Assumptions and Constraints
**Assumptions:**  
- Legacy system APIs remain available  
- Stakeholders are accessible  
- Standard app store approval timelines apply  

**Constraints:**  
- Fixed $50,000 budget  
- Fall semester deadline  
- FERPA/GDPR compliance  

### 1.4 Project Deliverables
- Mobile applications (iOS & Android)  
- Backend services  
- Test reports  
- User documentation  

### 1.5 Schedule and Budget Summary
- Duration: 6 months  
- Budget: $50,000 USD  

### 1.6 Evolution of the Plan
This plan may be updated through formal change control.

### Document Ownership
This Project Management Plan is developed and maintained by the Project Manager and approved by the Project Sponsor.

---

## 2. Project Organization
Centralized structure led by the Project Manager with development, QA, and IT support.

---

## 3. Managerial Process Plan
Includes startup planning, work planning, control mechanisms, risk management, and project closeout.

---

## 4. Technical Process Plans
Defines lifecycle model, tools, infrastructure, and acceptance approach.

---

## 5. Supporting Process Plans
Covers configuration management, quality assurance, testing, documentation, and continuous improvement.

---

## 6. Requirements Traceability Matrix (RTM)

| Requirement No. | Name | Category | Source | Status |
| :--- | :--- | :--- | :--- | :--- |
| R-01 | Single Sign-On (SSO) | Functional | Project Charter | In Progress |
| R-02 | Gradebook Module | Functional | Registrar’s Office | In Progress |
| R-03 | Course Registration | Functional | Academic Affairs | In Progress |
| R-04 | Campus Bus Tracker | Functional | Transportation Office | Planned |
| R-05 | News Feed | Functional | Student Union | Planned |
| R-06 | Performance (<3s load) | Non-Functional | Project Objectives | Planned |
| R-07 | Data Privacy & Security | Non-Functional | FERPA/GDPR Policies | Planned |

---

## 7. Work Breakdown Structure (WBS)

### 7.1 WBS Overview
The WBS is a deliverable-oriented hierarchical decomposition of the total project scope and forms the basis for schedule, cost, and resource planning.

### 7.2 WBS Hierarchy
1.0 CampusConnect Mobile Application  
1.1 Project Management  
1.2 Requirements & Design  
1.3 Development  
1.4 Testing  
1.5 Deployment & Launch  

### 7.3 Scope Baseline
The scope baseline includes the approved scope statement, WBS, and WBS dictionary.

---

## 8. Defining Activities

Defining activities involves identifying the specific actions required to produce the project deliverables in sufficient detail to enable accurate schedule and resource estimation.

---

### 8.1 Activity List

| Activity ID | Activity Name | Description |
| :--- | :--- | :--- |
| A-01 | Conduct Stakeholder Interviews | Gather functional and non-functional requirements |
| A-02 | Define System Requirements | Document and approve requirements |
| A-03 | Design UI/UX Wireframes | Create application interface designs |
| A-04 | Design System Architecture | Define backend and integration architecture |
| A-05 | Develop SSO Module | Implement authentication and login |
| A-06 | Develop Academic Modules | Implement gradebook and registration |
| A-07 | Develop Campus Services | Implement bus tracker and news feed |
| A-08 | Backend API Integration | Integrate legacy systems |
| A-09 | Unit Testing | Test individual components |
| A-10 | Integration Testing | Test combined modules |
| A-11 | User Acceptance Testing | Conduct beta testing with students |
| A-12 | App Store Deployment | Submit and publish applications |

---

### 8.2 Activity Attributes

| Activity ID | Predecessors | Relationship | Resources | Constraints | Assumptions |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A-01 | Start | FS | PM, Stakeholders | Stakeholder availability | Stakeholders cooperate |
| A-02 | A-01 | FS | PM, Analysts | Approval timelines | Requirements stable |
| A-03 | A-02 | FS | UI/UX Designer | Design standards | UI tools available |
| A-04 | A-02 | FS | Backend Developer | Architecture policies | APIs accessible |
| A-05 | A-03, A-04 | FS | Backend Developer | Security compliance | SSO specs approved |
| A-06 | A-05 | FS | Mobile Developers | Module dependencies | Reusable components |
| A-07 | A-05 | FS | Mobile Developers | GPS accuracy | Maps API available |
| A-08 | A-04 | FS | Backend Developer | Legacy system limits | APIs stable |
| A-09 | A-06, A-07 | FS | QA Engineer | Test environment | Code complete |
| A-10 | A-09, A-08 | FS | QA Engineer | Integration readiness | Stable build |
| A-11 | A-10 | FS | Students, QA | Student availability | Positive participation |
| A-12 | A-11 | FS | PM, IT Team | Store approval | No rejection |

---

## Document Approval and Sign-Off

| Role | Name | Signature | Date |
| :--- | :--- | :--- | :--- |
| Project Sponsor | Dr. Ahmed Shalaby |  |  |
| Project Manager | Ahmed Shaban |  |  |

---

## Project Team Acknowledgement

| Name | Role | Responsibility |
| :--- | :--- | :--- |
| Omar Emad Sholkamy | Mobile Developer | iOS/Android development |
| Ahmed Fahmy | Mobile Developer | iOS/Android development |
| Omar Isleem | Backend Developer | API & backend integration |
| Nadeem Shokry | QA Engineer | Testing and UAT support |

---

## References
- Project Charter: CampusConnect Mobile Application  
- IEEE SPMP Guidelines  
- University IT Policies

---
