<h1 align="center">Hi 👋, I'm Muhammed Shafi KT</h1>

<h3 align="center">
  Full Stack Developer | MERN Stack | Backend Engineering
</h3>

<p align="center">
  <a href="https://github.com/muhammedShafiKT">
    <img src="https://komarev.com/ghpvc/?username=muhammedShafiKT&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  </a>
  <a href="https://github.com/muhammedShafiKT?tab=followers">
    <img src="https://img.shields.io/github/followers/muhammedShafiKT?label=Followers&style=flat" alt="GitHub Followers" />
  </a>
  <a href="https://github.com/muhammedShafiKT?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=flat&logo=github" alt="GitHub Repositories" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/muhammedShafiKT">
    <img src="https://img.shields.io/badge/GitHub-muhammedShafiKT-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="mailto:muhammedshafikt85@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm an **Entry-Level MERN Stack Developer** focused on building secure,
scalable, and production-oriented full-stack web applications.

I work across the complete application stack, from responsive React
interfaces and REST APIs to authentication, databases, background jobs,
real-time communication, cloud storage, and deployment.

Currently, I'm working as a **Full Stack Developer Intern at Bridgeon
Solutions**, where I develop full-stack application features using React.js,
Node.js, Express.js, and MongoDB.

### My primary focus

* ⚛️ Full-stack web application development
* 🟢 Node.js backend engineering
* 🔐 Authentication and authorization
* 🍃 MongoDB and database design
* ⚡ Redis and background job processing
* 🔌 Real-time applications with Socket.IO
* ☁️ Cloud deployment and infrastructure
* 📊 Data analytics platforms
* 🤖 AI and LLM-integrated applications

---

# 🏢 Current Experience

## Full Stack Developer Intern — Bridgeon Solutions

**November 2025 – Present | Kerala, India**

Working on end-to-end web application development using the MERN stack.

### Responsibilities

* Developing scalable application features using React.js, Node.js,
  Express.js, and MongoDB
* Designing and integrating secure REST APIs
* Implementing JWT-based authentication
* Building reusable backend modules
* Working with MongoDB and application data models
* Optimizing application performance
* Maintaining and extending existing application features

---

# 🚀 Featured Projects

## 📊 Insight Flow

### AI-Powered Data Analytics Platform

Insight Flow is a data analytics platform designed to transform uploaded
datasets into analytical dashboards, insights, and reports.

### Technology Stack

`React.js` `Redux Toolkit` `Node.js` `Express.js`

`MongoDB` `DuckDB` `Redis` `BullMQ`

`Socket.IO` `Cloudflare R2` `OpenAI`

`Puppeteer` `AWS EC2`

### Key Features

* 📂 Dataset ingestion
* 🔍 Automated data profiling
* ✅ Data validation pipeline
* 📊 Interactive analytics dashboards
* ⚡ Redis caching
* 🐂 BullMQ background job processing
* 🔌 Socket.IO real-time status updates
* 🦆 DuckDB analytics engine
* ☁️ Cloudflare R2 object storage
* 📄 PDF report generation
* 🤖 OpenAI / LLM integration
* 🔐 JWT authentication
* 🔑 Google OAuth
* ☁️ AWS EC2 backend deployment
* ▲ Vercel frontend deployment

### Architecture

```text
                        ┌──────────────────┐
                        │     React UI     │
                        │   Redux Toolkit  │
                        └────────┬─────────┘
                                 │
                                 ▼
                        ┌──────────────────┐
                        │    Node.js API   │
                        │    Express.js    │
                        └────────┬─────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
              ▼                  ▼                  ▼
        ┌──────────┐       ┌──────────┐       ┌──────────┐
        │ MongoDB  │       │  Redis   │       │ R2       │
        │ Metadata │       │  Cache   │       │ Datasets │
        └──────────┘       └────┬─────┘       └──────────┘
                                │
                                ▼
                         ┌─────────────┐
                         │   BullMQ    │
                         │   Workers   │
                         └──────┬──────┘
                                │
                 ┌──────────────┼──────────────┐
                 │              │              │
                 ▼              ▼              ▼
              DuckDB        Puppeteer       OpenAI
                 │              │              │
                 └──────────────┼──────────────┘
                                ▼
                         Analytics / Reports
```

### Data Pipeline

```text
Dataset Upload
      ↓
Cloud Storage
      ↓
Data Ingestion
      ↓
Data Profiling
      ↓
Validation
      ↓
DuckDB Analytics
      ↓
Dashboard Generation
      ↓
AI Insights
      ↓
PDF Report
```

---

# 🛒 Luxora

## Full Stack E-Commerce Platform

Luxora is a full-stack e-commerce application featuring product management,
shopping functionality, authentication, coupons, payments, image
management, and an administrative dashboard.

### Technology Stack

`React.js` `Redux Toolkit` `Context API`

`Node.js` `Express.js` `MongoDB`

`Razorpay` `Cloudinary`

### Features

* 🛍️ Product management
* 🛒 Shopping cart
* ❤️ Wishlist
* 🎟️ Coupon system
* 💳 Razorpay payment integration
* 🔐 JWT authentication
* 🔑 Google OAuth
* 👥 Role-based authorization
* 🖼️ Cloudinary image management
* 👨‍💼 Admin dashboard
* 🍃 MongoDB database
* 🔗 REST API architecture

### Architecture

```text
                     React Frontend
                           │
              ┌────────────┼────────────┐
              │            │            │
              ▼            ▼            ▼
          Components    Redux       React Router
              │          Toolkit
              └────────────┬───────────┘
                           │
                           ▼
                    Axios / REST API
                           │
                           ▼
                 Node.js + Express.js
                           │
       ┌───────────────────┼───────────────────┐
       │                   │                   │
       ▼                   ▼                   ▼
 Authentication       Product APIs        Order APIs
       │                   │                   │
       └───────────────────┼───────────────────┘
                           │
                           ▼
                        MongoDB
                           │
              ┌────────────┼────────────┐
              │            │            │
              ▼            ▼            ▼
           Users       Products       Orders

External Services
       │
       ├── Razorpay → Payments
       ├── Cloudinary → Images
       └── Google OAuth → Authentication
```

---

# 🧰 Tech Stack

## Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,js,ts,html,css,tailwind,redux,vite" />
</p>

```text
React.js
JavaScript
TypeScript
HTML5
CSS3
Tailwind CSS
Next.js
Redux Toolkit
React Router
Axios
Recharts
Vite
```

---

## Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

```text
Node.js
Express.js
REST APIs
Socket.IO
JWT
OAuth
Bcrypt
Cookie-Based Authentication
WebSockets
```

---

## Databases & Analytics

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,redis" />
</p>

```text
MongoDB
Mongoose
PostgreSQL
Redis
DuckDB
```

---

## Cloud & Deployment

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,nginx,cloudflare,vercel" />
</p>

```text
AWS EC2
Cloudflare R2
Vercel
Docker
Nginx
Cloud Deployment
Reverse Proxy
```

---

## Development Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />
</p>

```text
Git
GitHub
Postman
VS Code
BullMQ
Puppeteer
Multer
Cloudinary
Razorpay
```

---

# 🔐 Authentication & Security

I have experience implementing authentication and authorization systems
using JWT and OAuth.

```text
                         Authentication
                              │
              ┌───────────────┴───────────────┐
              │                               │
              ▼                               ▼
             JWT                         Google OAuth
              │
       ┌──────┴──────┐
       │             │
       ▼             ▼
 Access Token   Refresh Token
       │
       ▼
 Protected APIs
       │
       ▼
 Authorization
       │
       ├── Role-Based Access
       └── Protected Routes
```

### Security Technologies

* JWT authentication
* Cookie-based authentication
* Bcrypt password hashing
* Google OAuth
* Protected routes
* Authentication middleware
* Authorization middleware
* Role-based access control
* Secure REST APIs

---

# ⚡ Backend Engineering

My backend development approach follows a separation of responsibilities:

```text
Client
  │
  ▼
HTTP Request
  │
  ▼
Express Router
  │
  ▼
Middleware
  │
  ├── Authentication
  ├── Authorization
  └── Validation
  │
  ▼
Controller
  │
  ▼
Service Layer
  │
  ▼
Database / External Service
```

I focus on:

* REST API design
* Modular backend architecture
* Authentication
* Authorization
* Error handling
* Validation
* Database operations
* Performance optimization
* Reusable backend modules

---

# ⚡ Background Job Processing

For long-running operations, I work with **Redis and BullMQ**.

```text
Client
  │
  ▼
API Server
  │
  ▼
Create Job
  │
  ▼
Redis
  │
  ▼
BullMQ Queue
  │
  ▼
Worker
  │
  ├── Dataset Processing
  ├── Analytics
  ├── PDF Generation
  └── Other Heavy Tasks
  │
  ▼
Result / Status
  │
  ▼
Client
```

This architecture helps move expensive operations away from the main
HTTP request lifecycle.

---

# 📡 Real-Time Systems

I use **Socket.IO / WebSockets** when applications require real-time
communication.

```text
                    Socket.IO Server
                          │
              ┌───────────┼───────────┐
              │           │           │
              ▼           ▼           ▼
           Events      Rooms       Status
              │           │           │
              └───────────┼───────────┘
                          │
                          ▼
                    Connected Clients
```

Typical use cases include:

* Real-time processing status
* Notifications
* Live dashboards
* Job progress
* Real-time data updates

---

# 📊 Data Analytics

I'm particularly interested in building applications that process and
analyze large datasets.

### Analytics Pipeline

```text
Upload
  ↓
Storage
  ↓
Ingestion
  ↓
Profiling
  ↓
Validation
  ↓
Analytics
  ↓
Visualization
  ↓
AI Insights
  ↓
Report Generation
```

Technologies I've worked with include:

`DuckDB`

`MongoDB`

`Cloudflare R2`

`Redis`

`BullMQ`

`Recharts`

---

# 🤖 AI & LLM Integration

I'm exploring the integration of LLMs into real-world software systems.

### Areas of interest

* OpenAI SDK
* LLM API integration
* AI-powered analytics
* Intelligent assistants
* Natural-language explanations
* Structured data → LLM pipelines
* AI-generated insights
* AI-assisted dashboard generation

```text
User Dataset
     │
     ▼
Data Profiling
     │
     ▼
Statistical Analysis
     │
     ▼
Structured Insights
     │
     ▼
LLM
     │
     ▼
Natural Language Explanation
     │
     ▼
Dashboard / Report
```

---

# 🧠 Engineering Interests

```text
Software Engineering
        │
        ├── Full Stack Development
        ├── Backend Engineering
        ├── REST API Design
        └── System Architecture

Performance
        │
        ├── Database Optimization
        ├── Redis Caching
        ├── Background Processing
        └── Efficient Data Access

Distributed Systems
        │
        ├── Queues
        ├── Workers
        ├── WebSockets
        └── Event-Driven Architecture

Cloud
        │
        ├── AWS
        ├── Object Storage
        ├── Docker
        └── Nginx

AI
        │
        ├── LLM Integration
        ├── AI Analytics
        └── Intelligent Applications
```

---

# 📈 GitHub Statistics

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=muhammedShafiKT&show_icons=true&theme=tokyonight&hide_border=true"
    height="180"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammedShafiKT&layout=compact&theme=tokyonight&hide_border=true"
    height="180"
  />
</p>

---

# 🔥 GitHub Streak

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=muhammedShafiKT&theme=tokyonight&hide_border=true"
    alt="GitHub Streak"
  />
</p>

---

# 🐍 Contribution Graph

<p align="center">
  <img
    src="https://raw.githubusercontent.com/muhammedShafiKT/muhammedShafiKT/output/github-contribution-grid-snake.svg"
    alt="GitHub Contribution Snake"
  />
</p>

---

# 📚 Currently Learning

```text
Advanced JavaScript
TypeScript
System Design
Backend Architecture
Redis
Distributed Systems
Docker
AWS
Data Engineering
AI / LLM Applications
```

---

# 🎯 Career Direction

My goal is to grow into a strong **Full Stack / Backend Engineer** capable
of designing, developing, deploying, and scaling production-grade systems.

I'm particularly interested in the intersection of:

```text
Full Stack Development
          +
Backend Engineering
          +
System Design
          +
Cloud Infrastructure
          +
Data Analytics
          +
AI Integration
```

---

# 📂 GitHub Projects

Some of my current public repositories:

### 🌐 Portfolio

[my_portfolio](https://github.com/muhammedShafiKT/my_portfolio)

### ⚛️ React Projects

[React-Ecommerce-project](https://github.com/muhammedShafiKT/React-Ecommerce-project)

[changetheme-by-hooks](https://github.com/muhammedShafiKT/changetheme-by-hooks)

[fetch-quotes-using-hooks](https://github.com/muhammedShafiKT/fetch-quotes-using-hooks)

[react-router-home-page](https://github.com/muhammedShafiKT/react-router-home-page)

### 📝 JavaScript Projects

[todoapp](https://github.com/muhammedShafiKT/todoapp)

---

# 📫 Connect With Me

<p align="center">

<a href="https://github.com/muhammedShafiKT">
<img src="https://img.shields.io/badge/GitHub-muhammedShafiKT-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="mailto:muhammedshafikt85@gmail.com">
<img src="https://img.shields.io/badge/Email-muhammedshafikt85%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</p>

---

<h3 align="center">
  Building • Learning • Shipping 🚀
</h3>

<p align="center">
  <i>Always learning. Always building.</i>
</p>
