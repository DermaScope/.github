<div align="center">

DermaScope adalah proyek capstone yang dibuat untuk Coding Camp 2026 powered by DBS Foundation. Platform ini membantu pengguna melakukan pemindaian kulit awal, meninjau informasi risiko berbasis AI, menemukan klinik terdekat, dan melacak riwayat pemindaian dalam satu sistem yang terpadu.

</div>

> Disclaimer medis: DermaScope dirancang untuk edukasi dan dukungan skrining awal. Platform ini bukan pengganti diagnosis, perawatan, atau konsultasi medis profesional dengan tenaga kesehatan tersertifikasi.

## Tim

Dibuat oleh Tim PSU288 untuk Coding Camp 2026 powered by DBS Foundation.

| Full Stack                                                                                                                                                | AI Engineer                                                                                                                              | Data Science                                                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Muhammad Brillian Mujahid Kamal &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/muhammad-brillian-mujahid-kamal) | Raymond Surya Setiawan &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/raymond-surya-9919321b3) | Leilani Najma Rachmawati &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/leilani-najma-rachmawati-b1421a28b) |
| Yusuf Saputrah &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/yusufsaputrah)                                    | Rizky Irswanda Ramadhana &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/rizky-irswanda)        | Rofiatul Qosimah &nbsp; [![small-colored-linkedin](assets/icon/linkedin.svg)](https://www.linkedin.com/in/rofiatulqosimah)                            |

## Tema Proyek

DermaScope mendukung tema **Healthy Lives & Well-being** dengan membantu pengguna lebih sadar terhadap potensi risiko kulit dan mendorong konsultasi tepat waktu dengan tenaga kesehatan profesional.

## Yang Kami Bangun

DermaScope berfokus pada peningkatan kesadaran kesehatan kulit yang mudah diakses melalui sistem web, backend, data, dan machine learning yang saling terintegrasi.

- **AI Skin Scan**: unggah gambar kulit dan data klinis pendukung untuk mendapatkan hasil klasifikasi berbasis AI.
- **Risk Triage**: menggabungkan output model dan data gejala menjadi rekomendasi risiko yang praktis.
- **Clinical Chat**: ajukan pertanyaan edukatif seputar kondisi kulit melalui asisten AI.
- **Klinik Terdekat**: cari dan lihat klinik terdekat melalui peta interaktif.
- **Riwayat Scan**: simpan hasil scan sebelumnya dan ekspor laporan kesehatan pengguna.
- **Data-Driven Model Development**: menganalisis HAM10000, menyiapkan dataset hasil pemrosesan, melatih model TensorFlow multi-input, dan menyajikannya melalui FastAPI.

## Tech Stack

| Repository                                                                       | Cakupan                                                               | Teknologi Utama                   |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------- |
| [Front-End](https://github.com/DermaScope/Front-End-FS)                          | Aplikasi web pengguna, UI scan, UI chat, peta klinik, riwayat, profil | React, Vite, Tailwind CSS         |
| [Back-End](https://github.com/DermaScope/Backend-FS)                             | REST API, autentikasi, riwayat scan, integrasi chatbot, akses gambar  | Node.js, Express, PostgreSQL      |
| [AI Inference](https://github.com/Capstone-Project-CC26-PSU288/inference-server) | API penyajian model untuk prediksi dan triage                         | FastAPI, TensorFlow, Docker       |
| [Model Development](https://github.com/Capstone-Project-CC26-PSU288/ai-engineer) | Notebook training model dan artefak Keras hasil ekspor                | TensorFlow, Keras, EfficientNetB0 |
| [Data Science](https://github.com/Capstone-Project-CC26-PSU288/data-science)     | EDA, data wrangling, dashboard, feature engineering, A/B testing      | Python, Pandas, Streamlit         |

## Pratinjau Produk

<table>
  <tr>
    <td><strong>Landing Page</strong><br />Halaman awal publik yang memperkenalkan pemindaian kulit berbasis AI, manfaat utama, kondisi kulit yang didukung, ulasan, dan disclaimer medis.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshot/1-landing-page.png" alt="Landing page DermaScope" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><strong>Dashboard Beranda</strong><br />Pusat layanan personal bagi pengguna terautentikasi untuk mengakses fitur scan, klinik, chat, dan riwayat.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshot/4-home.png" alt="Halaman beranda DermaScope" /></td>
  </tr>
</table>

## Fitur Utama: AI Skin Scan

<table>
  <tr>
    <td><strong>1. Unggah Gambar</strong><br />Pengguna mengunggah foto area kulit yang terdampak dengan jelas.</td>
    <td><strong>2. Lengkapi Data Klinis</strong><br />Pengguna melengkapi usia, jenis kelamin, area lesi, durasi keluhan, tingkat gatal, dan tingkat nyeri.</td>
    <td><strong>3. Tinjau Hasil</strong><br />Sistem menampilkan kelas prediksi, tingkat confidence, status risiko, dan saran penanganan awal.</td>
  </tr>
  <tr>
    <td width="33%"><img src="assets/screenshot/5-a-scan.png" alt="Unggah gambar kulit" /></td>
    <td width="33%"><img src="assets/screenshot/5-b-scan.png" alt="Lengkapi data pendukung scan" /></td>
    <td width="33%"><img src="assets/screenshot/5-c-scan.png" alt="Tinjau hasil scan" /></td>
  </tr>
</table>

## Fitur Penting Lainnya

<table>
  <tr>
    <td><strong>Login</strong><br />Masuk dengan email/password dan Google, disertai pesan privasi, aksesibilitas, dan standar medis.</td>
    <td><strong>Registrasi</strong><br />Halaman pembuatan akun untuk pengguna baru yang ingin menggunakan pengalaman awal kesehatan kulit DermaScope.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshot/2-login.png" alt="Halaman login" /></td>
    <td width="50%"><img src="assets/screenshot/3-register.png" alt="Halaman registrasi" /></td>
  </tr>
  <tr>
    <td><strong>Klinik Terdekat</strong><br />Peta interaktif dan daftar klinik untuk membantu pengguna menemukan fasilitas kesehatan terdekat.</td>
    <td><strong>Clinical Chat</strong><br />Pengalaman chat AI edukatif dengan disclaimer medis yang jelas dan aksi cepat.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshot/6-clinics.png" alt="Peta klinik terdekat" /></td>
    <td width="50%"><img src="assets/screenshot/7-chat.png" alt="Asisten clinical chat" /></td>
  </tr>
  <tr>
    <td><strong>Riwayat Scan</strong><br />Tampilan historis untuk diagnosis sebelumnya, confidence score, dan akses ekspor laporan.</td>
    <td><strong>Pengaturan Profil</strong><br />Identitas pengguna, progres monitoring, status keamanan, dan ekspor data.</td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screenshot/8-history.png" alt="Riwayat scan" /></td>
    <td width="50%"><img src="assets/screenshot/9-profile.png" alt="Pengaturan profil pengguna" /></td>
  </tr>
</table>
