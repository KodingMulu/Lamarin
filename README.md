# 🚀 Lamar.in - AI Career Assistant
Lamar.in adalah asisten karir berbasis AI untuk membuat surat lamaran kerja profesional secara instan. Proyek ini menerapkan Service-Oriented Architecture (SOA) yang memisahkan layanan Frontend (Next.js), Backend Core (User/Quota System), dan Microservice AI (Google Gemini Integration).

## 🏗️ Arsitektur Sistem
1.  Frontend Service (`frontend`)
    * Dibangun dengan Next.js.
    * Berfungsi sebagai antarmuka user (UI/UX).
2.  Backend Core Service (`backend`)
    * Dibangun dengan Express.js & Prisma ORM.
    * Mengatur Manajemen User, Autentikasi, Database, dan Sistem Kuota.
3.  AI Microservice (`microservice`)
    * Dibangun dengan Express.js.
    * Layanan terisolasi untuk Prompt Engineering ke Google Gemini API & PDF Generation.
  
## ✨ Fitur Unggulan
1.  AI Auto-Generate: Membuat surat lamaran yang personal dan rapi dalam hitungan detik.
2.  Sistem Kemitraan Kampus (B2B):
    -  User umum (Gmail) dibatasi kuota (Freemium).
    -  User mahasiswa (@univ.ac.id) otomatis mendapatkan Unlimited Access.
3.  History & Export: Simpan riwayat surat dan download dalam format PDF.
4.  Separation of Concerns: Beban proses AI yang berat tidak mengganggu performa login/register.
5.  AI ATS Scanner & Reviewer:
    -  Mengunggah file CV (PDF) untuk dianalisis oleh AI.
    -  Memberikan Skor Kelayakan (0-100).
    -  Memberikan Saran Perbaikan Spesifik (Actionable Insights) untuk meningkatkan peluang lolos screening mesin ATS.

## 🛠️ Tech Stack
1.  Runtime: Node.js (JavaScript).
2.  Frontend: Next.js, Tailwind CSS, Axios.
3.  Backend: Express.js, PostgreSQL, Prisma, JWT.
4.  AI Engine: Google Gemini API (@google/generative-ai).
5.  Tools: Git, NPM Workspaces.

*Dibuat untuk Tugas Besar Mata Kuliah Pemrograman Berorientasi Service.*
