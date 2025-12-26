
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


# 2. Software Project Management Plan (SPMP)

## 2.1 Introduction / Overview of the Project
**Project Name:** CampusConnect Mobile Application  
**Description:** This project involves the development of a unified mobile portal for iOS and Android to centralize the University's legacy student services.  
**Purpose:** To eliminate the 40% navigation difficulty rate reported by students using current disparate systems and to ensure students meet critical academic deadlines via a mobile-first interface.  
**Objectives:** * Consolidate Grades, News, Transit, and Course Registration into one app.
* Achieve 1,500 student downloads within 30 days of launch.
* Maintain a performance threshold of <3s load time.



## 2.2 Project Organization
The project is managed under a **Matrix Structure**, utilizing experts from the University’s Students.
* **2.2.1 Project Sponsor:** Dr. Ahmed Shalaby (Dean of Student Affairs) – Funding and high-level approval.
* **2.2.2 Project Manager:** Ahmed Shaban – Leads integration, scheduling, and stakeholder management.
* **2.2.3 Development Team:** Omar Sholkamy & Ahmed Fahmy (Mobile); Omar Isleem (Backend/APIs).
* **2.2.4 Quality Assurance:** Nadeem Shokry – Leads System Integration Testing (SIT) and UAT.

## 2.3 Management and Technical Processes
### 2.3.1 Management Processes
* **Monitoring & Controlling:** Weekly reports are used to monitor the "Big Picture" and ensure all knowledge areas are coordinated.
* **Integrated Change Control (ICC):** Any change to the project scope, such as adding a "Tuition Payment" module, requires a formal Change Request and Sponsor sign-off to prevent budget overruns.



### 2.3.2 Technical Processes
* **Lifecycle Model:** A Hybrid approach using Waterfall for initial requirements and Agile Sprints for coding individual modules.
* **Technical Infrastructure:** Development will be hosted on AWS, using GitHub for version control and Jira for tracking software bugs.

## 2.4 Work to be Done
The project is divided into the following technical phases:
* **Requirement Analysis:** Mapping data fields from legacy systems to the new mobile API.
* **UI/UX Design:** Developing wireframes and prototypes for student feedback.
* **Implementation:** Coding the SSO Authentication, Gradebook, and GPS Transit modules.
* **Testing:** Conducting internal integration tests and a 50-student Beta (UAT) group.

## 2.5 Schedule and Budget Information
### 2.5.1 Milestone Schedule
* **M1:** Project Charter & PMP Approval – Month 1
* **M2:** Design Sign-off – Month 2
* **M3:** Development Completion – Month 4
* **M4:** UAT & Beta Testing – Month 5
* **M5:** Official App Store Release – Month 6

### 2.5.2 Budget Summary
| Category | Allocated Amount |
| :--- | :--- |
| **Personnel** | $30,000 |
| **Software/Licenses** | $10,000 |
| **Marketing** | $5,000 |
| **Contingency Reserve (10%)** | $5,000 |
| **Total Project Budget** | **$50,000** |

## 2.6 References to Other Project Planning Documents
* **Project Charter:** Finalized and signed on Oct 24, 2025.
* **Risk Register:** Tracks legacy API instability and App Store rejection risks.
* **IEEE Std 1058:** Guidelines used for this Software Project Management Plan.
* **FERPA/GDPR Policies:** Standards for protecting student data privacy.

# 3. Project Scope Management

Project Scope Management includes the processes required to ensure that the project includes **all the work required, and only the work required**, to successfully complete the CampusConnect Mobile Application project.

This section covers how project requirements are traced and how the total project work is structured and controlled.

---

### 3.1 Requirements Traceability Matrix (RTM)
**Category:** Project Document (Requirements Management)

The Requirements Traceability Matrix (RTM) is a key project document used during the **Collect Requirements** process to ensure that all project requirements are clearly identified, documented, and tracked throughout the project lifecycle.

In alignment with the Project Charter and stakeholder inputs, the RTM provides end-to-end traceability by linking each requirement to its source and monitoring its implementation status. This ensures that:
- No approved requirement is overlooked or omitted.
- All functional and non-functional requirements remain aligned with project objectives.
- Scope validation and scope control activities can be effectively supported during later project phases.

The RTM also serves as a control mechanism to assess the impact of proposed changes and helps prevent scope creep by ensuring that only approved requirements are implemented.

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

### 3.2 Work Breakdown Structure (WBS)
**Category:** Scope Baseline

The Work Breakdown Structure (WBS) is a deliverable-oriented hierarchical decomposition of the total project scope and is developed during the **Create WBS** process. It defines **all the work required, and only the work required**, to successfully deliver the CampusConnect Mobile Application.

The WBS is created using the **decomposition technique**, where major project deliverables are progressively subdivided into smaller, more manageable components known as work packages. These work packages form the foundation for accurate schedule estimation, cost planning, resource allocation, and change control.

By organizing project work in this structured manner, the WBS ensures clarity of responsibilities, improves communication among stakeholders, and reduces the risk of scope creep.

#### 3.2.1 WBS Overview
The WBS provides a structured view of the project deliverables and ensures that no project work is overlooked while maintaining alignment with the approved project scope statement.

#### 3.2.2 WBS Hierarchy
1.0 CampusConnect Mobile Application  
1.1 Project Management  
1.2 Requirements & Design  
1.3 Development  
1.4 Testing  
1.5 Deployment & Launch  

#### 3.2.3 Scope Baseline
The scope baseline represents the approved version of the project scope and consists of:
- Approved Project Scope Statement  
- Work Breakdown Structure (WBS)  
- WBS Dictionary  

The scope baseline is used as a reference point for scope validation and scope control throughout the project lifecycle.

---

## 4. Activity List

### 4.1 Defining Activities – Overview

Defining activities is a key process within **Project Schedule Management** that involves identifying and documenting the specific actions required to produce the project deliverables. These activities are derived directly from the Work Breakdown Structure (WBS) and are defined in sufficient detail to support accurate schedule development, resource estimation, and project control.

According to the project schedule management processes covered in the lecture, the primary output of this process is the **Activity List**, which includes all activities that must be performed to complete the project successfully.

Each activity is assigned:
- A unique activity identifier  
- A clear and concise activity name  
- A brief description of the work involved  

These activities will later be used for sequencing, duration estimation, and schedule development.

---

### 4.2 Activity List

| Activity ID | Activity Name | Description |
| :--- | :--- | :--- |
| A-01 | Initiate Project & Charter Approval | Review, finalize, and formally approve the Project Charter |
| A-02 | Conduct Stakeholder Interviews | Identify and gather functional and non-functional requirements from stakeholders |
| A-03 | Document System Requirements | Analyze, document, and validate project requirements |
| A-04 | Approve Requirements Baseline | Review and formally approve the requirements baseline |
| A-05 | Design UI/UX Wireframes | Create wireframes and prototypes for the mobile application |
| A-06 | Design System Architecture | Define backend architecture and integration approach |
| A-07 | Develop SSO Authentication Module | Implement secure Single Sign-On functionality |
| A-08 | Develop Academic Modules | Implement Gradebook and Course Registration modules |
| A-09 | Develop Campus Services Modules | Implement Campus Bus Tracker and News Feed modules |
| A-10 | Backend API Integration | Integrate legacy university systems with the mobile application |
| A-11 | Unit Testing | Test individual application components |
| A-12 | Integration Testing | Test interaction between application modules and backend systems |
| A-13 | User Acceptance Testing (UAT) | Conduct beta testing with selected student users |
| A-14 | Fix Defects from UAT | Resolve issues identified during UAT |
| A-15 | App Store Deployment | Submit and publish the application to App Store and Google Play |
| A-16 | Project Closure | Final documentation, handover, and project sign-off |

---

### 4.3 Notes on Activity List Usage

The Activity List serves as a foundational input to subsequent schedule management processes, including:
- **Sequencing Activities**
- **Estimating Activity Durations**
- **Developing the Project Schedule**
- **Controlling the Schedule**

Milestones such as *Project Charter Approval*, *Requirements Approval*, and *App Store Release* are represented as significant events that mark progress and typically have zero duration.

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
