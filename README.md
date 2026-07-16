<div align="center">
  <img src="https://github.com/techtona-gard/.github/blob/08957db6f4bb1ad945eb2a76425d98fc115bfe4d/gard-logo-rectangle.png" alt="Techtona Logo" width="256" />

  <h1>Techtona</h1>
  <p><b>Developing GARD (Gerd Guard) — Proactive Gut Health Assistant</b></p>
</div>

---

## About Us

Kami adalah **Techtona**, tim pengembang perangkat lunak di balik proyek **GARD (Gerd Guard)**. Kami berfokus pada inovasi kesehatan digital preventif untuk mahasiswa Universitas Amikom Yogyakarta. 

GARD adalah platform asisten kesehatan lambung yang memanfaatkan arsitektur *Multi-Agent Artificial Intelligence*. Sistem kami menganalisis berbagai metrik pengguna—mulai dari nutrisi makanan, kualitas tidur, tingkat stres, jadwal akademik, hingga riwayat klinis GERD-Q—untuk memberikan kalkulasi risiko medis dan rekomendasi berbasis literatur ilmiah.

## Ecosystem & Repositories

Sistem GARD dibangun dengan arsitektur terdistribusi yang memisahkan antara antarmuka pengguna, pipa data, dan penalaran AI. Ekosistem kami terdiri dari tiga repositori utama:

* **[gard-agent](https://github.com/techtona-gard/gard-agent)**
    Microservice kecerdasan buatan utama. Dibangun menggunakan arsitektur *Centralized Supervisor* dengan **LangGraph** (Python/FastAPI). Terdiri dari 4 agen otonom (Orchestrator, Nutri-Scan, Bio-Rhythm, GERD-Expert) yang ditenagai oleh model Gemini 2.5 Flash, RAG (ChromaDB), dan Rule-Engine deterministik.
    
* **[gard-be](https://github.com/techtona-gard/gard-be)**
    Sistem backend utama dan *data pipeline*. Berbasis **Express.js (Node.js)**. Bertanggung jawab atas manajemen pengguna, sinkronisasi data sensor perangkat *wearable* (Google Health Connect), pelacakan aktivitas (Google Calendar API), serta orkestrasi pengiriman *payload* ke layanan AI.

* **[gard-fe](https://github.com/techtona-gard/gard-fe)**
    Aplikasi klien untuk platform seluler. Dibangun dengan **Flutter**, menyajikan antarmuka pengguna interaktif yang meliputi pemindai komposisi makanan (Vision AI), kuesioner medis, dan *chatbot* penasihat gaya hidup.

## Technology Stack

* **Artificial Intelligence:** Python 3.12, LangGraph, LangChain, Google Gemini API, ChromaDB (Vector Database)
* **Backend & Pipeline:** Node.js, Express.js, FastAPI, PostgreSQL
* **Frontend Mobile:** Flutter, Dart
* **External Integrations:** FatSecret API, Google Health Connect, Google Calendar API

## The Team

* **Jati Sri Pamungkas** — Backend Engineer (gard-be)
* **Gede Brawidya Puja Dharma** — Mobile Developer (gard-fe)
* **Arya Andrean Pratama** — Mobile Developer (gard-fe)
* **Rifki Bayu Ariyanto** — AI Software Architect (gard-agent)

---

**Fakultas Ilmu Komputer, Universitas Amikom Yogyakarta**
