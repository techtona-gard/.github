<div align="center">
  <img src="https://github.com/techtona-gard/.github/blob/08957db6f4bb1ad945eb2a76425d98fc115bfe4d/gard-logo-rectangle.png" alt="Techtona Logo" width="256" />

  <h1>Techtona</h1>
  <p><b>Developing GARD (GERD Guard) — Proactive Gut Health Assistant</b></p>
</div>

---

## About Us

Kami adalah **Techtona**, tim pengembang perangkat lunak di balik proyek **GARD (GERD Guard)**. Kami berfokus pada inovasi kesehatan digital preventif untuk mahasiswa Universitas Amikom Yogyakarta.

GARD adalah platform asisten kesehatan lambung yang memanfaatkan arsitektur *Multi-Agent Artificial Intelligence*. Sistem kami menganalisis berbagai metrik pengguna—mulai dari nutrisi makanan, kualitas tidur, tingkat stres, jadwal akademik, hingga riwayat klinis GERD-Q—untuk memberikan kalkulasi risiko medis dan rekomendasi berbasis literatur ilmiah.

## Ecosystem & Repositories

## Ecosystem

<table>
<tr>
<td width="33%">

### 🤖 gard-agent
AI microservice powered by LangGraph, Gemini, RAG, and FastAPI.

<a href="https://github.com/techtona-gard/gard-agent">View Repository →</a>

</td>
<td width="33%">

### ⚙️ gard-be
Backend API, data pipeline, Health Connect, and Calendar integration.

<a href="https://github.com/techtona-gard/gard-be">View Repository →</a>

</td>
<td width="33%">

### 📱 gard-fe
Flutter mobile application with Vision AI and chatbot.

<a href="https://github.com/techtona-gard/gard-fe">View Repository →</a>

</td>
</tr>
</table>

Sistem GARD dibangun dengan arsitektur terdistribusi yang memisahkan antarmuka pengguna, *data pipeline*, dan layanan AI:

- **gard-agent** — AI microservice berbasis LangGraph (Python/FastAPI) dengan arsitektur *Centralized Supervisor*. Terdiri dari Orchestrator, Nutri-Scan, Bio-Rhythm, dan GERD-Expert yang didukung Gemini, RAG (ChromaDB), serta rule engine deterministik.
- **gard-be** — Backend utama berbasis Express.js yang mengelola autentikasi, sinkronisasi data wearable (Google Health Connect), integrasi Google Calendar, dan orkestrasi komunikasi dengan layanan AI.
- **gard-fe** — Aplikasi Flutter yang menyediakan pengalaman pengguna melalui Vision AI untuk analisis makanan, kuesioner GERD-Q, serta AI lifestyle assistant.

## Technology Stack

- **Artificial Intelligence:** Python 3.12, LangGraph, LangChain, Google Gemini API, ChromaDB
- **Backend & Pipeline:** Node.js, Express.js, FastAPI, PostgreSQL
- **Frontend Mobile:** Flutter, Dart
- **External Integrations:** FatSecret API, Google Health Connect, Google Calendar API

## The Team

- **Jati Sri Pamungkas** — Backend Engineer (gard-be)
- **Gede Brawidya Puja Dharma** — Mobile Developer (gard-fe)
- **Arya Andrean Pratama** — Mobile Developer (gard-fe)
- **Rifki Bayu Ariyanto** — AI Software Architect (gard-agent)

---

<div align="center">

**Faculty of Computer Science**  
Universitas Amikom Yogyakarta

</div>
