# Golf Homes & Kingdom — Society Management Prototype

Stack: **Java 17 + Spring Boot 3 + React/Vite + MySQL 8**.

Included UI flows: Admin dashboard, flat-owner accounts, committee/special members, planned/live/closed voting, multiple voting plans, fixed start/end time, live voting extension, one-vote-per-flat backend constraint, complaints, work/expenses, notices, meetings, reports and settings.

## Run
### MySQL
CREATE DATABASE golf_homes_society;
Edit `backend/src/main/resources/application.properties` and set `spring.datasource.password`.

### Backend
cd backend
mvn spring-boot:run

### Frontend
cd frontend
npm install
npm run dev

Frontend: http://localhost:5173 | Backend: http://localhost:8080


# Golf Homes & Kingdom — Society Management System

A full-stack society management application designed to
manage residents, committee activities, voting, complaints,
expenses, notices, meetings, and reports.

## Technology Stack

- Java 17
- Spring Boot 3
- React + Vite
- MySQL 8

## Key Features

- Admin dashboard and resident accounts
- Committee and special member management
- Planned, live, and closed voting
- One vote per flat validation
- Complaints and expense management
- Notices and meeting management
- Reports and application settings

## Screenshots

### Admin Dashboard
![Admin Dashboard](frontend/public/images/admin-dashboard.png)

### Resident Dashboard
![Resident Dashboard](frontend/public/images/resident-dashboard.png)

### Voting System
![Voting System](frontend/public/images/voting-system.png)

## Project Structure

- `backend/` — Spring Boot REST APIs
- `frontend/` — React user interface

## Author

Raunak Kumar

## GitHub Repository

https://github.com/RaunakKumar1234/golf-homes-kingdom-society

