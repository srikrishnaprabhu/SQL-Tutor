# Project Scope

## 1. Scope Overview

SQL Tutor is an interactive SQL learning and assessment platform designed to help learners understand SQL concepts through structured lessons, practical exercises, query execution, automated assessment, and progress tracking.

Version 1.0 will provide a web application and Android application connected to a shared backend and database.

The project focuses on SQL learning and practical assessment rather than providing a complete database administration or enterprise database management platform.

---

## 2. In-Scope Features

### 2.1 User Management

- User registration
- User login and logout
- Secure password storage
- Basic user profile
- Authentication and authorization

### 2.2 SQL Learning

- Structured SQL learning modules
- Lessons organized by difficulty
- SQL explanations and examples
- Practical exercises
- Beginner-to-intermediate learning progression

### 2.3 SQL Practice Environment

- Interactive SQL editor
- Query submission
- SQL query execution
- Query result display
- SQL error handling
- Controlled database datasets
- Query execution restrictions
- Query timeout and resource controls

### 2.4 SQL Assessment

- Practical SQL challenges
- Difficulty levels
- Predefined expected outcomes
- Automated query evaluation
- Correct/incorrect results
- Basic feedback
- Attempt history

### 2.5 Progress Tracking

- Lesson completion
- Exercise attempts
- Correct and incorrect attempts
- Topic-level progress
- Overall learning progress
- Performance information

### 2.6 Practice and Interview Mode

- SQL practice questions
- Interview-style SQL questions
- Query-based evaluation
- Results and attempt tracking

### 2.7 Web Application

The web application will provide access to:

- Authentication
- Dashboard
- Learning modules
- Lessons
- SQL playground
- Exercises
- Challenges
- Assessments
- Progress tracking
- Interview practice

### 2.8 Android Application

The Android application will provide access to the core SQL Tutor learning and practice functionality through a mobile interface.

The Android application will use the same backend APIs and database as the web application.

### 2.9 Security

Security is included as a core part of the system.

The project will include:

- Password hashing
- JWT-based authentication
- Authorization controls
- Input validation
- SQL injection prevention
- SQL execution restrictions
- Sandbox isolation
- Query timeout controls
- Resource limitations
- Secure handling of sensitive information

### 2.10 Testing

Testing will cover:

- Functional testing
- API testing
- Integration testing
- SQL execution testing
- Security testing
- Web application testing
- Android application testing
- Usability testing
- Regression testing

---

## 3. Out of Scope for Version 1.0

The following features are intentionally excluded from the first release to maintain a realistic project scope.

### 3.1 Artificial Intelligence

The following are excluded from Version 1.0:

- AI tutor
- AI-generated SQL questions
- AI-generated explanations
- AI-based adaptive learning
- AI-based personalized recommendations
- AI-based SQL correction

These may be considered as future enhancements.

### 3.2 Additional Platforms

- iOS application
- Public Play Store release
- Desktop application

The Version 1.0 mobile target is Android.

### 3.3 Multiple Database Engines

Version 1.0 will primarily use PostgreSQL.

Support for other database systems such as:

- Microsoft SQL Server
- MySQL
- Oracle Database
- SQLite

is outside the initial scope.

### 3.4 Commercial Features

The following are excluded:

- Payments
- Subscription management
- Premium accounts
- Advertising
- Commercial marketplace functionality

### 3.5 Social and Multiplayer Features

The following are excluded:

- Social profiles
- User-to-user messaging
- Multiplayer competitions
- Public leaderboards
- Community forums
- Social sharing

### 3.6 Advanced Gamification

Advanced gamification features such as:

- Complex achievement systems
- Virtual currencies
- Rewards marketplaces
- Multiplayer competitions

are outside Version 1.0.

---

## 4. Technical Scope

### Frontend

- React
- TypeScript

### Mobile

- Flutter
- Dart
- Android

### Backend

- Python
- FastAPI
- REST APIs

### Database

- PostgreSQL
- SQLAlchemy

### SQL Execution

- Isolated PostgreSQL sandbox
- Controlled query execution
- Query restrictions
- Timeout and resource controls

### Authentication

- JWT-based authentication
- Secure password hashing

### Development and Testing

- Git
- GitHub
- Docker
- VS Code
- Pytest
- Postman
- Figma

---

## 5. Platform Integration Scope

The web and Android applications will communicate with the same backend API.

The backend will provide centralized access to:

- User accounts
- Learning content
- Exercises
- SQL execution
- Assessment
- Attempt history
- Progress data

This allows the same learner account and learning data to be accessed across supported platforms.

---

## 6. Security Boundary

SQL Tutor will allow users to execute SQL queries for educational purposes.

Because users submit SQL statements, the execution environment will be isolated and controlled.

The system will therefore apply:

- Query validation
- Allowed-operation restrictions
- Execution time limits
- Resource limits
- Sandbox isolation
- Authentication and authorization

The SQL execution environment will not provide unrestricted access to the application's production database.

---

## 7. Version 1.0 Boundary

Version 1.0 is considered complete when the following are available and functioning together:

1. User authentication
2. Structured SQL learning content
3. SQL exercises
4. Interactive SQL editor
5. Controlled SQL execution
6. Automated assessment
7. Attempt history
8. Progress tracking
9. Web application
10. Android application
11. Shared backend and database
12. Required security controls
13. Testing and bug fixing
14. Project documentation

Additional features will be considered only after the Version 1.0 scope is stable.

---

## 8. Future Enhancements

Potential future versions may include:

- AI-assisted SQL tutoring
- AI-generated practice questions
- Adaptive learning
- Additional SQL database engines
- iOS application
- Public Play Store deployment
- Advanced gamification
- Expanded interview preparation
- Personalized learning recommendations

These features are not required for the Version 1.0 academic implementation.