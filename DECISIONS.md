# Architectural Decisions

This document tracks key technical decisions made in this project.  
Each entry should answer **why** a decision was made, not just **what** was done.

---

## 1. Framework: React + Vite + TypeScript
- **Why**: React is widely used and in demand; Vite provides fast dev experience; TypeScript enforces type safety and better maintainability.

---

## 2. Code Quality Tooling
- **ESLint + Prettier + EditorConfig** to enforce consistent style and catch issues early.
- **Husky + lint-staged** to prevent bad commits.
- **Why**: Professional teams enforce code hygiene at commit time.

---

## 3. Testing Strategy
- **Frontend**: Vitest + React Testing Library + MSW for mocking API.
- **Backend**: Jest + Supertest.
- **Why**: Unit and integration tests ensure confidence when refactoring.

---

## 4. State Management
- Start with local `useState` and `useReducer`.
- Migrate to **Redux Toolkit** as app grows.
- **Why**: Demonstrates progression from simple to scalable patterns.
- **Status**: Planned (Phase 2)

---

## 5. API Architecture
- **REST API** with Express + MongoDB.
- **Auth**: JWT (HTTP-only cookie).
- **Why**: Common and realistic stack; covers most job requirements.
- **Status**: Planned (Phase 5)

---

## 6. Deployment Strategy
- **Frontend**: Vercel (simple + free tier).
- **Backend**: Railway or Render (free tier, quick deploy).
- **Why**: Matches common industry setups for small projects.
- **Status**: Planned (Phase 7)