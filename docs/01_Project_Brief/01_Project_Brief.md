# SQL Tutor — Project Brief

## 1. Project Information

| Item | Details |
|---|---|
| Project Name | SQL Tutor |
| Full Project Name | SQL Tutor: An Interactive SQL Learning and Assessment Platform |
| Project Type | Final Year Capstone Project |
| Research Area | Database Systems and Technology-Enhanced Learning (TEL) |
| Target Platforms | Web Application and Android Application |
| Primary Users | Students, beginners, and learners developing SQL skills |
| Version | v1.0 |

---

## 2. Project Overview

SQL Tutor is an interactive learning and assessment platform designed to help learners develop practical SQL skills through structured learning content, hands-on SQL practice, automated assessment, and progress tracking.

The platform combines learning materials with an interactive SQL execution environment, allowing users to learn SQL concepts and immediately apply them through practical exercises and challenges.

The system will be developed as both a web application and an Android application, using a shared backend and database infrastructure.

---

## 3. Background

Structured Query Language (SQL) is a fundamental technology for working with relational databases and is widely used in software development, data analysis, database administration, and information systems.

Although many resources are available for learning SQL, learners often need to use separate platforms for studying concepts, practising queries, executing SQL, and assessing their understanding.

SQL Tutor aims to provide these activities within a single interactive learning environment.

---

## 4. Problem

Learners may understand SQL concepts theoretically but struggle to apply them when writing and executing queries.

Traditional learning resources may provide examples and exercises, but they do not always provide an integrated environment for:

- Learning SQL concepts
- Writing SQL queries
- Executing queries
- Receiving immediate evaluation
- Practising progressively difficult problems
- Tracking learning progress

This creates an opportunity for an integrated practical SQL learning and assessment platform.

---

## 5. Proposed Solution

SQL Tutor will provide a unified environment where learners can:

1. Study structured SQL lessons.
2. View SQL examples.
3. Write queries using an interactive SQL editor.
4. Execute queries against a controlled practice database.
5. Receive automated evaluation of submitted solutions.
6. Complete SQL challenges and assessments.
7. Track their learning progress.
8. Practise SQL using interview-style questions.

A secure SQL sandbox will be used to prevent learner queries from accessing or modifying application data.

---

## 6. Aim

The aim of the project is to design and develop an interactive SQL learning and assessment platform that combines structured learning, practical SQL execution, automated assessment, and learner progress tracking.

---

## 7. Objectives

The project objectives are to:

- Develop structured SQL learning modules.
- Provide an interactive SQL editor and execution environment.
- Implement a controlled SQL sandbox for practical exercises.
- Develop automated SQL query evaluation.
- Provide practical SQL challenges and assessments.
- Track learner progress and exercise performance.
- Develop a web-based learning platform.
- Develop an Android application using shared backend services.
- Implement appropriate security controls for user data and SQL execution.
- Evaluate the functionality and usability of the developed platform.

---

## 8. Target Users

The primary target users are:

- Students learning SQL.
- Beginners developing database skills.
- Learners preparing for SQL-related assessments.
- Learners preparing for SQL interviews.
- Early-stage developers and database practitioners seeking practical SQL practice.

---

## 9. Core Features

The initial version of SQL Tutor will include:

### User Management
- User registration
- User authentication
- Login and logout
- Basic user profile

### Learning
- Structured SQL modules
- Lessons
- SQL examples
- Practical exercises

### SQL Practice
- Interactive SQL editor
- Query execution
- Controlled SQL sandbox
- Query results
- SQL error handling

### Assessment
- SQL challenges
- Difficulty levels
- Automated query evaluation
- Assessments
- Attempt history

### Progress Tracking
- Lesson completion
- Exercise performance
- Topic-wise progress
- Overall progress

### Practice and Interview Mode
- SQL practice questions
- SQL interview-style questions
- Query submission and evaluation

### Platforms
- Web application
- Android application
- Shared backend services

---

## 10. Security Considerations

Security is an important part of the project because users will submit SQL queries to the application.

The system will consider:

- Secure authentication
- Authorization
- Password protection
- Input validation
- SQL injection prevention
- SQL execution restrictions
- Query timeout and resource controls
- Isolation of the SQL practice environment
- Protection of application data and credentials

Learner queries will be executed against controlled practice data rather than the application's primary data.

---

## 11. Technology Overview

The planned technology stack includes:

| Layer | Technology |
|---|---|
| Web Frontend | React + TypeScript |
| Mobile Application | Flutter + Dart |
| Backend | Python + FastAPI |
| ORM | SQLAlchemy |
| Database | PostgreSQL |
| SQL Sandbox | Isolated PostgreSQL environment |
| API | REST |
| Authentication | JWT-based authentication |
| Testing | Pytest, Postman and manual testing |
| UI/UX | Figma |
| Containerization | Docker |
| Version Control | Git and GitHub |
| Development Environment | Visual Studio Code |

---

## 12. Project Deliverables

The project will produce four primary outcomes:

### 1. Working Product
A functional SQL Tutor web and Android application implementing the defined v1.0 scope.

### 2. GitHub Repository
A structured repository containing source code, documentation, development history, testing evidence, and project assets.

### 3. Portfolio Case Study
A professional case study documenting the problem, research, UX process, technical architecture, implementation, testing, and final outcome.

### 4. Dissertation
A formal academic dissertation documenting the research, design, development, testing, evaluation, limitations, and conclusions of the project.

---

## 13. Project Methodology

The project will follow an iterative development approach.

The general development cycle will be:

**Research → Requirements → Design → Implementation → Testing → Evaluation → Improvement**

Development and documentation will occur in parallel to maintain traceability between project decisions, implementation, testing, and academic evidence.

---

## 14. Version 1.0 Scope

Version 1.0 focuses on the core learning and assessment functionality required to demonstrate the proposed system.

The following are outside the initial version:

- AI-assisted tutoring
- AI-generated questions
- Adaptive AI learning
- iOS application
- Public app-store publication
- Multiple SQL database engines
- Payment and subscription functionality
- Social/community features
- Multiplayer functionality
- Advanced gamification

These capabilities may be considered as future enhancements.

---

## 15. Expected Outcome

The expected outcome is a functional and tested interactive SQL learning platform that enables learners to study SQL concepts, practise queries in a controlled environment, complete practical assessments, and monitor their learning progress through web and Android interfaces.

The project will demonstrate the integration of database systems, backend development, application development, security, user experience design, automated assessment, and software testing within a single application.