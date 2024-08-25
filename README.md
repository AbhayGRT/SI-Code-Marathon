# SI-Code-Marathon

## Overview

IPL Sponsorship Management is a comprehensive platform designed to manage sponsorships for Indian Premier League (IPL) teams. This project consists of a frontend built with React, a backend powered by .NET, and a PostgreSQL database.

## Tech Stack

- **Frontend:** React
- **Backend:** .NET
- **Database:** PostgreSQL

## Getting Started

Follow these steps to set up and run the application locally:

### 1. Clone the Repository

```bash
git clone <github link>
```

2. Install Dependencies
Frontend: Navigate to the frontend directory and install the required dependencies:

```bash
cd frontend
npm install axios react-router-dom react-bootstrap
```

Backend: Install the necessary packages for the backend:
```bash
cd backend
dotnet add package Npgsql
```
3. Set Up PostgreSQL
Install PostgreSQL if you haven't already.
Create a New Database in PostgreSQL for the application.

5. Configure the Backend
Update Connection String: Edit Sponsorship_Management/Server/appsettings.json and replace the connection string with your PostgreSQL connection details.
Configure CORS and Database Name: Open Program.cs and ensure that CORS and the database name are properly configured according to your setup.

5. Start the Application
Frontend: Navigate to the frontend directory and start the development server:

```bash
cd frontend
npm start
```

Backend: Run the backend server with the following command:
```bash
dotnet run <filename>
```
Note: Replace <filename> with the appropriate .NET project file name if required.
