# Job Crawler & Application Tracker

A cloud-based job search platform that helps users discover job opportunities, filter relevant listings, and keep track of applications in one place.

## Overview

Job seekers often have to search across multiple websites and manually keep track of the positions they have applied to.

This project aims to simplify that process by collecting job postings from multiple sources, storing them in a centralized database, filtering relevant opportunities, and allowing users to track their applications through a web dashboard.

## Features

- Collect job postings from multiple sources
- Store job listings in a centralized database
- Filter jobs based on user preferences
- Detect and reduce duplicate job postings
- Display relevant jobs through a web dashboard
- Track application status
- Send notifications for new matching jobs

## Tech Stack

### Frontend
- React
- JavaScript
- Azure Static Web Apps

### Backend
- Python
- Azure Functions

### Database
- PostgreSQL or Azure SQL Database

### Cloud Services
- Azure Blob Storage
- Azure Queue Storage
- Azure Communication Services
- Azure Functions Timer Trigger

### Development
- Git
- GitHub
- GitHub Actions

## How It Works

```text
Job Sources
    |
    v
Job Crawler
    |
    v
Backend Processing
    |
    v
Database
    |
    +------> Job Filtering
    |             |
    |             v
    |        SMS Notifications
    |
    v
React Dashboard
    |
    v
Application Tracking
```

## Project Structure

```text
job-crawler/
├── frontend/
├── backend/
├── database/
├── functions/
├── docs/
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd job-crawler
```

### 2. Install dependencies

Frontend:

```bash
cd frontend
npm install
```

Backend:

```bash
cd backend
pip install -r requirements.txt
```

### 3. Configure environment variables

Create the required environment files for database credentials, API keys, and Azure services.

Do not commit passwords, API keys, or other sensitive information to GitHub.

### 4. Run the application

Start the frontend:

```bash
npm run dev
```

Run the backend according to the Azure Functions configuration.

## Team

| Team Member | Role |
|---|---|
| Ebulo Mejia | Database Developer |
| Dylan Wu | Flex / Fill |
| Johnny Zhu | Backend Developer |
| Joshua Okeke | Researcher |
| Lina Romero | Backend Developer |
| Ayomide Ogunbode | Frontend Developer |

## Project Status

This project is currently under development for INST 347 at the University of Maryland.

Features and implementation details may change as development continues.
