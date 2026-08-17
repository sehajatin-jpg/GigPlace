# GigPlace

**GigPlace** is a full-stack job portal built with the MERN stack that connects job seekers and recruiters through job discovery, applications, and recruitment management.

🔗 **Live Demo:** https://gig-place-sigma.vercel.app/

🔗 **GitHub:** https://github.com/sehajatin-jpg/GigPlace.git

## Features

* **Authentication** — User registration, login, JWT authentication, and protected routes.
* **Job Search** — Browse and search available job opportunities.
* **Job Applications** — Apply for jobs and manage application status.
* **Recruiter Portal** — Recruiters can create, manage, and track job postings.
* **User Profiles** — Separate workflows for job seekers and recruiters.
* **Admin Management** — Admin functionality for managing the platform.
* **REST API Integration** — Frontend communicates with the Express backend through REST APIs.
* **Responsive UI** — Designed to work across different screen sizes.

## Tech Stack

**Frontend:** React.js, Vite, React Router
**Backend:** Node.js, Express.js, REST APIs, JWT
**Database:** MongoDB, Mongoose, MongoDB Atlas
**Deployment:** Vercel, Render

## Architecture

```text
React Frontend
      ↓
REST APIs
      ↓
Express.js + Node.js
      ↓
MongoDB
```

Authentication and protected routes are handled using JWT, while the backend manages users, jobs, applications, and recruiter-related operations.

## About

GigPlace was my **first MERN stack project and my first hackathon project**.

The biggest challenge was connecting the React frontend with the Node.js/Express backend. Since it was my first full-stack application, I had to learn how frontend API requests, backend routes, authentication, database operations, and deployment work together.

Building GigPlace gave me a strong foundation in **MERN stack development** and helped me understand how to build and connect a complete full-stack application.

## What I Learned

* Building REST APIs with Node.js and Express
* Connecting React with a backend
* MongoDB and Mongoose
* JWT authentication and protected routes
* Handling frontend/backend communication
* Debugging CORS and API issues
* Deploying a full-stack application
* Building a project for a hackathon
