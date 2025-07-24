# Create a styled HTML portfolio file with improved layout and color
html_content = """
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portofolio Devianti Nur Taufik</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #f1f5f9;
      color: #1e293b;
    }
    header {
      background: #0ea5e9;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    section {
      background: white;
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }
    h1 {
      margin: 0;
      font-size: 36px;
    }
    h2 {
      color: #0ea5e9;
      margin-top: 0;
    }
    ul {
      padding-left: 20px;
    }
    a {
      color: #0284c7;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #64748b;
    }
  </style>
</head>
<body>
  <header>
    <h1>Devianti Nur Taufik</h1>
    <p>Email: <a href="mailto:deviantinurtaufik7801@gmail.com" style="color:white;">deviantinurtaufik7801@gmail.com</a> |
       <a href="https://linkedin.com/in/devianti-nur-taufik" target="_blank" style="color:white;">LinkedIn</a> |
       Cikarang, Kab. Bekasi</p>
  </header>
  <main>
    <section>
      <h2>Tentang Saya</h2>
      <p>Saya adalah individu yang berdedikasi dan berpengalaman dalam bidang pendidikan, administrasi, dan pengelolaan dokumen. Memiliki kemampuan komunikasi yang baik, teliti dalam menyusun laporan pembelajaran, serta terbiasa mengelola arsip fisik maupun digital secara rapi dan terstruktur.</p>
    </section>
    <section>
      <h2>Pengalaman Kerja</h2>
      <ul>
        <li><strong>Sales Marketing</strong> – PT Trimitra Wahana Kreasi (Water Kingdom Mekarsari), Aug 2024 - Sekarang
          <ul>
            <li>Membuat laporan penjualan dan rekap data pengunjung.</li>
            <li>Mengelola database pelanggan dan mitra secara digital dan terstruktur.</li>
            <li>Menyusun anggaran promosi dan dokumen kerja sama.</li>
          </ul>
        </li>
        <li><strong>Admin</strong> – PT Zulva Birro Putri, Feb 2024 - Jun 2024
          <ul>
            <li>Mengelola dokumen penawaran harga, invoice, dan surat jalan.</li>
            <li>Mengatur sistem pengarsipan fisik dan digital.</li>
          </ul>
        </li>
        <li><strong>Guru Pengganti</strong> – SDIT Al-Islamiyah, Oct 2022 - Dec 2022
          <ul>
            <li>Menyusun RPP dan laporan hasil belajar siswa.</li>
            <li>Mengelola arsip administrasi kelas secara tertib.</li>
          </ul>
        </li>
      </ul>
    </section>
    <section>
      <h2>Pendidikan</h2>
      <ul>
        <li><strong>Universitas Presiden</strong>, PGSD – S.Pd (2019–2023), IPK 3.53/4.00</li>
        <li><strong>SMA Negeri 3 Cikarang Utara</strong>, Jurusan IPA (2016–2019)</li>
      </ul>
    </section>
    <section>
      <h2>Organisasi & Volunteer</h2>
      <ul>
        <li><strong>Ketua Divisi Kreatif</strong> – Himpunan Mahasiswa PGSD, 2021</li>
        <li><strong>Anggota Divisi Kemahasiswaan</strong> – Himpunan Mahasiswa PGSD, 2020</li>
        <li><strong>Volunteer</strong> – JFLS Goes to School (Dinas Pendidikan Jawa Barat), 2022</li>
        <li><strong>Volunteer</strong> – Taman Baca “Dari Donasi untuk Literacy”, 2021</li>
      </ul>
    </section>
    <section>
      <h2>Kemampuan</h2>
      <ul>
        <li><strong>Hard Skills:</strong> Microsoft Office, Canva, Desain Konten, Bahasa Inggris</li>
        <li><strong>Soft Skills:</strong> Teliti, Komunikatif, Disiplin, Kooperatif, Adaptif</li>
      </ul>
    </section>
    <section>
      <h2>Beasiswa & Proyek</h2>
      <ul>
        <li><strong>Beasiswa:</strong> Jabar Future Leader Scholarship – Beasiswa penuh (2019)</li>
        <li><strong>Proyek:</strong> Virtual English Coaching, Workshop Canva & Nearpods, Webinar Academic Writing, Program Pendampingan Jabar Future Leader</li>
      </ul>
    </section>
  </main>
  <footer>
    © 2025 Devianti Nur Taufik
  </footer>
</body>
</html>
"""

# Save as a .html file
file_path = "/mnt/data/index.html"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(html_content)

file_path
