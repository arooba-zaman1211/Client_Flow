# ClientFlow CRM Architecture

## Goal
Internal dashboard SaaS for managing leads, notes, follow-ups, and notifications.

## Frontend
Next.js App Router for authenticated dashboard UI.

## Backend
Express REST API with layered architecture:
- controller
- service
- repository

## Database
PostgreSQL with Prisma ORM.

## Core modules
- auth
- users
- leads
- followups
- notifications

## Development approach
Vertical slices:
1. Auth + dashboard
2. Leads
3. Notes
4. Assignment
5. Followups
6. Notifications
