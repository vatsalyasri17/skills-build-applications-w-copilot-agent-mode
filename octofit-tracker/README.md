# 🐙 OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite (Port 5173)
└── backend/           # Node.js + Express + TypeScript (Port 8000)
```

## Ports Configuration

- **Frontend**: 5173 (React with Vite)
- **Backend API**: 8000 (Express)
- **MongoDB**: 27017

## Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

## Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

## Prerequisites

- Node.js (v18+)
- MongoDB running on localhost:27017

## Technologies Used

- **Frontend**: React 19, Vite
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB with Mongoose ODM
- **Communication**: REST API with CORS enabled

## Getting Started

1. Start MongoDB
2. Configure `.env` in the backend directory
3. Install dependencies for both frontend and backend
4. Run development servers

Enjoy building with OctoFit Tracker! 🚀
