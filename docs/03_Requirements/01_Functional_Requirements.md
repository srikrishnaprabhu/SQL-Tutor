# Functional Requirements

## 1. Introduction

Functional requirements define the functions and capabilities that SQL Tutor must provide to users.

The requirements cover user management, SQL learning, SQL execution, assessment, progress tracking, interview practice, and application platforms.

---

## 2. User Management

### FR-01 — User Registration

The system shall allow a new user to create an account using the required registration information.

### FR-02 — User Login

The system shall allow registered users to authenticate using their credentials.

### FR-03 — User Logout

The system shall allow authenticated users to securely log out of the application.

### FR-04 — User Profile

The system shall allow authenticated users to view and manage basic profile information.

---

## 3. Learning Content

### FR-05 — SQL Modules

The system shall provide structured SQL learning modules.

### FR-06 — Lessons

Each module shall contain lessons covering specific SQL concepts.

### FR-07 — Examples

The system shall provide SQL examples relevant to the concepts being taught.

### FR-08 — Exercise Access

The system shall allow users to access practical SQL exercises associated with learning content.

### FR-09 — Completion Tracking

The system shall record whether a user has completed applicable lessons or exercises.

---

## 4. SQL Practice Environment

### FR-10 — SQL Editor

The system shall provide an interactive SQL editor for entering SQL queries.

### FR-11 — Query Execution

The system shall allow users to submit permitted SQL queries for execution within the controlled SQL environment.

### FR-12 — Result Display

The system shall display the results of successfully executed SQL queries.

### FR-13 — Error Handling

The system shall display meaningful error information when a query cannot be executed.

### FR-14 — Query Restrictions

The system shall restrict SQL operations that are not permitted within the educational execution environment.

### FR-15 — Execution Controls

The system shall apply execution controls such as query timeout and resource limitations.

---

## 5. SQL Challenges and Assessment

### FR-16 — Challenges

The system shall provide practical SQL challenges for users to solve.

### FR-17 — Difficulty Levels

Challenges shall be organized according to defined difficulty levels.

### FR-18 — Query Submission

The system shall allow users to submit SQL solutions for challenges.

### FR-19 — Automated Evaluation

The system shall automatically evaluate submitted queries against predefined expected outcomes.

### FR-20 — Result Feedback

The system shall inform users whether their submitted solution meets the expected result.

### FR-21 — Attempt History

The system shall record relevant information about previous challenge attempts.

---

## 6. Progress Tracking

### FR-22 — Progress Dashboard

The system shall provide a dashboard showing the user's learning progress.

### FR-23 — Topic Progress

The system shall track progress for relevant SQL topics.

### FR-24 — Performance Information

The system shall provide information about exercise and challenge performance.

### FR-25 — Overall Progress

The system shall calculate and display an overall learning progress indicator.

---

## 7. Practice and Interview Mode

### FR-26 — Practice Mode

The system shall provide a dedicated SQL practice experience.

### FR-27 — Interview Questions

The system shall provide SQL questions designed to simulate interview-style practice.

### FR-28 — Interview Evaluation

The system shall evaluate applicable SQL responses and record the resulting performance.

---

## 8. Application Platforms

### FR-29 — Web Application

The system shall provide the core SQL Tutor functionality through a web application.

### FR-30 — Android Application

The system shall provide the core SQL Tutor functionality through an Android application.

### FR-31 — Shared Backend

The web and Android applications shall communicate with the shared backend API and access the same user and learning data.

---

## 9. Requirement Priority

The following priority levels will be used during implementation:

| Priority | Meaning |
|---|---|
| High | Required for Version 1.0 |
| Medium | Important but may be simplified if necessary |
| Low | Can be deferred without affecting the core system |

All core authentication, learning, SQL execution, assessment, progress tracking, backend integration, security, and platform requirements are considered **High priority** for Version 1.0.

---

## 10. Requirement Traceability

Each functional requirement should eventually be traceable through the development lifecycle:

**Requirement → Feature → Implementation → Test → Evidence → Thesis**

This ensures that the final implementation can be demonstrated and academically documented.