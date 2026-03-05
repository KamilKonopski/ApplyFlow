# ApplyFlow - Job Application Manager

ApplyFlow is a modern web application designed to help users manage job applications and track the recruitment process in one place.

When searching for a job, it is easy to lose track of:

- where you sent your CV  
- the current status of a recruitment process  
- when you should follow up with a recruiter  
- whether you have already applied to a specific company  

ApplyFlow solves this problem by turning the job search process into a clear and organized application pipeline, similar to CRM systems used in sales.

The application is designed as a practical MVP focused on the most important features needed by people actively looking for a job.

---

# Application Purpose

The goal of ApplyFlow is to simplify managing the recruitment process by providing one place where users can:

- store all job applications  
- track recruitment status updates  
- save notes and recruiter feedback  
- manage upcoming actions in the recruitment process  

This makes the job search process more organized and easier to analyze.

---

# Technology Stack

## Frontend

- React  
- TypeScript  
- Vite  
- Mantine UI  
- Redux Toolkit + RTK Query  
- React Hook Form + Zod  
- Recharts  

## Backend

- .NET 8 Web API  
- Entity Framework Core  
- PostgreSQL  
- JWT Authentication  
- FluentValidation  

---

# Main Features

## Dashboard

The dashboard provides a quick overview of your job search activity.

It includes:

- number of active recruitment processes  
- total number of applications  
- recently added applications  
- a chart showing application status distribution  

This allows users to quickly understand the current state of their job search.

---

## Application Management

Each application stores key information about the recruitment process, such as:

- company name  
- job position  
- location  
- source of the job listing (e.g. LinkedIn, job board, referral)  
- application date  
- current recruitment status  
- recruiter messages  
- salary range (optional)

Applications can be:

- added  
- edited  
- viewed in a structured table  

---

## Recruitment Pipeline

ApplyFlow uses a recruitment pipeline to visually represent the progress of applications.

Example stages:

- Wishlist  
- Applied  
- HR Interview  
- Technical Interview  
- Offer  
- Rejected  

This allows users to quickly see how many applications are active and which stage they are currently in.

---

## Duplicate Application Detection

When adding a new application, the system checks whether the user has already applied to the same company for the same position.

If a duplicate is detected, the user receives a notification with information about the previous application and its status.

This helps avoid accidentally applying multiple times to the same job offer.

---

## Next Action Reminders

Each application can include a **next action date**.

For example:

- sending a follow-up message  
- preparing for an interview  
- replying to a recruiter  

If the selected date arrives, the application will be marked as requiring action.

---

## Notes

The application allows users to store information in two different ways.

### Application Notes

Each application can include its own notes, for example:

- interview impressions  
- questions asked during the interview  
- company information  
- recruiter feedback  

### General Notes

A separate notes section available from the main application menu.

It can be used to store:

- career development ideas  
- companies worth applying to  
- questions for future interviews  
- personal observations about the job market  

---

# Design

The interface is inspired by modern SaaS dashboards and CRM tools.

Key design characteristics:

- clean and minimalist interface  
- modern dashboard layout  
- structured data tables  
- pipeline view similar to kanban boards  

The application supports both **light mode** and **dark mode**.

---

# Author

This project was created as part of a portfolio and as an experiment in building modern SaaS-style web applications.
