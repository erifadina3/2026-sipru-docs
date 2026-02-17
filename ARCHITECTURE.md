# SIPRU – Architecture Documentation

## System Overview
SIPRU adalah sistem peminjaman ruangan kampus yang digunakan untuk
mencatat, mengelola, dan menelusuri data peminjaman ruangan.

## Technology Stack
- Frontend: React
- Backend: ASP.NET Core Web API
- Database: PostgreSQL

## Architecture Overview
Frontend → REST API → Backend Controller → Entity Framework Core → PostgreSQL

Sistem menggunakan layered architecture dengan prinsip separation of concerns.

