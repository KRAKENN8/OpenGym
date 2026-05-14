# OpenGym

## Project Description 
OpenGym is an open-source web and mobile platform for creating and managing gyms, fitness clubs, and training spaces. The project provides a complete environment for managing members, schedules, bookings, and trainers through a centralized system.

The platform is designed for gym owners, administrators, personal trainers, and members who need an easy and modern solution for sports club management.

# Team members

- [Ivan (KRAKENN8)](https://github.com/KRAKENN8)
- [Maksim (rewazi)](https://github.com/rewazi)

# Tech Stack

- **Frontend Language:** React + TypeScript + Tailwind CSS
- **Backend Language:** Node.js + Express.js
- **Mobile Application:** React Native
- **Database:** PostgreSQL
- **Architecture:** Layered architecture
- **Tools:** CI/CD, GitHub Actions, Figma, Postman

## Architecture

OpenGym uses a **Layered Architecture** because it makes the project easier to develop, maintain, and scale.  
This approach separates frontend, backend, and database logic, which helps avoid confusion in the codebase.

It was chosen because:

- frontend and backend can be developed independently
- new features can be added more easily
- the code is easier to maintain and debug
- the architecture works well for both web and mobile applications
- the project can scale better in the future

# Functional Requirements

1. Users can register and log into the system
2. Members can book training sessions
3. Administrators can manage schedules
4. Trainers can view their client lists
5. The system sends notifications about schedule changes
6. Users can view membership information
7. Administrators can manage trainers
8. Users can cancel booked sessions

# Non-Functional Requirements

1. Login time should not exceed 3 seconds.
2. The application must support desktop and mobile devices
3. User data must be securely stored and encrypted

# UML Diagramm

## Project Plan

The development process is organized using a Kanban board. Tasks are grouped into logical stages that represent the main phases of the project.

### Stage 1 - Project Setup
In this stage, the basic project structure is created.
- Set up frontend, backend, and mobile applications
- Configure database (PostgreSQL)
- Initialize GitHub repository and CI/CD pipeline

### Stage 2 - Core Backend Development
Focus on implementing main server functionality.
- User authentication (registration/login)
- Database schema design
- REST API structure setup
- Basic security and middleware

### Stage 3 - Core Features Implementation
Development of main system functionality.
- Booking system
- Schedule management
- Trainer management
- User profile and membership features

### Stage 4 - Frontend & Mobile Development
Implementation of user interfaces.
- Web dashboard (React)
- Mobile application (React Native)
- Responsive design improvements
- API integration

### Stage 5 - Testing & Improvements
Final stabilization phase.
- Bug fixing
- Error handling improvements
- Performance optimization
- UI/UX improvements

### Stage 6 - Deployment & Documentation
Final preparation for release.
- CI/CD pipeline finalization
- Project documentation completion
- Deployment setup
