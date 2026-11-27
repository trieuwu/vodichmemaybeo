## 1. Business Background

Bank X is a fictional Vietnamese commercial bank that serves individual customers and SMEs. The bank offers business loans through its branch network and online banking platform. Although Bank X has digitized much of its credit application process, customers continue to report difficulties preparing documentation, submitting applications, and obtaining updates.

The bank's management believes that improving this experience could increase customer satisfaction, reduce unnecessary operational work, and make its services more accessible. However, management is uncertain which problem should receive priority and whether improvements should involve automation, artificial intelligence, process redesign, or a combination of approaches.

Bank X has adopted Scrum for digital product development. Management expects the assigned Scrum Team to use an iterative, evidence-based approach to identify a valuable improvement, deliver usable product Increments, and adapt to feedback.

**Your challenge:**

How might Bank X redesign its SME credit application experience to reduce unnecessary customer effort and operational inefficiencies, while using Scrum to deliver and validate a creative, feasible solution? Your Scrum Team has 8 weeks, organized into 4 two-week Sprints, to prepare a feasible MVP for a controlled pilot.

Your team is not required to improve every stage of the journey. You must prioritize the most valuable opportunity and demonstrate how your solution could be developed incrementally.

### *Instructions*

* Teams must submit one coordinated response addressing all four parts.
* **Maximum of 6 pages.** If teams go over this limit, content beyond page 6 will not be graded.
* All recommendations must relate to the same selected product or service improvement.
* Use supplied evidence and respect all implementation constraints.
* Do not use videos, GIFs, and embedded objects, as they cannot be reliably inserted into a .docx file
* Tables, charts, wireframes/mockups, roadmaps, and similar visuals are allowed to better present your ideas. Visuals are not scored for design quality, and all tables and figures must be readable at 100% zoom.
* Coding is not required.
* There is no mandatory solution or technology choice.

### *Submission Requirements*

* 1 file in .docx format, with a limit of **5 MB**.
* References are not required; cite case data inline (e.g., Exhibit A, Section 6). If external sources are used, list them briefly at the end (maximum 5 entries; not counted toward the page limit). Appendices are not allowed.
* Format: A4, Times New Roman 12 pt, 1.5 line spacing, margins 2–2.5 cm. Tables may use single spacing and 10–11 pt font.
* File name: `Team Name_Round 1` (e.g., `Agile Eagles_Round 1.docx`).
* Any answer file not uploaded when the system automatically submits at 120 minutes will not be graded, unless an upload failure has been reported as described in the Candidate Booklet.

---

## 2. Current Customer Journey

Bank X's current application process consists of five major stages.

| Stage | Customer and employee activities | Observed difficulties |
| :--- | :--- | :--- |
| **1. Discover requirements** | SME owners review loan information and document requirements through the bank's website or branch advisors. | Requirements vary by loan product and business profile. Some customers struggle to determine which documents apply to them. |
| **2. Prepare and upload documents** | Applicants prepare supporting documents, upload them through the portal, and submit their applications. | Some attachments are missing, unreadable, or incorrectly categorized. |
| **3. Completeness verification** | Bank employees review submissions and request corrections where necessary. | Applicants may receive follow-up requests after submission and need to upload additional documents. |
| **4. Track application progress** | Applicants wait for updates and contact customer support or relationship managers when necessary. | Status information is limited, leading to repeated inquiries and uncertainty. |
| **5. Initial document review** | Credit operations employees examine submitted documents and manually enter relevant information into internal systems. | Repetitive data entry and document verification consume employee time. Possible risk of human error in the entry process. |

The process ends with an initial document review. Formal credit assessment and final lending decisions take place afterward and are outside the scope of this challenge.

---

## 3. Target Users and Stakeholders

| Users / Stakeholders | Needs |
| :--- | :--- |
| **Primary customer (SME owner)** | Small-business owners seeking financing for their business operations. They may have limited familiarity with banking documentation and prefer minimizing administrative work. |
| **Returning customer (Experienced SME borrower)** | An applicant who has previously completed a credit application and may already be familiar with the bank's requirements. |
| **Relationship Manager / Customer Support employee** | Assists applicants, answers questions, and coordinates follow-up requests. |
| **Credit Operations employee** | Checks submitted documentation, records information, and identifies missing or inconsistent materials. |
| **Bank Management** | Seeks to balance customer experience, operational efficiency, implementation costs, and compliance obligations. |

---

## 4. Operational Data

The following figures represent **01 typical month** of Bank X's operations.

### Exhibit A - Application Processing

| Metric | Value |
| :--- | :--- |
| Credit applications received | 1,200/month |
| Applications requiring missing-document follow-up | 780 (65%) |
| Affected applications corrected within one working day | 68% |
| Average staff time per follow-up (contacting the applicant and re-checking the resubmission) | 10 minutes |
| Median duration from initial submission to completion of initial document review - all applications | 7 working days |
| Median duration — applications without follow-up | 4 working days |
| Median duration — applications with follow-up | 8 working days |
| Applications initiated on mobile devices | 78% |

Applications requiring follow-up generally take longer to process. However, other factors may also contribute to these delays, so it is unclear how much processing time could be saved through automation.

### Exhibit B - Customer Segmentation

| Segmentation | Monthly applications | Requiring missing-document follow-up |
| :--- | :--- | :--- |
| First-time applicants | 800 | 75% |
| Returning applicants | 400 | 45% |
| Total | 1,200 | 65% |

### Exhibit C - Application Status and Support

| Metric | Value |
| :--- | :--- |
| Status-related customer inquiries | 400/month |
| Average employee handling time per inquiry | 5 minutes |
| Inquiries identified as repeated status requests within seven days | 26% |
| General mobile banking app sessions, across all banking services | 21,000/month |

A separate convenience survey found that 21 of 25 respondents were interested in receiving proactive application status notifications.

However, the survey's small sample size and recruitment method limit how confidently its findings can be generalized to all applicants.

### Exhibit D - Document Review Operations

| Metric | Value |
| :--- | :--- |
| Average initial review time | 12 minutes/application |
| Total initial review effort | 240 staff-hours/month |
| Share of review time spent on manual data transcription | 35% |
| Uploaded documents consisting of image-based scans or photographs | 41% |

Bank X previously tested an AI-based document classification prototype that correctly classified 48 of 50 clean, digitally generated test documents, equivalent to 96% accuracy. However, it has not been adequately evaluated on real-world document scans, photographs, corrupted files, or incomplete submissions.

---

## 5. Existing Systems and Service Capabilities

Bank X currently operates the following systems:

| System/capability | Current state |
| :--- | :--- |
| Online application portal | Supports authenticated users, application submission, basic draft saving, and document uploads. |
| Document storage | Secure storage for uploaded supporting documents. |
| Accepted document formats | PDF, JPG/JPEG, and PNG, with a maximum size of 10 MB per file. |
| Document requirements | Maintained internally and varies according to loan product and applicant characteristics. |
| Basic validation | Checks file format and size, but does not comprehensively verify whether all required documents have been attached. |
| Application status system | Tracks application progress internally. Limited status information is exported to the customer-facing system once daily. |
| Customer communications | Supports transactional emails. Additional notification channels require assessment. |
| AI document classification | Experimental prototype only. Production readiness has not been established. |
| Credit approval | Operates through a separate controlled process that cannot be modified within this project. |

Teams may recommend improvements to existing systems, new lightweight capabilities, staff-assisted processes, or combinations of these approaches.

---

## 6. Team Capacity and Constraints

### Delivery capacity (fixed)

| Resource | Availability |
| :--- | :--- |
| Product Owner | 1, full-time |
| Scrum Master | 1, full-time |
| Software Developers | 2, full-time |
| QA engineer | 1, at 50% (about 5 working days per Sprint) |
| Business Analyst | 1, full-time |
| Bank Operations employees (relationship managers and credit operations) | Up to 2 hours per week in total, for consultation, feedback, and usability sessions |

### Scrum delivery arrangement

* The bank has approved an 8-week development window, organized into **4 two-week Sprints**. The 8 weeks include validation and preparation for a controlled pilot.
* The Scrum Team must work toward a clear Product Goal.
* A usable product Increment satisfying the Definition of Done is expected every Sprint. An Increment does not need to be released to customers immediately.
* Sprint Reviews involve appropriate bank stakeholders and may result in Product Backlog adjustments.
* Sprint Retrospectives are used to identify improvements to the team's way of working.
* A controlled customer pilot may begin after the 4th Sprint if the solution satisfies the bank's release requirements.

### Implementation constraints

| Constraint | Requirement |
| :--- | :--- |
| **Decision authority** | The Product Owner may adjust the order and scope of Product Backlog items as new evidence emerges. The team cannot extend the deadline or increase its delivery capacity. |
| **Existing infrastructure** | Teams should reuse existing systems where practical. |
| **Security** | Customer documents must remain within approved environments, with appropriate authorization and access controls. |
| **External services** | New third-party services and production AI integrations require security and compliance approval from bank management; approval within 8 weeks is not guaranteed. |
| **Launch requirement** | A security review and critical functionality testing must be completed before the pilot. |

---

## 7. Additional Scenario

Assume that your Scrum Team has completed its 2nd Sprint and demonstrated an early Increment of your proposed solution to bank stakeholders.

During the Sprint Review, two important developments emerge.

### *Development 1: Unexpected user feedback*

*In a small usability evaluation involving 8 intended users, 5 participants struggled to understand what action they should take next after interacting with the early Increment. The observations suggest a potential usability issue, but the sample is too small to establish how widespread the problem is.*

### *Development 2: New stakeholder request*

*A senior business stakeholder requests that the team introduce an additional AI-powered customer assistant before the 8-week pilot, believing that it would improve customer experience. However, this capability was not included in the initial MVP scope. Production approval for a new AI integration is not guaranteed within the remaining two Sprints.*

The delivery deadline, team capacity, and security requirements **remain unchanged**.

The Product Owner must determine how these findings and requests should influence the Product Backlog and future work.

---

# Your Assignment

Your team must submit **ONE integrated proposal**, covering the following parts. You may focus on any significant problem in the customer journey, provided your decision is supported by the evidence.

Reasonable assumptions are allowed but must be identified clearly. No coding or diagram creation is required.

### Part 1: Problem Identification & Product Goal

Identify **ONE problem** your team would prioritize within Bank X's SME credit application journey.

Your response must:

1. Identify the affected users and define the selected problem.
2. Support the prioritization with at least 2 relevant pieces of evidence.
3. Define one **Product Goal** that describes the desired future outcome and one important assumption requiring validation.

### Part 2: Creative Service Redesign

Propose an innovative service improvement that addresses your selected problem.

Your response must:

1. Describe the proposed solution and the value it creates for customers or employees.
2. Explain the redesigned workflow, identifying what changes from the current experience.
3. Explain how the proposal addresses the underlying problem.

Teams may propose either AI-based or non-AI-based solutions, which may involve automation, new or improved digital features, operational process improvements, or a combination of these approaches. Creativity will be evaluated based on the solution's relevance, effectiveness, and ability to address the identified problem, rather than the technology used.

### Part 3: Scrum-Based MVP Planning & Execution

Develop a delivery proposal covering the following:

#### A. Product Backlog

Define **4 prioritized Product Backlog items** for your solution.

For each item, provide:

1. A short description of the capability or work.
2. The customer or business value it contributes.
3. Its relative priority.

For the highest-priority item, provide one specific, testable acceptance criterion.

#### B. Incremental Delivery

In Scrum, each Sprint Goal is set during that Sprint's Sprint Planning. Your plan should therefore:

1. Explain what usable Increment or improvement the team expects to demonstrate after each Sprint.
2. State a Sprint Goal for Sprint 1 and a forecast objective for Sprints 2–4, recognizing that these will be refined as the team learns.
3. Account for implementation, testing, dependencies, the stated team capacity, and the fixed eight-week deadline.

The team is not expected to commit to a fixed 8-week Sprint Backlog in advance.

#### C. Definition of Done

Propose at least 3 relevant quality conditions that all completed product work must satisfy to qualify as part of a usable Increment.

#### D. Feasibility and Scope

Identify the key implementation dependencies or risks (1–3 risks), ranked by importance, and explain how the most critical one would be managed. Identify at least 1 feature to defer beyond the MVP and explain why.

*Suggested format: Compact tables and short explanations.*

### Part 4: Inspection, Adaptation, and Validation

Consider the new information introduced during the 2nd Sprint Review in Section 7.

Your response must:

1. Explain how the Product Owner should respond to the two developments in Section 7, how this decision protects the Product Goal, and what it means for the remaining two Sprints.
2. Define 2 measurable success indicators, including a target and evaluation period, and one critical test or release condition before the controlled pilot.
