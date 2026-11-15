# Tactyqal Labs – Frontend Redesign & Blog Management System

A full-stack project built as part of the Tactyqal Labs development assignment. It includes a redesigned company homepage and a blog management system with a custom backend and database.

## Live Demo

- **Task 1 – Homepage:** [https://tactyqal-cms-otwy.vercel.app]
- **Task 2 – Blog Dashboard:** [https://tactyqal-cms.vercel.app]

## Project Overview

### Task 1 – Homepage Redesign

Redesigned the existing Tactyqal Labs homepage with a modern, responsive interface focused on usability, visual hierarchy, and a clean user experience.

**Highlights:**
- Responsive layout for desktop, tablet, and mobile.
- Modern UI with consistent typography and spacing.
- Improved content hierarchy and navigation.
- Reusable React components.

### Task 2 – Blog Management System

Developed a custom blog backend to manage blog content without relying on a separate WordPress installation.

**Highlights:**
- RESTful API architecture.
- Create, read, update, and delete blog posts.
- MongoDB database integration.
- Category management.
- Author and category population.
- Slug-based blog retrieval.
- Authentication and protected dashboard routes.
- Featured image management.

## Tech Stack

**Frontend**
- React.js
- Vite
- Tailwind CSS
- Redux Toolkit
- React Router

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

**Deployment**
- Vercel – Frontend
- Render – Backend
- MongoDB Atlas – Database

## Project Structure

```text
Tactyqal/
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── services/
│   ├── validators/
│   └── package.json
│
└── README.md
```

## Author

**Pratyush Singh**
---

Built with React, Node.js, Express, and MongoDB.