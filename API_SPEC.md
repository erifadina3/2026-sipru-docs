# API Specification

## Base URL
http://localhost:5153/api

## Endpoints

### GET /peminjaman
Mengambil seluruh data peminjaman.

### GET /peminjaman/{id}

### POST /peminjaman
Request Body:
{
  "namaPeminjam": "Legia",
  "namaRuangan": "Lab 1",
  "keperluan": "Praktikum",
  "status": 0
}

### PUT /peminjaman/{id}

### DELETE /peminjaman/{id}
