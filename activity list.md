## 5. Activity List and Sequencing Activities

### 5.1 Defining Activities – Overview

Defining activities is a core process within **Project Schedule Management** that involves identifying the specific actions required to produce the project deliverables. Activities are derived directly from the Work Breakdown Structure (WBS) and are defined in sufficient detail to support accurate schedule development, sequencing, and control.

The primary output of this process is the **Activity List**, which includes all activities necessary to complete the project, along with their identifiers, descriptions, and alignment with the WBS hierarchy.

---

### 5.2 Activity List

| Activity ID | Activity Name | Description | WBS ID |
| :--- | :--- | :--- | :--- |
| A-01 | Initiate Project & Charter Approval | Review, finalize, and formally approve the Project Charter | 1.1 |
| A-02 | Conduct Stakeholder Interviews | Gather functional and non-functional requirements from stakeholders | 1.2 |
| A-03 | Document System Requirements | Analyze, document, and validate system requirements | 1.2 |
| A-04 | Approve Requirements Baseline | Review and formally approve requirements baseline | 1.2 |
| A-05 | Design UI/UX Wireframes | Create UI/UX wireframes and prototypes | 1.2 |
| A-06 | Design System Architecture | Define backend and integration architecture | 1.2 |
| A-07 | Develop SSO Authentication Module | Implement secure authentication and login | 1.3 |
| A-08 | Develop Academic Modules | Implement gradebook and course registration modules | 1.3 |
| A-09 | Develop Campus Services Modules | Implement bus tracker and news feed modules | 1.3 |
| A-10 | Backend API Integration | Integrate legacy systems with backend services | 1.3 |
| A-11 | Unit Testing | Test individual system components | 1.4 |
| A-12 | Integration Testing | Test interaction between system modules | 1.4 |
| A-13 | User Acceptance Testing (UAT) | Conduct beta testing with student users | 1.4 |
| A-14 | Fix Defects from UAT | Resolve issues identified during UAT | 1.4 |
| A-15 | App Store Deployment | Submit and publish application to app stores | 1.5 |
| A-16 | Project Closure | Final documentation, handover, and sign-off | 1.1 |

---

### 5.3 Sequencing Activities

Sequencing activities involves identifying and documenting the logical relationships among project activities. This process defines the order in which activities must be performed and provides a foundation for developing the **Network Diagram** and the **Project Schedule**.

Activity sequencing is based on technical dependencies, best practices, and project constraints identified during planning.

#### 5.3.1 Types of Dependencies

- **Mandatory Dependencies (Hard Logic):**  
  Activities that must follow a specific order, such as completing requirements documentation before system design.

- **Discretionary Dependencies (Soft Logic):**  
  Activities sequenced based on preferred practices, such as designing UI before development.

- **External Dependencies:**  
  Activities dependent on external entities, such as application store approval.

#### 5.3.2 Logical Relationships

The **Finish-to-Start (FS)** relationship is primarily used in this project, ensuring that predecessor activities are completed before successor activities begin.

---

### 5.4 Activity Sequencing Table

| Activity ID | Activity Name | Predecessor(s) | Relationship |
| :--- | :--- | :--- | :--- |
| A-01 | Initiate Project & Charter Approval | — | — |
| A-02 | Conduct Stakeholder Interviews | A-01 | FS |
| A-03 | Document System Requirements | A-02 | FS |
| A-04 | Approve Requirements Baseline | A-03 | FS |
| A-05 | Design UI/UX Wireframes | A-04 | FS |
| A-06 | Design System Architecture | A-04 | FS |
| A-07 | Develop SSO Authentication Module | A-05, A-06 | FS |
| A-08 | Develop Academic Modules | A-07 | FS |
| A-09 | Develop Campus Services Modules | A-07 | FS |
| A-10 | Backend API Integration | A-06 | FS |
| A-11 | Unit Testing | A-08, A-09 | FS |
| A-12 | Integration Testing | A-10, A-11 | FS |
| A-13 | User Acceptance Testing (UAT) | A-12 | FS |
| A-14 | Fix Defects from UAT | A-13 | FS |
| A-15 | App Store Deployment | A-14 | FS |
| A-16 | Project Closure | A-15 | FS |

---

### 5.5 Output of Activity Definition and Sequencing

The outputs of defining and sequencing activities include:
- A complete and structured **Activity List**
- Documented logical relationships between activities
- A clear linkage between activities and the **WBS hierarchy**

These outputs serve as direct inputs to:
- **Network Diagram development**
- **Estimating Activity Durations**
- **Project Schedule Development**
