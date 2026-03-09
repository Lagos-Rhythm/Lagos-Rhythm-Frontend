# Project Tech Stack

This document outlines the core technologies, libraries, and services used in this project.

---

# Core Framework

- **Next.js 16** – React framework for building the frontend application
- **React 19** – UI library for building component-based interfaces
- **TypeScript** – Static typing for better developer experience and reliability

---

# Styling & UI

- **TailwindCSS v4** – Utility-first CSS framework
- **shadcn/ui** – Component system built on top of Radix UI
- **Radix UI** – Accessible headless UI primitives
- **Lucide React** – Icon library
- **class-variance-authority (CVA)** – Component variant management
- **clsx** – Conditional className utility
- **tailwind-merge** – Merges Tailwind classes safely
- **tw-animate-css** – Animation utilities for Tailwind

---

# State & UX

- **react-hot-toast** – Toast notifications for UI feedback

---

# Backend Services

The project uses external backend services instead of a monolithic backend.

### Authentication & Database
- **Supabase**
  - User authentication
  - PostgreSQL database
  - API access layer

### File Storage
- **Cloudinary**
  - Media storage
  - Image optimization
  - CDN delivery

---

# Development Tools

- **ESLint** – Linting and code quality
- **PostCSS** – CSS transformation
- **TypeScript** – Static type checking

---

# Architecture

The project follows a **separated architecture**:

- Frontend → Next.js application
- Backend services → Supabase
- File storage → Cloudinary

This approach improves:

- Scalability
- Maintainability
- Performance
- Developer collaboration

---

# Package Manager

- **npm**

---



# Other tools
- Zustand – Global state management