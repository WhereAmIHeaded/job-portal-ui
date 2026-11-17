# Job Portal UI

React frontend for [Job Portal Backend](https://github.com/WhereAmIHeaded/job-portal), built with Vite, Tailwind CSS, React Router, and Axios.

## Run locally

Use Node.js 22.12 or later and npm. Start the backend separately using its README instructions.

```bash
npm ci
cp .env.example .env.local
npm run dev
```

Open the URL printed by Vite (normally http://localhost:5173). `VITE_API_BASE_URL` defaults to `http://localhost:8080/api`. Restart Vite after changing environment variables. The backend must allow the frontend origin through its CORS configuration.

```bash
npm run build
npm run preview
```

## Application scope

The source includes company and job browsing, registration/login, contact forms, profiles, saved jobs, applications, and administration screens. Some screens use mock data or depend on backend endpoints that may not yet be implemented. The presence of a screen does not establish that its full workflow works with the published backend.

The HTTP client sends the API version in the Accept header and supports bearer tokens and CSRF cookies.

## Project context

This frontend accompanies a course-based Spring Boot learning project using Eazy Bytes examples. Included demonstration accounts and mock records are sample data.

## Repository contents

Commit source, public assets, package.json, and package-lock.json. Dependencies, build output, and local environment files are excluded. Frontend environment variables are visible in the browser; do not put secrets in them.
