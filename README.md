<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

  body {
    font-family: 'Poppins', sans-serif;
  }

  .container {
    padding: 2rem;
    background-color: #f0f2f5;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  }

  .profile-header h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color: #1a1a1a;
    transition: color 0.3s ease-in-out;
  }

  .profile-header h1:hover {
    color: #007bff;
  }

  .profile-header h3 {
    font-weight: 400;
    color: #555;
    animation: fadeInDown 1s ease-in-out;
  }

  .profile-image {
    transition: transform 0.5s ease-in-out;
  }

  .profile-image:hover {
    transform: scale(1.05) rotate(5deg);
  }

  .section-title {
    font-size: 1.5rem;
    font-weight: 600;
    color: #333;
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
    display: inline-block;
  }

  .skill-icons {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    animation: fadeInUp 1s ease-in-out;
  }

  .project-item img {
    border-radius: 10px;
    transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
  }

  .project-item img:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0, 123, 255, 0.2);
  }

  .connect-icons a {
    transition: transform 0.3s ease-in-out;
  }

  .connect-icons a:hover {
    transform: scale(1.1);
  }

  @keyframes fadeInDown {
    from {
      opacity: 0;
      transform: translateY(-20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>

<div class="container" align="center">
  <div class="profile-header">
    <img class="profile-image" src="https://avatars.githubusercontent.com/u/193345457?v=4" alt="Foto Profil Putra" width="180" style="border-radius: 50%; border: 4px solid #fff; box-shadow: 0 0 20px rgba(0, 123, 255, 0.7);">
    <h1>Hai, Saya <span style="color: #007bff;">Putra Arsy Sanjaya Tanjung</span>! 👋</h1>
    <h3>NIM : 2305903040029</h3>
    <h3>Web Developer | Mahasiswa Teknologi Informasi</h3>
  </div>
</div>

---

<div class="container">
  <h2 class="section-title">🚀 Tentang Saya</h2>
  <p align="justify">
    Nama saya <b>Putra Arsy Sanjaya Tanjung</b>. Saya adalah seorang mahasiswa semester 5 di Universitas Teuku Umar, mengambil jurusan <b>Teknologi Informasi</b>. Sebagai seorang Web Developer, saya memiliki passion kuat dalam menciptakan solusi digital yang efisien dan memberikan pengalaman pengguna yang luar biasa. Saya fokus pada <b>Python</b> untuk <i>backend development</i>, <b>JSON</b> untuk pertukaran data, dan <b>HTML</b> untuk membangun struktur yang kokoh. Saya percaya bahwa setiap baris kode adalah kesempatan untuk belajar dan berkreasi.
  </p>
</div>

---

<div class="container">
  <h2 class="section-title">🎓 Riwayat Pendidikan</h2>
  <ul>
    <li><b>S1 Teknologi Informasi</b>, Universitas Teuku Umar (2023 - Sekarang)</li>
    <li><b>SMK Jurusan Multimedia</b>, SMKN 1 Gunung Meriah (2020 - 2023)</li>
    <li><b>Madrasah Tsanawiyah</b>, Pesantren Al - Kausar Al - Akbar Medan (2017 - 2019)</li>
  </ul>
</div>

---

<div class="container">
  <h2 class="section-title">🛠️ Keahlian & Teknologi</h2>
  <br>
  <h4>Bahasa Pemrograman</h4>
  <div class="skill-icons">
    <img src="https://skillicons.dev/icons?i=python,js,html," alt="Languages">
  </div>
  <br>
  <h4>Framework & Library</h4>
  <div class="skill-icons">
    <img src="https://skillicons.dev/icons?i=react,nodejs" alt="Frameworks">
  </div>
  <br>
  <h4>Database</h4>
  <div class="skill-icons">
    <img src="https://skillicons.dev/icons?i=mysql,mongodb,postgresql" alt="Databases">
  </div>
  <br>
  <h4>Tools & Platform</h4>
  <div class="skill-icons">
    <img src="https://skillicons.dev/icons?i=vscode,
