
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

# 4. Project Schedule Management

## 4.1 Activity List
The following activities represent the decomposition of the WBS work packages into specific actions required to produce the project deliverables.

| Activity ID | Activity Name | Description | Duration (Est. Days) |
| :--- | :--- | :--- | :--- |
| **A-01** | Charter & PMP Approval | Formal sign-off of the project roadmap and authority. | 3 |
| **A-02** | Stakeholder Interviews | Gather technical data specs from Registrar and Transit offices. | 7 |
| **A-03** | Requirements Documentation | Formalizing the RTM and functional specification document. | 5 |
| **A-04** | UI/UX Design & Prototyping | Creating high-fidelity wireframes for student feedback. | 12 |
| **A-05** | Backend API Mapping | Defining how AWS middleware connects to legacy Banner systems. | 8 |
| **A-06** | SSO & Security Coding | Implementing OAuth2 for secure student login. | 10 |
| **A-07** | Academic Module Dev | Developing the Gradebook and Course Registration logic. | 20 |
| **A-08** | Campus Services Dev | Developing the GPS Bus Tracker and News Feed parser. | 15 |
| **A-09** | System Integration | Merging frontend modules with the backend API layer. | 10 |
| **A-10** | Unit & Alpha Testing | Internal technical testing of individual modules. | 7 |
| **A-11** | User Acceptance Testing (UAT) | Controlled pilot with 50 students to validate usability. | 10 |
| **A-12** | App Store Submission | Handling the 14-day review cycle for Apple and Google. | 14 |
| **A-13** | Marketing & Launch | Distribution of user guides and official campus release. | 5 |



## 4.2 Activity Attributes & Sequencing
Following the **Precedence Diagramming Method (PDM)** from Lecture 6, the table below defines the logical dependencies (Finish-to-Start) necessary for the Network Diagram.

| Activity ID | Predecessors | Resources | Logical Relationship |
| :--- | :--- | :--- | :--- |
| **A-01** | — | PM, Sponsor | Project Start |
| **A-02** | A-01 | PM, Stakeholders | FS (Cannot interview without authority) |
| **A-03** | A-02 | PM, IT Team | FS (Specs depend on interview data) |
| **A-04** | A-03 | UI/UX Designer | FS (Design requires approved specs) |
| **A-05** | A-03 | Backend Dev | FS (Arch depends on technical specs) |
| **A-06** | A-04, A-05 | Mobile/Backend Dev | FS (Coding requires design & arch) |
| **A-07** | A-06 | Mobile/Backend Dev | FS (Academic data requires login/SSO) |
| **A-08** | A-06 | Mobile Dev | FS (Campus services require login/SSO) |
| **A-09** | A-07, A-08 | Backend Dev | FS (Integration follows module coding) |
| **A-10** | A-09 | QA Engineer | FS (Testing follows integration) |
| **A-11** | A-10 | QA, Students | FS (UAT requires a stable Alpha build) |
| **A-12** | A-11 | PM, IT Team | FS (Store submission follows student sign-off) |
| **A-13** | A-12 | Marketing, PM | FS (Marketing launch once app is live) |



## 4.3 Schedule Milestone List
These zero-duration milestones will be used to track progress against the project baseline.

* **M1: Project Kickoff** (Start of Month 1)
* **M2: Design Freeze** (End of Month 2)
* **M3: Code Complete** (End of Month 4)
* **M4: UAT Sign-off** (End of Month 5)
* **M5: Official Launch** (End of Month 6)
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
