# Menu Scanner - AI Powered Timetable Analyzer

A modern web application that allows you to take a photo of a food timetable or menu and instantly see what meals are available for the current day.

![App Preview](https://github.com/HardikSingh201/Menu-Scanner/blob/main/Screenshot%202026-02-06%20125609.png?raw=true/https://github.com/HardikSingh201/Menu-Scanner/blob/main/Screenshot%202026-02-06%20125643.png?raw=true)

## Features
- **AI Processing**: Automatically extracts meal data from images using GPT-4 Vision.
- **Daily View**: Shows Breakfast, Lunch, and Dinner for the current day.
- **Timetable Management**: Upload and manage multiple schedules.

## Tech Stack
- **Frontend**: React, Tailwind CSS, Shadcn UI
- **Backend**: Node.js, Express
- **Database**: PostgreSQL with Drizzle ORM
- **AI**: OpenAI GPT-4o API

## Installation & Local Setup

To run this project on your local machine, follow these steps:

### 1. Prerequisites
- [Node.js](https://nodejs.org/) (v20 or higher)
- [PostgreSQL](https://www.postgresql.org/) database
- [OpenAI API Key](https://platform.openai.com/)

### 2. Clone the repository
```bash
git clone https://github.com/yourusername/MenuScanner.git
cd MenuScanner
```

### 3. Install dependencies
```bash
npm install
```

### 4. Environment Setup
Create a `.env` file in the root directory and add the following:
```env
DATABASE_URL=your_postgresql_connection_string
OPENAI_API_KEY=your_openai_api_key
```

### 5. Database Setup
Push the database schema:
```bash
npm run db:push
```

### 6. Run the application
```bash
npm run dev
```
The app will be available at `http://localhost:5000`.

## Files Included in this Repository
- `client/`: React frontend source code and assets.
- `server/`: Express backend API and database storage logic.
- `shared/`: Shared TypeScript types and database schema.
- `package.json`: Project dependencies and scripts.
- `tailwind.config.ts` & `postcss.config.js`: Styling configuration.
- `tsconfig.json`: TypeScript configuration.
- `vite.config.ts`: Frontend build configuration.
- `drizzle.config.ts`: Database migration settings.
