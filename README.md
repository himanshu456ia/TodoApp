# Task Manager Application

## Project Overview
This is a task management application built using **Next.js**, **Clerk** for authentication, and **Styled Components** for a responsive UI. It allows users to create, manage, and organize tasks efficiently.

## Features
- User authentication with **Clerk**
- Task creation and management
- Responsive design using **Styled Components**

## Tech Stack
- **Next.js**
- **Clerk** for authentication
- **Styled Components**
- **Axios**

## Prerequisites
- **Node.js** (v14 or later)
- Clerk account for authentication

## Getting Started

### 1. Clone the Repository
```bash
https://github.com/himanshu456ia/TodoApp.git
cd TodoApp
npm install
```
## 2. Set Up Environment Variables

Create a file named .env.local in the root directory of the project. This file will store your environment variables. Add the following lines to .env.local:
```bash
NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
CLERK_API_KEY=<your-clerk-api-key>
```
Make sure to replace <your-clerk-frontend-api> and <your-clerk-api-key> with your actual Clerk API credentials.
## 3. Run the Development Server

To start the development server, use the following command:

```bash

npm run dev
```
