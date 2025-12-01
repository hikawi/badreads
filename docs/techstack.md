# Tech Stack for Badreads MVP

This document provides recommended technology stacks for building the Badreads
book-tracking application. It highlights three options depending on development
goals: fastest build, standard production stack, and scalable cloud-native design.

---

## Project Goals

- Build a functional and polished MVP
- Support user authentication, book management, reviews, and reading progress
- Include basic admin features (book/user management)
- Deploy to a live environment with CI/CD

---

### **MERN Style (Node + React)**

| Layer | Technology |
|-------|-----------|
| Frontend | Vite + React + TailwindCSS |
| UI | **TailwindCSS + ShadCN UI** |
| Backend | Node.js + Express |
| Auth | JWT + Cookies |
| ORM | Prisma |
| Database | PostgreSQL |


#### **Why to choose**
- You already understand Express and want to deepen backend knowledge
- You want a classic frontend/backend separation architecture
