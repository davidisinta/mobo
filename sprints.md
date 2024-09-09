# Project Sprint Plan - [Mobo]

---

## Project Overview
- **Project Name:** [Mobo]
- **Start Date:** [Sep 8]
- **End Date:** [Nov 9]
- **Project Goal:** [Gym progress tracker and AI powered workout suggestions]

# High-Level Sprint Planning

### Plan the Core Architecture:
- Design the app in a modular way with REST APIs, so the backend (Spring Boot) can handle all business logic, while the front-end (mobile or web) communicates via APIs.
- Use Spring Security for user authentication and role-based access (e.g., admin for managing exercises).

### Set Up a Reliable Database:
- Use Spring Data JPA for relational databases or Spring Data MongoDB for NoSQL databases. Ensure the user, workout, exercise, and progress data are efficiently stored.
- Build out the database schema first, allowing for flexibility in expanding features (e.g., adding nutrition tracking later).

### Create a Fluid and Intuitive UI:
- Ensure the user interface is intuitive, especially for logging workouts and tracking progress.
- Use front-end frameworks like React.js or Angular for dynamic, responsive UIs.

### Test with Real Users:
- Collect feedback from gym-goers, fitness enthusiasts, or personal trainers to improve usability and features.
- Perform user testing with different fitness levels to ensure the app caters to both beginners and experienced users.


---

# Sprints Overview

### Sprint 1 - [CRUD] - [Sep 8th] to [Sep 24th]
#### Sprint Goal
- Build & Deploy the API to azure with basic CRUD functions.

#### User Stories
| ID  | User Story Description                                       | Priority  | Status  |
| --- | -------------------------------------------------------------| --------- | ------- |
| 001 | As a user, I want to login and logout             | High      |  To Do   |
| 002 | As a user, I want to be able to set my fitness goals & log workouts         | High | To Do |

#### Tasks
| Task ID | Description                               | Related User Story | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | ------------------ | ------------------ | ------- |
| T001    | Implement authentication flow             | 001                | 4                  | To Do   |
| T002    | Create database models                    | 001                | 8                  | To Do |
|T003     | User Can Set Their Fitness Goals          |  002                  | 5                  |      To Do         |
|T004     | User can log their workouts. (sets, reps, weights) |    002       | 5                   |    To Do        |


#### Bugs
| Bug ID  | Description                               | Priority  | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | --------- | ------------------ | ------- |
|  B001  |                  |      |                  |    |

---

### Sprint 2 - [Sprint Name] - [Start Date] to [End Date]
#### Sprint Goal
- Brief description of the goal for Sprint 2.

#### User Stories
| ID  | User Story Description                                       | Priority  | Status  |
| --- | -------------------------------------------------------------| --------- | ------- |
| 001 |      |       |   |
| 002 |         |  |  |

#### Tasks
| Task ID | Description                               | Related User Story | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | ------------------ | ------------------ | ------- |
| T001    |          |              |               |    |
| T002    |                |            |       |  |

#### Bugs
| Bug ID  | Description                               | Priority  | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | --------- | ------------------ | ------- |
| B001    |                   |       |         |   |

---

### Sprint 3 - [Sprint Name] - [Start Date] to [End Date]
#### Sprint Goal
- Brief description of the goal for Sprint 3.

#### User Stories
| ID  | User Story Description                                       | Priority  | Status  |
| --- | -------------------------------------------------------------| --------- | ------- |
| 001 |      |       |   |
| 002 |         |  |  |

#### Tasks
| Task ID | Description                               | Related User Story | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | ------------------ | ------------------ | ------- |
| T001    |          |              |               |    |
| T002    |                |            |       |  |

#### Bugs
| Bug ID  | Description                               | Priority  | Estimation (Hours) | Status  |
| ------- | ----------------------------------------- | --------- | ------------------ | ------- |
| B001    |                   |       |         |   |


---

## Sprint Retrospective (End of Project)
- **What went well:** [list of positive outcomes for the project]
- **What can be improved:** [areas for improvement across all sprints]
- **Action items for future projects:** [steps for improvement in future projects]

---

## Notes
- Additional notes or comments.
