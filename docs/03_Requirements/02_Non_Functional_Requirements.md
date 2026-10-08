# Non-Functional Requirements

## 1. Introduction

Non-functional requirements define the quality attributes and operational constraints that SQL Tutor should satisfy.

These requirements focus on security, performance, usability, reliability, maintainability, and testability.

---

## 2. Security Requirements

### NFR-01 — Authentication Security

The system shall protect authenticated resources and shall not allow unauthenticated users to access protected functionality.

### NFR-02 — Authorization

The system shall verify that authenticated users are authorized to access the requested resources and operations.

### NFR-03 — SQL Injection Protection

The system shall implement appropriate controls to prevent SQL injection against the application and its database.

### NFR-04 — Sandbox Isolation

User-submitted SQL queries shall execute within a controlled and isolated environment rather than directly against the application's primary production data.

### NFR-05 — Sensitive Data Protection

Passwords and other sensitive information shall not be stored or transmitted insecurely.

---

## 3. Performance Requirements

### NFR-06 — Response Time

Normal application and API operations should return within an acceptable response time under the expected project workload.

### NFR-07 — Query Timeout

SQL queries shall have an execution time limit to prevent excessively long-running queries from affecting the system.

### NFR-08 — Resource Control

SQL execution shall have appropriate resource controls to reduce the risk of excessive CPU, memory, storage, or database resource consumption.

---

## 4. Usability Requirements

### NFR-09 — Ease of Use

The interface shall be understandable to learners with beginner-to-intermediate SQL knowledge.

### NFR-10 — Consistent Interface

The web and Android applications shall maintain consistent terminology, navigation concepts, and core workflows where practical.

### NFR-11 — Error Feedback

The system shall provide understandable feedback when an operation fails or a SQL query contains an error.

### NFR-12 — Error Recovery

Users should be able to recover from common errors without losing unrelated learning or progress information.

---

## 5. Reliability and Data Integrity

### NFR-13 — Data Integrity

The system shall maintain the consistency and integrity of user, learning, exercise, assessment, attempt, and progress data.

### NFR-14 — Reliable Operations

Important operations such as authentication, exercise submission, assessment, and progress recording shall handle failures without creating inconsistent records.

---

## 6. Maintainability

### NFR-15 — Modular Architecture

The system shall use a modular architecture that separates major application responsibilities such as authentication, learning content, SQL execution, assessment, and progress tracking.

### NFR-16 — Maintainability

The source code shall follow a consistent structure and coding practices that allow future modification and debugging.

### NFR-17 — Documentation

Important technical decisions, system components, APIs, security controls, and testing activities shall be documented.

---

## 7. Testability

### NFR-18 — Backend Testability

Backend functionality shall be designed so that important components can be tested independently.

### NFR-19 — API Testability

REST API endpoints shall be testable using automated and/or manual API testing tools.

### NFR-20 — Cross-Platform Validation

Core functionality shall be tested on both the web application and Android application.

### NFR-21 — Regression Testing

Previously working core functionality shall be re-tested after significant changes to reduce the risk of introducing regressions.

---

## 8. Scalability and Extensibility

### NFR-22 — Extensible Learning Content

The learning content structure should allow additional modules, lessons, exercises, and challenges to be added without major changes to the application architecture.

### NFR-23 — Extensible Assessment

The assessment architecture should allow additional challenge types and evaluation rules to be introduced in future versions.

### NFR-24 — Future Platform Extension

The backend API architecture should allow future client applications or platforms to consume the same services without requiring a complete redesign.

---

## 9. Version 1.0 Quality Expectations

Before Version 1.0 is considered complete, the system should satisfy the following quality expectations:

- Core functionality works as intended.
- Critical authentication and authorization flows are tested.
- SQL execution is isolated and controlled.
- SQL injection risks are tested.
- Query execution limits are enforced.
- Important API endpoints are tested.
- Web functionality is tested.
- Android functionality is tested.
- Important defects are resolved or documented.
- User and progress data remain consistent.
- Technical documentation is maintained.
- Evidence of implementation and testing is captured.

---

## 10. Requirement Traceability

Non-functional requirements shall follow the same traceability approach as functional requirements:

**Requirement → Design Decision → Implementation → Test → Evidence → Thesis**

This provides evidence that quality and security requirements were considered throughout the development lifecycle.