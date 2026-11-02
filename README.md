# M. Nouman — Full-Stack Developer Portfolio

Welcome to my project showcase! This repository serves as a central hub for my latest full-stack web applications. Below you will find detailed descriptions, live links, and the tech stacks behind each project. 

## 🚀 The Main Portfolio Hub

A modern, fully responsive portfolio web application showcasing my projects, technical skills, and experience. Built with a React (Vite) + Tailwind CSS frontend and a Django REST Framework backend with PostgreSQL.

- **🔗 Live Link:** [https://portfolio-five-umber-43.vercel.app](https://portfolio-five-umber-43.vercel.app)
- **🛠️ Tech Stack:** React (Vite), Django REST Framework, PostgreSQL, Tailwind CSS v4.
- **✨ Key Feature:** Includes a secure admin dashboard with custom-signed token authentication to dynamically add, edit, and delete projects directly from the UI.

---

## 📂 Featured Projects

Here are some of the live applications I have built and deployed:

# 1 🛒 Complete End-to-End E-Commerce Platform
A fully functional e-commerce platform featuring a complete user flow from browsing products to checkout.
- **🔗 Live Link:** [https://complete-end-to-end-e-commerce-plat.vercel.app](https://complete-end-to-end-e-commerce-plat.vercel.app)
- **🛠️ Tech Stack:** React, Vite, Tailwind CSS, Django, Django REST Framework, PostgreSQL, JWT Authentication, Cloudinary, Vercel, Render
- **✨ Highlights:** Features robust production-ready configurations including CORS and CSRF security settings.
  A complete, production-deployed e-commerce platform built with React (Vite) and Django REST Framework. Features secure JWT authentication, dynamic category filtering, a persistent shopping cart, and a full checkout flow. Deployed on Vercel and Render.
 ###  Detailed Description:
Frontend: React, Vite, Tailwind CSS, React Router, React Helmet (for SEO).
Backend: Django, Django REST Framework, PostgreSQL.
Authentication: JWT (JSON Web Tokens) for secure user login and registration.
Cloud Storage: Cloudinary (for permanent product image hosting).
Deployment: Frontend hosted on Vercel, Backend & Database hosted on Render.
Key Features: Dynamic product search, category filtering, user order history, newsletter subscription, and a custom Django Admin panel for inventory management.

# 2 ⚙️ Machine.pk Sealing Platform
A specialized web platform designed for the sealing and packaging industry.
- **🔗 Live Link:** [https://machine-pk-sealing-platform.vercel.app](https://machine-pk-sealing-platform.vercel.app)
- **🛠️ Tech Stack:** React, Vite, Tailwind CSS, Django, Django REST Framework, PostgreSQL, LangGraph, LangChain, Groq, JWT Auth, Render, Vercel
- **✨ Highlights:** Includes optimized performance with a 1-minute auto-refresh interval for live data tracking.
  AECO Sealing Platform (MACHINES.PK) is a full-stack B2B e-commerce platform with a custom AI sales assistant built on LangGraph and Groq. The platform enables industrial buyers to search a live product catalog, check specs, verify inventory, and place real orders through natural-language conversation — all in under 60 seconds.

 #  Detailed Description:
• LangGraph-powered AI agent with 4 custom tools (search_products, get_product_details, check_inventory, create_order) that read and write to the PostgreSQL database.
• Server-Sent Events (SSE) streaming for real-time token-by-token AI responses.
• Token-based authentication with Djoser, secure user registration, and user-linked order tracking.
• Dynamic visual shipping tracker that animates a delivery truck based on order status (Pending → Paid → Shipped → Delivered).
• Product catalog with category filtering, sorting, image galleries, and persistent localStorage cart.
• Admin dashboard (Django Admin) with full CRUD for products, orders, and quotes.

Challenges Solved:
• Production deployment across Render (backend) + Vercel (frontend), resolving CORS, static file serving (Whitenoise), and media storage issues.
• AI tool-call schema validation — resolved null-handling errors by typing tool parameters as Optional.
• Stale token bug in localStorage causing 401 errors — fixed with a custom Axios interceptor.
• Render cold-start handling with a 60-second request timeout and auto-wakeup strategy.

Result: A production-ready AI-driven B2B platform that reduces customer friction from first inquiry to confirmed order to under one minute.

# 3 🚲 Bicycle Rental System
A web application designed to manage and rent bicycles.
- **🔗 Live Link:** [https://bicycle-rental.vercel.app](https://bicycle-rental.vercel.app)
- **🛠️ Tech Stack:**  React, Django, JavaScript, TailwindCSS, Python, REST API, PostgreSQL (or whatever DB used)
- **✨ Highlights:** Built with a focus on clean UI and seamless rental management.
### Detailed Description
  The Bicycle Rental Website is a full-stack application designed for seamless bike bookings. The frontend is built with React and TailwindCSS, featuring a clean, mobile-first interface, while the backend was developed using Django and Python to handle inventory and booking logic via a custom REST API.

Note on Live Demo: The backend was hosted on a free-tier service which has since expired, meaning the database and API are currently offline. The live link demonstrates the React frontend UI. However, the complete full-stack source code (including the Django models, API views, and authentication logic) is available on GitHub to showcase the end-to-end architecture.

### 🤖 LangGraph Website Chatbot
An AI-powered website chatbot integration to assist users with automated responses.
- **🔗 Live Link:** [https://langgraph-website-chatbot.vercel.app](https://langgraph-website-chatbot.vercel.app)
- **🛠️ Tech Stack:** LangGraph, AI APIs, React
- **✨ Highlights:** Implements advanced AI workflows for natural language understanding.

---

## 🛠️ Core Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, React Router DOM, FontAwesome
- **Backend:** Python, Django, Django REST Framework (DRF)
- **Database:** PostgreSQL
- **Deployment:** Vercel (Frontend), Render (Backend & Database)

## 📬 Contact
If you'd like to collaborate or have any questions, feel free to reach out!
- **Portfolio:** [https://portfolio-five-umber-43.vercel.app](https://portfolio-five-umber-43.vercel.app)
