#  Claude Code Optimized Prompt Pack (Backend: Node.js + TypeScript)

##  Universal Plan Prompt
Act as a senior backend engineer.  
Task: [describe task]  
Give 2–3 approaches with pros/cons and recommend one.  
Do NOT write code.

##  Execution Prompt
Use approach 2. Implement it cleanly.

---

#  Backend Prompts

## 1. Project Setup (Plan First)
Act as a senior backend engineer.  
Set up a Node.js + TypeScript API project.  
Give 2–3 approaches and recommend one. Do NOT write code.

## 2. API Architecture (Plan First)
Act as a senior backend engineer.  
Design the API structure for this service.  
Give 2–3 approaches and recommend one. Do NOT write code.

## 3. Data Model / Schema (Plan First)
Act as a senior backend engineer.  
Design the database schema for this feature.  
Give 2–3 approaches and recommend one. Do NOT write code.

## 4. Auth Design (Plan First)
Act as a senior backend engineer.  
Design authentication and authorization for this API.  
Give 2–3 approaches and recommend one. Do NOT write code.

## 5. API Boilerplate
Set up an Express + TypeScript API with versioned routes, centralized error handling, and a health check.

## 6. Endpoint
Build a production-ready API endpoint using route → controller → service structure.

## 7. CRUD
Create CRUD APIs for this resource using clean, maintainable TypeScript code.

## 8. Validation
Add request validation for params, query, and body with clear errors.

## 9. Error Handling
Refactor to use centralized error handling and consistent API responses.

## 10. Database Integration
Integrate database access with a clean repository or data access layer.

## 11. Prisma
Implement this API using Prisma with clean service-layer usage and proper error handling.

## 12. PostgreSQL
Implement this feature with PostgreSQL using a clean data access pattern.

## 13. Pagination / Filtering
Add pagination, filtering, and sorting with clean query handling.

## 14. Authentication
Build signup, login, token verification, and secure auth flow.

## 15. Authorization
Add role-based authorization middleware and protect routes cleanly.

## 16. File Upload
Build a secure file upload API with validation and clean separation of concerns.

## 17. S3 Upload
Build a file upload API that stores files in S3 with proper validation and error handling.

## 18. Webhook
Build a webhook handler with verification, idempotency, and fast acknowledgement.

## 19. Background Jobs / Queue
Design this feature so heavy work runs asynchronously via a queue or worker.

## 20. Logging
Add structured request and error logging without exposing sensitive data.

## 21. Security
Review and improve API security: validation, auth, error handling, and abuse protection.

## 22. Testing
Add backend tests for services and endpoints using practical, maintainable test structure.

## 23. Production Readiness
Prepare this API for production: config, health checks, graceful shutdown, logging, and error handling.

---

#  Engineering Prompts

## Refactor
Refactor this Node.js + TypeScript API for readability, maintainability, and cleaner separation of concerns. Preserve behavior.

## Optimization
Optimize this API for practical performance and scalability improvements. Avoid over-engineering.

## Bug Fix
Find and fix bugs in this API. Explain root cause and provide corrected code.

## Master Prompt
Review this Node.js + TypeScript API as a senior backend engineer. Improve architecture, validation, error handling, security, maintainability, and performance where it matters. Preserve behavior.

---

#  Workflow

1. Plan (only when needed)  
Give me approaches. Do NOT write code.

2. Decide  
Use approach 2

3. Execute  
Implement it.

4. Improve  
Refactor it.

5. Harden  
Review for security and production readiness.
