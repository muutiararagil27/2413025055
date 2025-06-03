<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Tugas Grafika Komputer PTI</title>
  <style>
    body {
      background-color: rgb(216, 156, 202);
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #b66fb4;
      text-align: center;
      padding: 20px 0;
      color: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    ul.nav {
      display: flex;
      justify-content: center;
      list-style-type: none;
      background-color: #d494d1;
      margin: 0;
      padding: 15px;
      gap: 30px;
    }
    ul.nav li a {
      text-decoration: none;
      color: white;
      font-weight: bold;
    }
    ul.nav li a:hover {
      text-decoration: underline;
    }
    section {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }
    .task {
      background-color: #f8f0f8;
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      display: flex;
      gap: 20px;
      align-items: center;
    }
    .task img {
      width: 120px;
      height: 80px;
      object-fit: cover;
      border-radius: 10px;
    }
    .task-content {
      flex-grow: 1;
    }
    .task-content h3 {
      margin-top: 0;
    }
    .task-content a {
      display: inline-block;
      margin-right: 10px;
      margin-top: 5px;
      color: #b66fb4;
      text-decoration: none;
      font-weight: bold;
    }
    .task-content a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      background-color: #b66fb4;
      color: white;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Grafika Komputer - Mutiara Ragil</h1>
  </header>

  <ul class="nav">
    <li><a href="#profil">Profil</a></li>
    <li><a href="#tentang">Tentang</a></li>
  </ul>

  <section id="tugas-section">
    <!-- Tugas akan dimuat lewat JavaScript -->
  </section>

  <section id="profil">
    <h2>Profil</h2>
    <ul style="list-style-type: none; padding-left: 0;">
      <li><strong>Nama:</strong> Mutiara Ragil</li>
      <li><strong>NIM:</strong> 2413025055</li>
      <li><strong>Program Studi:</strong> Pendidikan Teknologi Informasi</li>
      <li><strong>Fakultas:</strong> FKIP</li>
      <li><strong>Universitas:</strong> Universitas Lampung</li>
      <li><strong>Email:</strong> mutiararagil37@email.com</li>
      <li><strong>Domisili:</strong> Lampung, Indonesia</li>
    </ul>
  </section>

  <section id="tentang">
    <h2>Tentang Saya</h2>
    <p>Halo! Saya <strong>Mutiara Ragil</strong>, Seorang Mahasiswa Pendidikan Teknik Informatika,semester 2 yang sedang mendalami dunia grafika komputer. 
      Saat ini, saya sedang mengerjakan website guna untuk memenuhi tugas tugas mata kuliah Grafika Komputer.</p>
  </section>

  <footer>
    <p>Hak Cipta &copy; 2025. Mutiara Ragil</p>
  </footer>

  <script>
    const tugasList = [
      {
        judul: "Tugas 1 - Tokoh Perintis",
        pdf: "https://drive.google.com/file/d/1UjF5fPnt6-KuSOoQ1jQDUZVhDQpUVNEp/view?usp=drive_link",
        video: "https://drive.google.com/drive/folders/1SmCI9GhiOEttwVH35Z_dKMawCYlfgz_U"
      },
      {
        judul: "Tugas 2 - Garis DDA dan Bresenham",
        pdf: "https://drive.google.com/file/d/1kfHhCkZtCS9O8iNLx7O6aMqjYC-xORG7/view?usp=drive_link",
        video: "https://drive.google.com/file/d/1dlJgNKpC0R6tx3h3Tj5FWjeE5EnhgMiL/view?usp=drive_link"
      },
      {
        judul: "Tugas 3 - Garis Lingkaran Mindpoint dan Bresenham",
        pdf: "https://drive.google.com/file/d/17ij0mBjxCNd_OQTcA0UggqENlVAtqiAF/view?usp=sharing",
        video: "https://drive.google.com/drive/folders/1ifqWe3BrKWsJpb5SdWlq-HNq120gNkhW?usp=drive_link"
      },
      {
        judul: "Tugas 4 - Kurva",
        pdf: "https://drive.google.com/file/d/1kCxBFqpes4k5uP_gmWp9fkFuIWDuu4S1/view?usp=drive_link",
        video: "https://drive.google.com/file/d/1Y5v9hXccUeQTBiif8ypnojlXTkstO5Pq/view?usp=drive_link"
      },
      {
        judul: "Tugas 5 - KUIS 1 Persamaan Misteri",
        pdf: "https://drive.google.com/file/d/1OIAVusESfQPXjo4x38QRA_APpROzfM-b/view?usp=drive_link",
      },
      {
        judul: "Tugas 6 - KUIS 2 Matriks Transformasi",
        pdf: "https://drive.google.com/file/d/1shAERd5uuvjj5bzt9N2Z51Klz5ygui47/view?usp=drive_link",
        video: "https://drive.google.com/file/d/1z-_XBeesodeO5_PDHcTSJ3CrVonbHkZo/view?usp=drive_link"
      },
      {
        judul: "Tugas 7 - KUIS 3 Line Clipping Algorithm",
        pdf: "https://drive.google.com/file/d/1NSGa-EWc6a26RkBORbZz3Jfrc9syupil/view?usp=drive_link",
        video: "https://drive.google.com/file/d/191BkbtWXsEJ1puH6h29CzbXLUwOKpvkd/view?usp=drive_link"
      },
      {
        judul: "Tugas 8 - KUIS 4 Polygon Clipping Algorithm",
        pdf: "https://drive.google.com/file/d/1AmCwl0EhrrP2h7XY1VlmHxoz9GkUPikR/view?usp=drive_link",
        video: "https://drive.google.com/file/d/1bpRMIGIjgkV98se5X9djiu4d7cr2l9Ka/view?usp=drive_link"
      },
    ];

    const tugasContainer = document.getElementById("tugas-section");

    tugasList.forEach((tugas, index) => {
      const div = document.createElement("div");
      div.className = "task";
      div.innerHTML = `
        <div class="task-content">
          <h3>${tugas.judul}</h3>
          <a href="${tugas.pdf}" target="_blank">📄 PDF</a>
          <a href="${tugas.video}" target="_blank">🎥 Video</a>
        </div>
      `;
      tugasContainer.appendChild(div);
    });
  </script>

</body>
</html>
