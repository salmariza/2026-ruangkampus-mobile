# 2026-ruangkampus-mobile

Aplikasi mobile untuk RuangKampus (sistem booking ruangan kampus). Repo ini fokus ke sisi mobile: tampilan, konsumsi API backend, serta implementasi CRUD + dokumentasi dengan prinsip yang setara seperti backend.

---

## Scope & Goal
- Menyediakan aplikasi mobile untuk:
  - Melihat daftar ruangan
  - Membuat peminjaman/booking ruangan
  - Melihat daftar booking & statusnya (Pending / Approved / Rejected)
  - (Opsional sesuai kebutuhan) Update / Cancel booking
- Mengikuti standar:
  - Struktur folder rapi & konsisten
  - Logika CRUD jelas
  - Dokumentasi lengkap
  - Task mobile dicatat di GitHub Project Board 

---

## Tech Stack

- Flutter (Dart)
- HTTP Client: `dio` / `http` 
- State Management: `provider` / `bloc` / `riverpod` 
- Code generation (opsional): `json_serializable`

---

## Prerequisites
- Flutter SDK (`flutter --version`)
- Android Studio / VS Code + Flutter extension
- Emulator Android / device fisik

---

## Setup & Run
1. Clone repo
   ```bash
   git clone <repo-url>
   cd 2026-ruangkampus-mobile

2. Install dependencies
flutter pub get

3. Jalankan di emulator/device
flutter run
