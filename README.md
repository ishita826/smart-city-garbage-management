# Smart City Garbage Management System

A proposed software-based system to help citizens report uncollected garbage and help municipal authorities monitor reports and update collection status.

> **Project status:** Planning and documentation stage. The application code has not been implemented yet.

## Problem Statement

Uncollected garbage can create unhygienic public spaces and make it difficult for authorities to track and prioritize complaints. This project proposes a centralized system through which citizens can submit garbage reports with location details and authorities can monitor and manage those reports.

## Proposed Objectives

- Allow users to register and log in.
- Allow citizens to report uncollected garbage and provide its location.
- Let authorities review submitted reports.
- Track report and collection status.
- Provide an overview of reported and resolved complaints.

## Planned User Roles

- **Citizen:** Create an account, submit a report, and view its status.
- **Authority/Admin:** Review reports, manage their status, and monitor collection progress.

## Planned Technology Stack

- **Language:** Java
- **Backend:** Spring Boot
- **Database:** To be selected / finalized
- **Frontend:** To be finalized

The stack and design may be refined during implementation.

## Current Progress

- [x] Project idea and problem statement
- [x] Initial requirements / SRS planning
- [ ] Detailed system design and DFDs
- [ ] Database schema
- [ ] Frontend implementation
- [ ] Spring Boot backend and APIs
- [ ] Database integration
- [ ] Testing and screenshots

Checkboxes indicate current project progress, not guaranteed features.

## Repository Structure

```text
smart-city-garbage-management/
├── README.md
├── .gitignore
└── docs/
    └── SRS.md
```

As development progresses, source code, diagrams, screenshots, and setup instructions will be added.

## Documentation

See [`docs/SRS.md`](docs/SRS.md) for the initial requirements outline.

## Scope and Limitations

This project is intended as a software-based reporting and monitoring system. It does not currently include IoT-enabled smart bins or automatic sensor-based garbage detection. Reports are intended to be submitted by users and reviewed by authorities.

## How to Run

There is no runnable application yet because implementation has not started. Instructions for building and running the system will be added after the source code is available.

## Future Work

1. Finalize functional and non-functional requirements.
2. Design the database and application architecture.
3. Implement authentication and role-based access.
4. Build report submission and status-tracking features.
5. Add authority-side report management.
6. Test the system and document setup steps.

## Contributions / Feedback

Suggestions about requirements, usability, and system design are welcome.

---
*This README describes the planned system and current progress; it does not claim that the listed features are already implemented.*
