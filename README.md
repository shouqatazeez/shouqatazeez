# Hey, I'm Shouqat!

Full-stack developer building scalable web applications, secure backend systems, and AI-powered solutions. I focus on clean architecture, real-world problem solving, and modern web technologies. B.Tech in Computer Science Engineering (2026).

## Featured Projects

### <a href="https://myhiretrack.vercel.app/"><u>HireTrack</u></a>

An AI-powered job application tracking platform designed to replace disorganized spreadsheets with a smart, centralized dashboard.

* **Core Architecture:** React 19 + FastAPI (Python) + PostgreSQL (Neon) + Google Gemini AI.
* **Key Technical Implementations:**
  * Engineered a secure REST API with JWT authentication, bcrypt password hashing, and strict user-scoped database isolation.
  * Integrated Google Gemini AI for resume-to-job match scoring, cover letter generation, and interview coaching with AI-powered feedback.
  * Developed a real-time analytics dashboard featuring 7-day activity charts, application pipelines, and Google Calendar integration for interview reminders.
  * Implemented PDF resume parsing, CSV export, drag-and-drop uploads, and client-side search with multi-status filtering.
  * Built an AI Referral Message Generator that produces personalized Email/DM outreach and LinkedIn connection notes, tailored to the user's resume and target job description.

### <a href="https://myinvotrack.vercel.app/"><u>InvoTrack</u></a>

A full-stack invoice management system for small businesses — handles customers, products, billing with tax/discount, PDF invoices, AI payment reminders, and revenue tracking.

* **Core Architecture:** Next.js 16 (App Router) + TypeScript + Prisma 7 + PostgreSQL (Neon) + NextAuth + Google Gemini AI + shadcn/ui.
* **Key Technical Implementations:**
  * Built a complete billing workflow with multi-line item invoices, automatic GST/tax calculation, discount handling, and sequential numbering (INV-001, INV-002).
  * Implemented server-side PDF generation using jsPDF with branded headers, styled line-item tables, and color-coded status badges.
  * Integrated Google Gemini AI to generate personalized payment reminder messages (WhatsApp + Email) with one-click send via Resend.
  * Designed a real-time dashboard with revenue analytics, invoice status breakdown charts, and clickable recent invoices.
  * Engineered multi-tenant data isolation with userId-scoped queries, JWT session management, and route-level middleware protection.
  * Added CSV export, search/filter by status, and status lifecycle management (UNPAID → PAID/OVERDUE) across full CRUD for customers, products, and invoices.

### <a href="https://jobhive-gamma.vercel.app"><u>JobHive</u></a>

A full-stack job board platform connecting job seekers with employers through role-based dashboards, real-time search, and applicant management.

* **Core Architecture:** Next.js 16 (App Router) + TypeScript + React 19 + Prisma 7 + PostgreSQL (Neon) + NextAuth + shadcn/ui + Tailwind CSS 4.
* **Key Technical Implementations:**
  * Designed a role-based access system (Seeker/Employer) with JWT sessions, protected routes, and role-aware API endpoints.
  * Built a job search engine with multi-filter support (keyword, location, category, job type) and server-side query composition.
  * Implemented an employer applicant management panel with inline Accept/Reject actions and real-time status updates via PATCH API.
  * Engineered real-time form validation with on-blur + while-typing feedback for salary format enforcement.
  * Developed a responsive landing page with featured jobs grid, latest jobs list, company directory, and category browsing.
  * Set up a GitHub Actions CI/CD pipeline with lint, build, and automated Vercel production deployments on push to main.

---

## Technical Capabilities

* **Languages:** JavaScript, TypeScript, Python, SQL, Java
* **Frontend:** React.js, Next.js, Tailwind CSS, Shadcn/UI, Framer Motion, Recharts
* **Backend:** Next.js API Routes, FastAPI, Prisma, SQLAlchemy, NextAuth, Google Gemini AI
* **Databases & Storage:** PostgreSQL, Neon, Supabase, Firebase, Cloudinary
* **Tools & Platforms:** Git, GitHub, GitHub Actions, Postman, Vercel, Resend

---

## Links

[Portfolio](https://mohammadshouqatazeez.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/shouqat-azeez-mohammad/) · [Email](mailto:mdshouqatazeez@gmail.com)
