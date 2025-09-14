# School ERP Starter

This repository will contain a full-stack School ERP starter (backend + frontend). Initializing repository with README so branches and PRs can be created.

Contents (planned)
- backend/: Express + SQLite REST API with JWT auth, role-based permissions, migration & seed script, and basic tests.
- frontend/: Vite + React + Material UI frontend, JWT-based auth, pages for Students/Teachers/Classes/Attendance/Fees.
- .github/workflows/ci.yml: CI that runs backend tests and builds the frontend.

Quick start (dev)
1. Create the repository on GitHub or push an initial commit (README).
2. Clone the repo locally.
3. Copy the scaffold files into the repository (I provided these earlier).
4. Create and push the feature branch:
   git checkout -b feature/backend-and-mui
   git add .
   git commit -m "feat: add backend & frontend scaffold"
   git push -u origin feature/backend-and-mui

Demo accounts (when backend is migrated)
- admin / password
- teacher / password
