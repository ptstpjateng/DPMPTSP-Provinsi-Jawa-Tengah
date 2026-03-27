<div align="center">
  <img src="https://github.com/ptstpjateng/DPMPTSP-Provinsi-Jawa-Tengah/blob/main/images/logo.webp" alt="DPMPTSP Logo" width="120" />

  # 🏢 DPMPTSP GovTech Ecosystem
  **Dinas Penanaman Modal dan Pelayanan Terpadu Satu Pintu**

  [![Ecosystem](https://img.shields.io/badge/Ecosystem-GovTech-0ea5e9)](#)
  [![Architecture](https://img.shields.io/badge/Architecture-Microservices-success)](#)
  [![Security](https://img.shields.io/badge/Security-Data%20Encrypted-critical)](#)

  *Transformasi Digital Pelayanan Publik & Investasi Daerah yang Clean, Robust, dan User-Centric.*
</div>

---

## 🚀 Visi Teknologi Kami
Repositori ini memuat ekosistem perangkat lunak terintegrasi milik DPMPTSP. Kami berfokus pada pengembangan *software* yang mengutamakan **keamanan data (UU PDP)**, **UI/UX yang seamless**, dan **skalabilitas tinggi**. Dari pelayanan perizinan publik hingga manajemen tata kelola internal, infrastruktur kami dibangun untuk memastikan *zero-downtime* dan *error handling* yang presisi.

---

## 🌐 Portofolio Sistem Inti (Core Systems)

### 1. [SIAP Jateng (Sistem Informasi Aplikasi Perizinan)](https://perizinan.jatengprov.go.id)
**Status: Production/Live** | **Domain:** Pelayanan Publik Non-OSS
SIAP Jateng adalah tulang punggung pelayanan perizinan daerah yang tidak ter- *cover* oleh sistem OSS RBA pusat. 
* **Fokus:** Pemrosesan izin sektoral daerah dengan alur birokrasi digital yang transparan dan *traceable*.
* **Keunggulan:** *Form validation* berlapis untuk mencegah *garbage data*, integrasi Tanda Tangan Elektronik (TTE), dan pelacakan status dokumen secara *real-time*.

### 2. [CJIP (Central Java Investment Platform)](https://cjip.jatengprov.go.id)
**Status: Production/Live** | **Domain:** Promosi & Manajemen Investasi
Portal pintar yang menghubungkan potensi daerah dengan investor domestik dan global.
* **Fokus:** Pemetaan spasial (GIS) untuk peluang investasi, direktori proyek *ready-to-offer*, dan interaksi proaktif dengan calon penanam modal.
* **Keunggulan:** Antarmuka visual yang sangat responsif, mendukung *multi-language*, dan menyajikan analitik data ekonomi yang *clean* untuk meyakinkan investor.

### 3. [INTAN (Sistem Informasi Tata Kelola Internal)](https://intan.dpmptsp.jatengprov.go.id)
**Status: Production/Live** | **Domain:** HRIS & Back-Office Management
Mesin penggerak efisiensi ASN dan pegawai di lingkungan DPMPTSP.
* **Fokus:** Manajemen kepegawaian, penilaian kinerja (KPI), pencatatan agenda dinas, manajemen asset,  dan otomatisasi administrasi kepegawaian.
* **Keunggulan:** Arsitektur *backend* yang *robust* dengan *dashboard* operasional yang intuitif, memangkas red tape internal dan memastikan produktivitas tim pelayanan tetap maksimal.
---

## 🌟 Under Development

### 4. BIMA-AI (Business Investment & Management Assistant)
**Status: MVP / Hackathon Project** | **Domain:** AI-Driven Public Service
Solusi *Omnichannel* yang mentransformasi kerumitan birokrasi OSS RBA menjadi pengalaman percakapan *natural language*. BIMA-AI memandu UMKM dari fase *Pre-Licensing* hingga *Post-Licensing*.
* **Tech Stack:** TALL Stack (Core & Filament Admin), Next.js & React Native (Frontend Wizard), Google Gemini 2.5 API (NLP Engine), Docker.
* **Inovasi Krusial:** Menerapkan arsitektur **Retrieval-Augmented Generation (RAG)** yang mematikan risiko AI berhalusinasi, memastikan setiap rekomendasi KBLI dan syarat perizinan ditarik murni dari *database* hukum daerah (*Single Source of Truth*).

---

## 🛠️ Standar Engineering & Arsitektur

Kami mengadopsi standar pengembangan *enterprise-grade*:
1. **Clean Architecture:** Pemisahan *frontend* dan *backend* via REST API terpusat untuk kemudahan pemeliharaan dan ekspansi lintas *platform* (Web/Mobile).
2. **High Availability:** Penggunaan *Queue System* dan lingkungan *containerized* (Docker) untuk menangani lonjakan *traffic* secara efisien.
3. **Data Security First:** Sanitasi *input* ketat terhadap potensi *SQL Injection* maupun *AI Prompt Injection*, serta enkripsi penuh pada data identitas warga dan dokumen perizinan.

<div align="center">
  <i>Membangun birokrasi cerdas melalui baris kode yang elegan dan aman.</i>
</div>
