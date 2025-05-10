## 📘 Requirement Analysis in Software Development

This repository is dedicated to exploring and documenting the **Requirement Analysis phase** in the **Software Development Life Cycle (SDLC)**. Requirement analysis is a critical early stage where business needs are gathered, analyzed, and clearly defined to ensure the success of a software project.

The purpose of this repository is to:

* Explain the importance of requirement analysis in SDLC.
* Provide templates, examples, and best practices for effective requirement gathering.
* Serve as a reference for developers, analysts, and students to understand how clear, complete, and validated requirements contribute to building robust and scalable software solutions.

---
## What is Requirement Analysis?

**Requirement Analysis** is the second phase of the Software Development Life Cycle (SDLC), following the **Planning phase**. It involves the process of **gathering, analyzing, validating, and documenting** the functional and non-functional requirements of the software to be developed.

During this phase, stakeholders—including clients, users, project managers, and developers—collaborate to define:

* **What the software should do** (functional requirements),
* **How well it should perform** (non-functional requirements),
* **Constraints and assumptions**, and
* **Business rules and dependencies**.

---

## 🔍 **Key Activities in Requirement Analysis**

* **Requirement Gathering**
   Collecting needs from various stakeholders through interviews, questionnaires, meetings, observation, and document analysis.

* **Requirement Elicitation**
   Clarifying and expanding on stakeholder needs to uncover implicit or hidden requirements.

* **Requirement Analysis & Prioritization**
   Analyzing feasibility, consistency, and completeness of the requirements. Identifying conflicting requirements and prioritizing them.

* **Requirement Specification**
   Documenting all validated requirements in a **Software Requirements Specification (SRS)** document.

* **Requirement Validation**
   Ensuring the documented requirements meet stakeholder expectations and are achievable, testable, and aligned with the project’s goals.

---

## ⭐ **Why is Requirement Analysis Important?**

1. ### ✅ **Defines the Project Scope**

   * Provides a clear boundary of what will and won’t be developed.
   * Helps prevent scope creep and keeps the project focused.

2. ### 🚀 **Ensures Stakeholder Alignment**

   * Ensures all parties (users, developers, testers, business analysts) have a shared understanding.
   * Minimizes miscommunication and unmet expectations.

3. ### 💸 **Reduces Development Costs and Rework**

   * Detecting errors or gaps in requirements early is significantly cheaper than fixing them in later stages.
   * Prevents costly redesigns or delays due to misunderstood requirements.

4. ### 🛠️ **Guides Design and Development**

   * Acts as a blueprint for developers and system architects.
   * Clarifies what features and functions need to be implemented.

5. ### 🔍 **Enables Effective Testing**

   * Provides a baseline for writing test cases and acceptance criteria.
   * Makes verification and validation of the software more structured.

6. ### 📊 **Improves Project Success Rate**

   * Accurate and well-defined requirements are directly linked to successful project delivery.
   * Reduces the risk of project failure due to incomplete or inaccurate requirements.

---

## 📘 **Common Tools & Techniques Used**

* **Techniques:** Use cases, user stories, interviews, brainstorming, SWOT analysis, prototyping.
* **Tools:** JIRA, Confluence, Lucidchart, Draw\.io, Microsoft Visio, Balsamiq, etc.

---

## 🧾 **Deliverables of the Requirement Analysis Phase**

* Software Requirements Specification (SRS) Document
* Use Case Diagrams
* Functional and Non-Functional Requirements List
* Wireframes or Prototypes (optional)
* Requirements Traceability Matrix (RTM)

---

## **Types of Requirements.**


## 🔍 **1. Requirement Gathering**

### 🟢 Functional Requirements (FR)

These define **what** the system should do.

**Examples:**

* Users must be able to **create accounts** using email and password or third-party auth (e.g., Google).
* Hosts should be able to **list properties** with descriptions, photos, pricing, and availability.
* Guests must be able to **search for properties** based on location, price range, and dates.
* Users should be able to **book a stay** and receive a confirmation email.
* Admins must be able to **view and manage all bookings, users, and listings**.

### 🟡 Non-Functional Requirements (NFR)

These define **how well** the system performs its functions.

**Examples:**

* The system should handle **up to 10,000 concurrent users**.
* The search functionality must return results **within 2 seconds**.
* The platform must be **available 99.9% of the time** (high availability).
* The app must be **responsive across devices** (mobile, tablet, desktop).
* All data must be **encrypted using SSL/TLS** protocols.

---

## 🤝 **2. Requirement Elicitation**

### 🟢 Functional Requirements

* Host dashboard must allow users to **edit or delete listings**.
* Users must be able to **rate and review** properties after checkout.
* There must be a feature to **message hosts** before making a booking.

### 🟡 Non-Functional Requirements

* The messaging feature must have **real-time delivery** with **<1s latency**.
* User interactions should be tracked for **analytics and behavior monitoring**.
* The system should comply with **GDPR** for users in Europe.

---

## ⚙️ **3. Requirement Analysis & Prioritization**

### 🟢 Functional Requirements

* Payment integration must support **Stripe or PayPal**.
* Users should be able to **filter properties by amenities** (e.g., Wi-Fi, parking).
* Users should receive **booking reminders and cancellation policies** via email.

### 🟡 Non-Functional Requirements

* Payments must be **PCI DSS compliant**.
* High-priority features (search, booking) should have **99.99% uptime SLA**.
* System must be **scalable to accommodate regional growth**.

---

## 📝 **4. Requirement Specification**

### 🟢 Functional Requirements

* Property listing form must include fields for title, description, images, nightly rate, and rules.
* Booking form must capture check-in/check-out dates, guest count, and payment details.
* Admin panel must provide **filtering, reporting, and user management** options.

### 🟡 Non-Functional Requirements

* UI/UX must follow **WCAG 2.1 accessibility standards**.
* Data must be backed up **every 24 hours**.
* Platform should support **multi-language support (English, Spanish, French)**.

---

## ✅ **5. Requirement Validation**

### 🟢 Functional Requirements

* Confirm with stakeholders that **search and filter logic** matches expected user journey.
* Review wireframes to validate the **booking flow** and **checkout steps**.
* Confirm that users can **cancel bookings** and receive refunds per policy.

### 🟡 Non-Functional Requirements

* Validate **performance benchmarks** via load testing (e.g., booking within 3s).
* Confirm security measures with penetration testing (e.g., XSS/SQL injection prevention).
* Ensure **mobile compatibility** across major browsers and OS versions.

---

## **Use Case Diagrams.**

### 📘 **What are Use Case Diagrams?**

A **Use Case Diagram** is a type of **Unified Modeling Language (UML)** diagram used to visually represent the **functional requirements** of a system from the user's perspective. It shows **interactions** between external users (**actors**) and the system to achieve a specific goal (**use cases**).

In simple terms, it answers:

* **Who** will use the system? (actors)
* **What** will they do with it? (use cases)

---

### 🧩 **Basic Components of a Use Case Diagram**

| Element             | Description                                                                                |
| ------------------- | ------------------------------------------------------------------------------------------ |
| **Actor**           | A user or external system that interacts with the system (e.g., Guest, Host, Admin)        |
| **Use Case**        | A specific action or function performed in the system (e.g., Book Property, List Property) |
| **System Boundary** | A box that defines the scope of the system                                                 |
| **Relationships**   | Connections between actors and use cases (`include`, `extend`, or direct association)      |

---

### ✨ **Benefits of Use Case Diagrams**

1. ### ✅ **Clear Visualization of System Behavior**

   * Helps stakeholders understand how users will interact with the system.
   * Makes it easier to explain features to non-technical clients or team members.

2. ### 🧠 **Helps Identify Functional Requirements**

   * A structured way to define what the system **must do** based on user actions.
   * Ensures all user needs are captured.

3. ### 👥 **Defines User Roles and Responsibilities**

   * Clarifies which user (actor) is responsible for which actions in the system.
   * Useful for role-based access control design.

4. ### 🔍 **Aids in Requirement Validation**

   * Makes it easier to confirm with stakeholders whether the use cases match real-world expectations.
   * Can reveal missing or redundant functionality early.

5. ### 🧪 **Foundation for Test Case Design**

   * Each use case can be directly translated into **test scenarios** for QA and UAT (User Acceptance Testing).

6. ### 🚀 **Improves Communication Among Teams**

   * Provides a shared visual reference for **developers, designers, testers, and clients**.
   * Reduces ambiguity and misinterpretation of requirements.

---

### 🏡 Example (StayEase - Airbnb Clone)

![Screenshot from 2025-05-10 21-56-37](https://github.com/user-attachments/assets/abff45b0-f740-4541-a6be-367becf450d2)
