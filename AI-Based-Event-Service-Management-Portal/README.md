# AI-Based Event & Service Management Portal

A student project for event planning and service-request management. It includes an event designer, planner workspace, service operations, approvals, and analytics pages.

## Requirements
- Node.js (LTS) and npm

## Run locally
1. Install dependencies: `npm install`
2. Copy `.env.example` to `.env` and add API keys only if you use AI generation. Never commit `.env`.
3. Start the server: `npm start`
4. Open `http://localhost:3000`

## Important security note
This is an academic/demo project, not a production-ready application. Authentication and authorization are currently implemented in client-side code and browser storage; these can be bypassed. Do not use real passwords, personal information, or confidential records. Before deploying for real users, move authentication and authorization to the server, hash passwords, validate and sanitize all user input, add rate limiting, and restrict static file serving.

## Public repository hygiene
`.env`, dependencies, generated output, local backups, and test/generator scripts are excluded by `.gitignore`. `.env.example` contains placeholders only.
