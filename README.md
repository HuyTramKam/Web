# Online Academy Course Marketplace

## Overview
A web-based platform that allows users to create, buy, and enroll in online courses. The system supports both learners and instructors with course management features.

## Features
- User authentication (register, login)
- Create and manage courses
- Browse and enroll in courses
- Upload course content
- Basic dashboard for users

## System Architecture
The project follows MVC structure:

- controllers/ → handle request logic
- models/ → database schema & data handling
- routes/ → define API endpoints
- views/ → UI templates
- middlewares/ → authentication & validation
- static/ → CSS, JS, images
- utils/ → helper functions
- uploads/ → stored uploaded files

## Database
- PostgreSQL (via Supabase)
- Tables:
  - users (id, username, password, role, permission, dob)
  - courses (...)

## How to run
```bash
npm install
node app.js
