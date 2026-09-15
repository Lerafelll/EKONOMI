# Product Requirements Document (PRD)

# Econiverse
### Platform Analisis Perilaku Ekonomi Berbasis AI

---

## Document Information

| Item | Detail |
|--------|--------|
| Product Name | Econiverse |
| Version | 1.0 |
| Status | Draft |
| Platform | Web Application |
| Product Master | Team Econiverse |

---

# 1. Product Overview

## Product Vision

Membantu pengguna memahami, memperbaiki, dan mengembangkan kebiasaan ekonomi melalui analisis perilaku, rekomendasi AI, dan sistem gamifikasi yang menarik.

---

## Problem Statement

Banyak orang mengalami kesulitan dalam mengelola perilaku ekonomi mereka karena:

- Tidak memahami pola konsumsi pribadi.
- Tidak mengetahui kelebihan dan kekurangan kebiasaan finansial mereka.
- Sulit mempertahankan konsistensi dalam menabung.
- Kurangnya motivasi untuk memperbaiki kebiasaan ekonomi.

Sebagian besar aplikasi hanya mencatat transaksi tanpa membantu pengguna memahami alasan di balik perilaku mereka.

---

## Solution

Econiverse menggabungkan:

- Economic Personality Test
- AI Financial Coach
- Habit Tracking
- Streak System
- Achievement System

untuk membantu pengguna membangun kebiasaan ekonomi yang lebih baik.

---

# 2. Target Users

## Primary Users

### Mahasiswa

Karakteristik:

- Pendapatan terbatas.
- Sedang belajar mengelola keuangan.

### Freelancer

Karakteristik:

- Pendapatan tidak stabil.
- Membutuhkan kontrol pengeluaran.

### Karyawan

Karakteristik:

- Pendapatan tetap.
- Ingin meningkatkan kualitas finansial.

---

# 3. Product Goals

### Goal 1

Membantu pengguna mengenali tipe perilaku ekonomi mereka.

### Goal 2

Meningkatkan kesadaran terhadap kebiasaan konsumsi.

### Goal 3

Membantu pengguna membangun kebiasaan menabung yang konsisten.

### Goal 4

Memberikan rekomendasi yang dipersonalisasi melalui AI Agent.

---

# 4. Core Features

---

## 4.1 Economic Personality Test

### Description

Pengguna mengisi survei yang dirancang untuk mengidentifikasi tipe perilaku ekonomi.

### Output

Sistem menentukan personality pengguna.

### Personality Types

- The Saver
- The Investor
- The Rational Planner
- The Impulsive Buyer
- The Experience Seeker
- The Risk Taker

### User Story

Sebagai pengguna, saya ingin mengetahui tipe perilaku ekonomi saya agar dapat memahami kebiasaan finansial saya.

---

## 4.2 AI Financial Coach

### Description

AI Agent menganalisis aktivitas dan hasil survei pengguna.

### AI Analysis

- Pola konsumsi
- Konsistensi menabung
- Kebiasaan impulsif
- Kelebihan finansial
- Kekurangan finansial

### User Story

Sebagai pengguna, saya ingin mendapatkan saran yang sesuai dengan kondisi saya agar dapat memperbaiki kebiasaan ekonomi saya.

---

## 4.3 Daily Mission

### Description

Sistem memberikan misi harian kepada pengguna.

### Example

- Menabung Rp5.000
- Tidak melakukan pembelian impulsif
- Menyelesaikan refleksi harian

### Reward

XP dan Progress.

---

## 4.4 Streak System

### Description

Mencatat konsistensi aktivitas pengguna.

### Example

- Saving Streak
- No Impulse Buying Streak
- Daily Check-In Streak

### User Story

Sebagai pengguna, saya ingin melihat progres saya agar lebih termotivasi untuk mempertahankan kebiasaan baik.

---

## 4.5 Achievement System

### Description

Memberikan penghargaan berdasarkan pencapaian pengguna.

### Example Badges

- First Saving
- 7 Day Streak
- Smart Saver
- Financial Explorer
- Financial Master

---

## 4.6 Personality Evolution

### Description

Menampilkan perubahan personality pengguna dari waktu ke waktu.

### Example

```text
Januari:
Impulsive Buyer

Maret:
Balanced Spender

Juni:
Rational Planner
```

### User Story

Sebagai pengguna, saya ingin melihat perkembangan diri saya agar mengetahui apakah kebiasaan ekonomi saya membaik.

---

## 4.7 Economic Dashboard

### Description

Dashboard utama yang menampilkan:

- Personality Type
- AI Insight
- Streak Progress
- Achievement
- Daily Mission

---

# 5. User Journey

## New User

```text
Register
↓
Login
↓
Economic Personality Test
↓
Get Personality Result
↓
Receive AI Analysis
↓
Start Daily Mission
↓
Build Streak
↓
Unlock Achievement
```

---

# 6. MVP Scope

Fitur yang wajib tersedia pada versi pertama:

- Authentication
- Personality Test
- Personality Result
- AI Insight
- Daily Mission
- Streak System
- Dashboard
- Achievement

---

# 7. Success Metrics

## User Engagement

- Pengguna membuka aplikasi minimal 3 kali per minggu.

## Streak Retention

- Minimal 50% pengguna mempertahankan streak selama 7 hari.

## Personality Completion

- Minimal 80% pengguna menyelesaikan personality test.

---

# 8. Future Features

## AI Chat Coach

Pengguna dapat berdiskusi langsung dengan AI.

---

## Community Challenge

Tantangan kelompok antar pengguna.

---

## Economic Leaderboard

Peringkat berdasarkan konsistensi dan pencapaian.

---

## Habit Prediction

AI memprediksi kebiasaan ekonomi pengguna di masa depan.

---

# 9. Tech Stack

## Frontend

- Next.js
- TypeScript
- Tailwind CSS

## Backend

- Next.js API Routes

## Database

- PostgreSQL

## Authentication

- NextAuth

## AI

- OpenAI API / Local AI Model

---

# 10. Development Team

| Role | Responsibility |
|--------|--------|
| Product Master | Requirement & Planning |
| Frontend Developer | UI/UX Development |
| Backend Developer | API & Business Logic |
| Database Engineer | Database Design |
| QA Tester | Testing & Validation |

---

# Status

Draft Version 1.0
