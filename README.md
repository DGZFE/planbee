# Plan Bee - School Management System

A comprehensive school management platform with role-based access control and real-time features.

## Features
- Role-based authentication (Owner, Superintendent, Admin, Teacher, Student)
- Real-time chat functionality
- Registration key system for controlled access
- WebSocket integration for live updates

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Set up environment variables in .env:
```
DATABASE_URL=your_database_url
```

3. Start the development server:
```bash
npm run dev
```

## Hosting Options

1. Vercel:
   - Sign up at vercel.com
   - Install Vercel CLI: npm i -g vercel
   - Run: vercel
   - Set up environment variables in Vercel dashboard

2. Railway:
   - Visit railway.app
   - Connect your GitHub repository
   - Railway will automatically deploy your app
   - Add PostgreSQL database from Railway dashboard

3. Render:
   - Visit render.com
   - Create a new Web Service
   - Connect your repository
   - Add PostgreSQL database from Render dashboard

4. DigitalOcean:
   - Create a new App Platform deployment
   - Connect your repository
   - Add managed PostgreSQL database
   - Configure environment variables

