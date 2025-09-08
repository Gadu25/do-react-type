
A full-stack ToDo application built with **React + TypeScript + Vite**.  
This project is structured to simulate a real-world production-grade workflow while practicing **clean code, testing, and DevOps discipline**.

## 🚀 Features (Planned by Phase)
- **Phase 1**: Local ToDo list (create, delete, list, detail view). ⌛
- **Phase 2**: State management with Redux Toolkit.
- **Phase 3**: Forms with validation (React Hook Form + Zod).
- **Phase 4**: Mocked REST API integration.
- **Phase 5**: Backend with Node.js + Express + MongoDB.
- **Phase 6**: Full-stack integration with authentication.
- **Phase 7**: Production readiness (Docker, CI/CD, deployment).
- **Phase 8**: Migration to Next.js.

## 🛠 Tech Stack
- **Frontend**: React 18, TypeScript, Vite
- **State Management**: Redux Toolkit, RTK Query
- **Forms & Validation**: React Hook Form, Zod
- **Backend**: Node.js, Express, MongoDB
- **Testing**: Vitest, React Testing Library, MSW, Supertest (backend)
- **Tooling**: ESLint, Prettier, Husky, lint-staged, GitHub Actions
- **Deployment**: Vercel (frontend), Railway/Render (backend)

## 📂 Project Structure
├── src/ # Frontend source code

│ ├── components/ # Reusable UI components

│ ├── pages/ # Page-level components

│ ├── hooks/ # Custom hooks

│ ├── store/ # Redux slices

│ ├── types/ # Global TypeScript types

│ └── tests/ # Unit + integration tests

├── api/ # Backend (Node + Express + MongoDB)

├── .github/workflows/ # CI/CD pipelines

├── README.md

└── DECISIONS.md

## 🔧 Setup
```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Run tests
npm run test

# Build for production
npm run build
✅ Conventions
Use TypeScript everywhere (noImplicitAny: true).

All code changes require:

Passing lint & formatting (npm run lint).

Passing unit tests (npm run test).

Clear commit message (Conventional Commits).

Document major decisions in DECISIONS.md.