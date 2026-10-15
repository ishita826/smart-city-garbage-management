# Software Requirements Specification (Initial Outline)

## 1. Introduction

### 1.1 Purpose
This document outlines the initial requirements for a Smart City Garbage Management System intended to support citizen reporting of uncollected garbage and authority-side monitoring.

### 1.2 Scope
The proposed system will provide a centralized way for citizens to submit garbage-related reports with location details. Authorized municipal personnel will be able to review reports and update their collection status.

The system is planned as a software-based solution. IoT sensors and automatic bin-level detection are outside the current scope.

## 2. User Classes

### Citizen
- Register and log in.
- Submit a report about uncollected garbage.
- Provide location information for the report.
- View the status of submitted reports.

### Authority / Administrator
- Log in to an authorized account.
- View submitted reports.
- Review report details and locations.
- Update collection status.
- Monitor reported and resolved complaints.

## 3. Functional Requirements (Proposed)

- **FR-01:** The system shall support user registration and login.
- **FR-02:** A citizen shall be able to submit a garbage report.
- **FR-03:** A report shall include location information and relevant descriptive details.
- **FR-04:** A citizen shall be able to view the status of a submitted report.
- **FR-05:** An authorized authority user shall be able to view submitted reports.
- **FR-06:** An authorized authority user shall be able to update a report's status.
- **FR-07:** The system shall provide a way to monitor report and collection progress.

These are proposed requirements and should be validated before implementation.

## 4. Non-Functional Requirements (Proposed)

- **Security:** Authentication and authorization should protect user and authority functions.
- **Performance:** Common actions should respond within an acceptable time under expected usage.
- **Reliability:** Reports should be stored consistently and remain available for authorized review.
- **Maintainability:** The system should be organized into modules to support future changes.

## 5. Proposed Technology

- Java
- Spring Boot
- A relational database (selection pending)
- Frontend technology (selection pending)

## 6. Constraints and Assumptions

- Citizens submit reports manually.
- Location details are supplied or confirmed by the user.
- Authority users are responsible for reviewing reports and updating status.
- No IoT bin sensors or automatic garbage detection are included in the current scope.
- Technology choices may be finalized during design.

## 7. Planned Development Phases

1. Requirement validation
2. System design and data-flow diagrams
3. Database design
4. Backend implementation
5. Frontend implementation
6. Integration and testing
7. Documentation and demonstration

## 8. Status

This is an initial requirements outline. It does not represent a completed or tested application.
