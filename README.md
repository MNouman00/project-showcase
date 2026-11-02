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
 ### Frontend Functions (React/Vite)
- Dynamic Product Catalog: Fetches data from the Django API. Allows users to search, filter by category, and sort products by price or date.
- State Management (Cart): Uses React Context API to manage the shopping cart globally. Users can add items, adjust quantities, and the state persists using localStorage (so the cart doesn't empty if the page refreshes).
- User Authentication (JWT): Handles user registration and login. It stores the JWT access token securely and passes it in the headers for authenticated requests.
- Checkout & Payment Flow: Collects shipping details and offers multiple payment methods (Cash on Delivery, Cards, Easypaisa, etc.). It handles form validation and sends the order data to the backend.
- Order Tracking: Authenticated users have a dedicated dashboard where they can view their order history, check the current status (pending, shipped, etc.), and cancel pending orders.

Backend Functions (Django REST Framework)
- RESTful API: Provides clean JSON endpoints for products, categories, orders, and user management.
- Role-Based Access Control: Public users can view products, but only authenticated users (using JWT) can place orders or view their profiles.
- Custom Admin Dashboard: A powerful backend interface where the store owner can:
Create, edit, or delete Categories and Products.
- Manage Stock levels (automatically deducted when an order is placed).
- Mark products as "Featured" or "On Sale" with custom discount percentages.
- View and update the status of customer orders (e.g., change from Pending to Shipped).
- Newsletter System: A dedicated API endpoint that captures user emails from the frontend and securely stores them in the database.
- Cloudinary Integration: Automatically uploads and serves product images to a cloud CDN, ensuring images load fast and are never lost when the server restarts

# 2 ⚙️ Machine.pk Sealing Platform
A specialized web platform designed for the sealing and packaging industry.
- **🔗 Live Link:** [https://machine-pk-sealing-platform.vercel.app](https://machine-pk-sealing-platform.vercel.app)
- **🛠️ Tech Stack:** React, Vite, Tailwind CSS, Django, Django REST Framework, PostgreSQL, LangGraph, LangChain, Groq, JWT Auth, Render, Vercel
- **✨ Highlights:** Includes optimized performance with a 1-minute auto-refresh interval for live data tracking.
  AECO Sealing Platform (MACHINES.PK) is a full-stack B2B e-commerce platform with a custom AI sales assistant built on LangGraph and Groq. The platform enables industrial buyers to search a live product catalog, check specs, verify inventory, and place real orders through natural-language conversation — all in under 60 seconds.

 ###  Detailed Description:
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

# 3 🤖 LangGraph Website Chatbot
An AI-powered website chatbot integration to assist users with automated responses.
- **🔗 Live Link:** [https://langgraph-website-chatbot.vercel.app](https://langgraph-website-chatbot.vercel.app)
- **🛠️ Tech Stack:** React, Tailwind CSS, Python, FastAPI, LangGraph, LangChain, Groq API, Tavily Search, SQLite, Server-Sent Events (SSE)
- **✨ Highlights:** Implements advanced AI workflows for natural language understanding.

###  Detailed Description:
An intelligent, full-stack AI chatbot built to demonstrate advanced LLM orchestration. The backend leverages LangGraph to create an agentic workflow, allowing the AI to autonomously decide when to use Tavily Search for real-time web retrieval and cite its sources.

Key Features:
• Real-time Streaming: Utilizes FastAPI and Server-Sent Events (SSE) to stream AI responses token-by-token, providing an instant, ChatGPT-like user experience.
• Agentic RAG Pipeline: The AI is bound to tools and can independently execute web searches to answer questions about recent events or specific facts.
• Stateful Memory: Implements LangGraph's async SQLite checkpointer to persist multi-turn conversation history, mapping unique thread IDs to specific user sessions.
• High-Speed Inference: Powered by the Groq API for ultra-fast token generation.
• Modern Architecture: Uses FastAPI's lifespan context manager for safe, single-time initialization of the AI graph and database connections.

  
# 4 🚲 Bicycle Rental System
A web application designed to manage and rent bicycles.
- **🔗 Live Link:** [https://bicycle-rental.vercel.app](https://bicycle-rental.vercel.app)
- **🛠️ Tech Stack:**  React, Django, JavaScript, TailwindCSS, Python, REST API, PostgreSQL (or whatever DB used)
- **✨ Highlights:** Built with a focus on clean UI and seamless rental management.
### Detailed Description
  The Bicycle Rental Website is a full-stack application designed for seamless bike bookings. The frontend is built with React and TailwindCSS, featuring a clean, mobile-first interface, while the backend was developed using Django and Python to handle inventory and booking logic via a custom REST API.

Note on Live Demo: The backend was hosted on a free-tier service which has since expired, meaning the database and API are currently offline. The live link demonstrates the React frontend UI. However, the complete full-stack source code (including the Django models, API views, and authentication logic) is available on GitHub to showcase the end-to-end architecture.



## 📬 Contact
If you'd like to collaborate or have any questions, feel free to reach out!
- **Portfolio:** [https://portfolio-five-umber-43.vercel.app](https://portfolio-five-umber-43.vercel.app)
