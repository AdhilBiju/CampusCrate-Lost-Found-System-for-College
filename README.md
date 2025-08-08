# CampusCrate-Lost-Found-System-for-College
CampusCrate – Lost & Found System for College
CampusCrate is a full-stack MERN web application that helps college students securely report, search, and claim lost and found items on campus, with role-based access, images, chat, moderation, and a modern UI.


🚀 Features
Google login (college email restriction)

User roles (student / admin), JWT-protected API routes

Create, search, and filter "lost" and "found" items

Image uploads via Cloudinary

Claim items via secure flow

Real-time chat/commenting (Socket.io or REST)

Admin panel for approving items, moderating users & reports

Responsive design (Material UI / TailwindCSS)

Modern folder structure, ready for deployment

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/eaedf0ca-979a-404e-aa0a-444fc5280acd" />

🌎 Main Tech Stack
Frontend: React, React Router, Axios, MUI/Tailwind CSS

Backend: Node.js, Express.js, Passport.js (Google OAuth), JWT, Multer, Cloudinary

Database: MongoDB + Mongoose
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/27b75ec6-81e4-4525-8fcf-b476e592cac6" />


🤖 API Routes Overview
/api/auth – Login, Google OAuth callbacks

/api/items – CRUD lost/found items, with filtering/search

/api/claims – Claim and chat on items

/api/admin – Approve/reject posts, manage users/reports
