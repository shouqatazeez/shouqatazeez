# Hey, I'm Shouqat!

Full-stack developer building scalable web applications, secure backend systems, and AI-powered solutions. I enjoy solving real-world problems through clean architecture and modern web technologies. B.Tech in Computer Science Engineering (2026).


## Featured Projects

### <a href="https://myhiretrack.vercel.app/"><u>HireTrack</u></a>

An AI-powered job application tracking platform designed to replace disorganized spreadsheets with a smart, centralized dashboard.

* **Core Architecture:** React  + FastAPI (Python) + PostgreSQL (NeonDB) + Google Gemini AI.
* **Key Technical Implementations:**
  * Designed secure REST APIs with JWT authentication, bcrypt hashing, user-scoped DB isolation, rate limiting, and input validation to prevent abuse.
  * Integrated Google Gemini AI for match scoring, cover letter generation, interview coaching with answer feedback, and referral message generation (Email, DM, LinkedIn formats).
  * Built a real-time analytics dashboard with 7-day activity charts, application pipelines, Google Calendar integration, PDF parsing, CSV export, and drag-and-drop uploads.
  * Optimized frontend with lazy loading, TanStack Query caching, optimistic UI updates, Framer Motion page transitions, and Vite chunk splitting — reducing initial bundle by 77%.
  * Hardened backend with async Gemini calls, DB-level AI result caching (20s → instant on repeat), GZip compression, connection pooling, and an Error Boundary for crash recovery.

### <a href="https://myinvotrack.vercel.app/"><u>InvoTrack</u></a>

A full-stack invoice management system for small businesses that streamlines customer management, invoicing, AI-powered payment reminders, and revenue tracking.

* **Core Architecture:** Next.js (App Router) + TypeScript + Prisma + PostgreSQL (NeonDB) + NextAuth + Google Gemini AI + shadcn/ui.
* **Key Technical Implementations:**
  * Built a complete billing workflow with multi-line invoices, automatic GST/tax calculation, discount handling, and sequential invoice numbering (INV-001, INV-002).
  * Generated branded PDF invoices using jsPDF with styled layouts, line-item tables, and color-coded status badges.
  * Integrated Google Gemini AI to generate personalized payment reminders for WhatsApp and Email with one-click delivery via Resend.
  * Designed a real-time analytics dashboard with revenue insights, invoice status breakdowns, and recent invoice tracking.
  * Implemented secure multi-tenant data isolation using userId-scoped queries, JWT session management, and route-level middleware protection.
  * Added CSV export, search and filtering by status, and complete CRUD operations for customers, products, and invoices.

### <a href="https://jobhive-gamma.vercel.app"><u>JobHive</u></a>

A full-stack job board platform connecting job seekers and employers through role-based dashboards, intelligent search, and applicant management.

* **Core Architecture:** Next.js (App Router) + TypeScript + React + Prisma + PostgreSQL (NeonDB) + NextAuth + shadcn/ui + Tailwind CSS.
* **Key Technical Implementations:**
  * Designed a role-based access system (Seeker/Employer) with JWT authentication, protected routes, and role-aware API endpoints.
  * Built a job search engine supporting keyword, location, category, and job type filtering with server-side query composition.
  * Implemented an employer applicant management panel with inline Accept/Reject actions and real-time status updates through PATCH APIs.
  * Added real-time form validation with on-blur and while-typing feedback for improved user experience.
  * Developed a responsive landing page with featured jobs, latest openings, company directory, and category browsing.
  * Configured a GitHub Actions CI/CD pipeline for automated linting, builds, and Vercel production deployments.

---

## Technical Capabilities

* **Languages:** JavaScript, TypeScript, Python, SQL, Java, C
* **Frontend:** React.js, Next.js, Tailwind CSS, shadcn/ui, Framer Motion, TanStack Query, Recharts
* **Backend:** FastAPI, Next.js API Routes, Prisma, SQLAlchemy, NextAuth, Google Gemini AI
* **Databases & Storage:** PostgreSQL, MySQL, NeonDB, Supabase, Firebase, Cloudinary
* **Tools & Platforms:** Git, GitHub, GitHub Actions, Postman, Vercel, Google Antigravity, VS Code

---

## Links

[Portfolio](https://mohammadshouqatazeez.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/shouqat-azeez-mohammad/) · [Email](mailto:mdshouqatazeez@gmail.com)
