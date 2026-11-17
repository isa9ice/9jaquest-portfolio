# Technical Overview

This document explains 9jaQuest at a **portfolio level**. It intentionally omits production configuration, sensitive schema details, internal access policies, and private application source code.

## Main application areas

| Area | Purpose |
|---|---|
| Authentication and profiles | Allow users to sign in and work with eligible learner profiles |
| Learning library | Organise learning activities by class, subject, and topic |
| Assessments | Let learners select an assessment and complete a question-based attempt |
| Results and review | Present feedback and permit answer review |
| Progress and leaderboard | Display performance summaries and assessment rankings |
| Administration | Provide interfaces for managing educational content and assessment records |

## Conceptual user flow

```text
Sign in
   |
Select learner profile
   |
Explore learning materials or choose an assessment
   |
Complete and submit an attempt
   |
View results and review answers
   |
Track progress
```

## Technologies

- **Next.js and React** for the application and interactive interfaces
- **TypeScript** for application code
- **Tailwind CSS** for styling and responsive layouts
- **Supabase** for authentication and database-backed operations
- **Git / GitHub** for version control
- **Vercel** for a referenced web deployment

## Engineering focus

The project illustrates experience coordinating frontend components with backend services and modelling a multi-step user journey. It includes role-aware application views, authentication flows, and data-driven assessment screens.

This overview is not a security audit or production certification. Backend permissions, source history, data protection, and any prospective public code samples require separate review before disclosure.
