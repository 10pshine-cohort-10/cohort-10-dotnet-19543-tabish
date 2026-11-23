# 10Pearls Shine Task Management Tool

Cohort 10 - .NET Fullstack assignment for Tabish Khalil.

ASP.NET Core (.NET 10) API and React frontend built with Vite and JavaScript.

## Prerequisites

- .NET 10 SDK
- Node.js 22.12+ and npm
- Git

## Run locally

Run each application in a separate terminal from the repository root.

### Backend

```sh
cd backend
dotnet run --launch-profile http
```

API: http://localhost:5223

`GET /api/health` returns `{"status":"Healthy"}`.

### Frontend

```sh
cd frontend
npm ci
npm run dev
```

Open the URL printed by Vite, usually http://localhost:5173.

If PowerShell blocks `npm`, use `npm.cmd`.

## Build and lint

From the repository root:

```sh
dotnet build backend/TaskManagement.Api.csproj --configuration Release
cd frontend
npm run lint
npm run build
```
