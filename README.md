# Project Organizer

The Project Management Platform is a web-based CRUD (Create, Read, Update, Delete) application designed to facilitate project management tasks efficiently. It enables users to swiftly create projects, add tasks to projects, and effortlessly manage projects, all without requiring user accounts. With its intuitive front-end interface, users can visually interact with their projects, making the management process more engaging and user-friendly.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [Members Repositories](#members-repositories)
- [Contact](#contact)
- [License](#license)

## Overview
This project management application is designed to help manage tasks, projects, and teams efficiently. It provides a user-friendly interface for creating, updating, and managing various project-related activities.

## Features
- Task creation and management
- Project tracking
- Team collaboration tools
- Real-time updates
- User authentication and authorization

## Installation
There is no installation required for the Project Management Platform. Simply access the platform through your preferred web browser by navigating to the URL where it is hosted.

To use the Project Management Platform, follow these steps:

1. **Access the Platform:**
   - Open your web browser.
   - Navigate to the URL where the platform is hosted.

2. **Navigating the Interface:**
   - Upon accessing the platform, you will be presented with the homepage.
   - Use the navigation bar or the homepage links to access different sections of the platform.

3. **Creating a New Project:**
   - Click on the "New Project" button, usually located in the top menu or on the dashboard.
   - Enter the required project details in the form that appears and submit it to create your new project.

4. **Adding Tasks to a Project:**
   - Navigate to the project you want to add tasks to.
   - Click on "Add Task" within the project’s detail page.
   - Fill out the task details in the provided form and submit it to add the task to your project.

5. **Managing Projects and Tasks:**
   - Use the dashboard or the projects page to view all your projects.
   - Click on a project to view its details, including its tasks, status, and options to edit or delete the project or its tasks.

## Technologies
### Frontend
- **React**: JavaScript library for building user interfaces
- **TypeScript**: Superset of JavaScript that adds static types
- **CSS**: Styling the application
- **HTML**: Structuring the web pages

### Backend
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine
- **Express**: Web application framework for Node.js
- **MongoDB**: NoSQL database for storing project data

### Others
- **Git**: Version control system for tracking changes in the source code
- **NPM**: Package manager for JavaScript
- **Webpack**: Module bundler for JavaScript applications

## File Structure
```plaintext
project_management_front
│
├── public
├── src
│   ├── components
│   │   ├── Cards
│   │   ├── Containers
│   │   ├── Modal
│   │   └── Navbar
│   │       └── Navbar.tsx
│   ├── forms
│   ├── interfaces
│   ├── App.tsx
│   └── index.tsx
├── .gitignore
├── package-lock.json
├── package.json
└── tsconfig.json
