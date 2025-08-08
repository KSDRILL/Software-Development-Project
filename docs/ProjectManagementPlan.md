# 📄 CMPG224 SOFTWARE PROJECT MANAGEMENT PLAN

### Project: Institutional Asset Management System

**Date**: August 2025  
**Version**: 1.0  
**Submitted in Partial Fulfillment of the Requirements of CMPG224**  
**North-West University, Mafikeng Campus**

---

## 🔹 1.0 Project Introduction

### 1.1 Project Title
**Institutional Asset Management System**

### 1.2 Project Purpose and Scope
The purpose of this system is to assist the institution in registering, tracking, updating, and disposing of laptops and computers. The users of the system will be administrative staff and IT personnel. The system ensures accurate and consistent records of all assets, promotes accountability, and simplifies auditing and reporting processes.

### 1.3 Definitions and Acronyms
* **SRS** – Software Requirements Specification
* **UI** – User Interface
* **DB** – Database
* **SPMP** – Software Project Management Plan
* **QA** – Quality Assurance

---

## 🔹 2.0 Project Organization

### 2.1 Organizational Structure
The project group uses a flat team structure, where each member has a clearly defined role and responsibility. Communication is maintained through regular group meetings, and all major decisions are made collectively.

### 2.2 Roles and Responsibilities
| Team Role            | Key Responsibilities                                                                  | Main Deliverables                                            |
| -------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Project Leader       | Coordinates group activities, ensures deadlines are met, communicates with supervisor | Project Proposal, Project Plan, Final Report & Presentation  |
| Analyst              | Gathers user requirements, analyzes system needs                                      | Software Requirements Specification (SRS)                    |
| System Designer      | Designs system structure, including architecture and diagrams                         | System Design Document (SDD)                                 |
| Data Engineer        | Designs and builds the database, handles data integration                             | Database part of SDD, Source Code, Deployment Guide, Testing |
| Developer            | Codes front-end and back-end functionalities based on system design                   | Source Code & User Interface                                 |
| Tester               | Develops test cases, executes tests, and reports bugs                                 | Test Plan, Test Results                                      |
| Documentation Writer | Prepares manuals, final report, and assists in compiling group documentation          | User Manual, Deployment Guide, Final Report                  |

---

## 🔹 3.0 Project Schedule

### 3.1 Work Plan

#### 3.1.1 Work Breakdown Structure
1. Project Proposal
2. Requirements Gathering
3. System and Database Design
4. Front-end and Back-end Development
5. Testing and Debugging
6. Documentation (Manuals, Final Report)
7. Presentation and Submission

#### 3.1.2 Project Schedule with Tasks and Dependencies
* Requirements must be finalized before system design begins
* Design must be completed before coding begins
* Testing is performed during and after development
* Documentation is created throughout development and testing
* Final report and presentation are completed after full testing and review

---

## 🔹 4.0 Technical Plan

### 4.1 Tools and Technologies
* **Programming Languages**: Python, HTML, CSS, JavaScript
* **Frameworks**: Flask (Backend), Bootstrap (Frontend)
* **Database**: MySQL or SQLite
* **Version Control**: Git and GitHub
* **Communication Tools**: WhatsApp, Google Meet
* **Project Management Tools**: Trello, Google Docs

### 4.2 Development Approach
The Agile methodology is adopted for this project. Work is divided into sprints. After each sprint, the group reviews progress, makes necessary changes, and plans for the next cycle. This iterative process promotes flexibility and continuous improvement.

---

## 🔹 5.0 Risk Management and Communication Plan

### 5.1 Risk Identification and Mitigation
| Risk                    | Probability | Impact | Mitigation Strategy                                 |
| ----------------------- | ----------- | ------ | --------------------------------------------------- |
| Member unavailability   | Medium      | High   | Assign backup members for critical tasks            |
| Programming errors/bugs | High        | High   | Regular testing and early bug reporting             |
| Miscommunication        | Medium      | Medium | Weekly meetings and written updates                 |
| Data loss or corruption | Low         | High   | Use GitHub for version control and automatic backup |
| Scope creep             | Medium      | High   | Stick to approved requirements and features only    |

### 5.2 Communication Strategy
* **Primary Tool**: WhatsApp Group (daily updates and communication)
* **Meetings**: Google Meet twice a week
* **Task Tracking**: Trello board or Google Docs
* **File Sharing**: Shared Google Drive
* **Version Control**: GitHub for managing and reviewing code changes

---

## 🔹 6.0 Test and Quality Assurance

### 6.1 Testing Plan
This project will follow **manual black-box testing**. Each function will be tested from the user’s point of view without knowledge of the internal code. The goal is to ensure that the system performs as expected based on the requirements.

**Features to be tested include**:
* User login and logout
* Registering new assets
* Updating and deleting assets
* Searching and filtering assets
* Generating PDF/CSV reports
* Role-based access control (Admin vs Viewer)

**Testing strategy includes**:
* Writing test cases for each feature
* Comparing expected output with actual output
* Recording results in a test log
* Fixing any bugs found before release

### 6.2 Version Control
GitHub is used for version control. Each developer creates their own branch for new features. Once complete, they submit a pull request for review and merge into the main branch. This prevents data loss, ensures collaboration, and tracks all code changes clearly.

---

## 🔹 7.0 Project Closure

### 7.1 Closeout Plan
Once all tasks are completed, the group will conduct a final review of the project. This includes checking if all requirements have been met, testing the system one last time, and finalizing the documentation and presentation.

### 7.2 Final Product Delivery and Acceptance
The final system, including all source code and documentation, will be submitted. A presentation will be held to demonstrate all system features. The supervisor will evaluate the project against the SRS and functionality.

### 7.3 Project Completion and Review
The group will reflect on the project process, identifying:
* What went well
* What could be improved
* Lessons learned in working as a team
  This helps improve future collaboration and project management skills.

---

## 🔹 Appendix

To be added:
* ERD (Entity Relationship Diagram)
* System wireframes or screenshots
* Sprint progress logs
* Testing checklist and bug reports

---

## 🔹 References

* Python Documentation
* Flask Documentation
* W3Schools (HTML, CSS, JS)
* GitHub Docs
* Stack Overflow (for code troubleshooting)
* Trello and Google Docs Help pages
