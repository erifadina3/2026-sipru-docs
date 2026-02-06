# SIPRU – Architecture Documentation

## System Overview
SIPRU adalah sistem peminjaman ruangan kampus yang digunakan untuk
mencatat, mengelola, dan menelusuri data peminjaman ruangan.

## Architecture Overview
Sistem menggunakan arsitektur client-server dengan pemisahan komponen
backend, frontend, dan mobile.

## Components
- Backend: ASP.NET Core Web API
- Frontend: React.js + TypeScript
- Mobile: Flutter
- Version Control: GitHub

## Communication Flow
Frontend dan Mobile berkomunikasi dengan Backend melalui REST API
menggunakan format JSON.
