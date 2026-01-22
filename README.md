<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Madrasah At-Taklimiah Al-Khairiah</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background-color: #f4f6f9;
            color: #333;
        }
        header {
            background: #004080;
            color: white;
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }
        section {
            margin-bottom: 60px;
        }
        h2 {
            color: #004080;
            border-bottom: 2px solid #004080;
            padding-bottom: 5px;
        }
        ul.staff-list {
            list-style: none;
            padding: 0;
        }
        ul.staff-list li {
            background: white;
            margin: 10px 0;
            padding: 15px;
            border-radius: 6px;
            box-shadow: 0 1px 4px rgba(0,0,0,0.1);
        }
        ul.staff-list strong {
            color: #004080;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table th, table td {
            padding: 12px;
            border: 1px solid #ccc;
            text-align: left;
        }
        table th {
            background: #004080;
            color: white;
        }
        table tr:nth-child(even) {
            background: #f2f2f2;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        .download-btn {
            display: inline-block;
            background: #004080;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }
        .download-btn:hover {
            background: #0066cc;
        }
        footer {
            background: #004080;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Madrasah At-Taklimiah Al-Khairiah</h1>
        <nav>
            <a href="#utama">Utama</a>
            <a href="#profil">Profil</a>
            <a href="#guru">Guru & Staf</a>
            <a href="#aktiviti">Aktiviti</a>
            <a href="#galeri">Galeri</a>
            <a href="#hubungi">Hubungi</a>
        </nav>
    </header>

    <main>
        <section id="utama">
            <h2>Selamat Datang</h2>
            <p>Selamat datang ke laman rasmi Madrasah At-Taklimiah Al-Khairiah. Kami komited melahirkan pelajar cemerlang dalam akademik dan sahsiah.</p>
        </section>

        <section id="profil">
            <h2>Profil Sekolah</h2>
            <p><strong>Madrasah At-Taklimiah Al-Khairiah (MTK)</strong> ialah Sekolah Menengah Agama Rakyat yang ditubuhkan pada tahun 1992, namun akarnya bermula dari tahun 40-an di Kampung Tok Keling, Alor Setar, Kedah. Ia hasil wakaf tanah dan usaha Tuan Guru Hj. Wahab bin Lebai Idris. Kini MTK berperanan sebagai pusat pendidikan agama dan peperiksaan awam seperti SPM, STAM & SMA, didorong oleh sumbangan masyarakat dan menjadi pusat dakwah.</p>
        </section>

        <section id="guru">
            <h2>Guru & Staf</h2>
            <ul class="staff-list">
                <li><strong>Pengetua:</strong> Puan Madihah binti Wahab</li>
                <li><strong>Penolong Kanan 1:</strong> Aryani binti Arshad</li>
                <li><strong>Penolong Kanan 2:</strong> Noor Aimi binti Mohamed</li>
                <li><strong>Penolong Kanan KoKurikulum:</strong> Mohamad Fahmi Ronaldo</li>
            </ul>
        </section>

        <section id="aktiviti">
            <h2>Jadual Aktiviti Sekolah</h2>
            <table>
                <tr>
                    <th>Tarikh</th>
                    <th>Aktiviti</th>
                </tr>
                <tr>
                    <td>19 April 2026</td>
                    <td>MISMAM</td>
                </tr>
                <tr>
                    <td>23 April 2026</td>
                    <td>Kejohanan Sukan Tahunan</td>
                </tr>
                <tr>
                    <td>6 Jun 2026</td>
                    <td>MASSAK</td>
                </tr>
		<tr>
                    <td>14 April- 28 April</td>
                    <td>Pendaftaran Calon Sijil Menengah Agama (SMA) 2026</td>
		</tr>
		<tr>
                    <td>4 Oktober- 8 Oktober</td>
                    <td>Sijil Menengah Agama (SMA) 2026</td>
		</tr>
		<tr>
                    <td>13 September- 22 September</td>
                    <td>Sijil Tinggi Agama (STA) 2026</td>
          

            <!-- Butang Muat Turun PDF -->
            <a href="jadual.pdf" download class="download-btn">📥 Muat Turun Jadual Aktiviti (PDF)</a>
    

        <section id="galeri">
            <h2>Galeri Aktiviti</h2>
            <div class="gallery">
                <img src="images/sukan.jpg" alt="Kejohanan Sukan">
                <img src="images/kokurikulum.jpg" alt="Hari Kokurikulum">
                <img src="images/spm.jpg" alt="Peperiksaan SPM">
                <img src="images/stam.jpg" alt="Peperiksaan STAM">
		<div class="gallery">
 		<img src="img/1.jpg">
  		<img src="img/2.jpg">
  		<img src="img/3.jpg">
		<img src="img/4.jpg">
  		<img src="img/5.jpg">
  		<img src="img/6.jpg">
		<img src="img/7.jpg">
  		<img src="img/8.jpg">
  		<img src="img/9.jpg">
		<img src="img/10.jpg">
  		<img src="img/11.jpg">
  		<img src="img/12.jpg">
		<img src="img/13.jpg">
		<img src="img/14.jpg">
  		<img src="img/15.jpg">
  		<img src="img/16.jpg">
		<img src="img/17.jpg">
  		<img src="img/18.jpg">

            </div>
            <p style="margin-top:10px; font-style:italic;">*Letakkan gambar sebenar dalam folder <code>images</code> dengan nama fail yang sama.</p>
        </section>

        <section id="hubungi">
            <h2>Hubungi Kami</h2>
            <p>Alamat: Kampung Tok Keling, Mukim Derga, 05400 Alor Setar, Kedah</p>
            <p>Telefon: 04-1234567</p>
            <p>Email: info@mtk.edu.my</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Madrasah At-Taklimiah Al-Khairiah. Semua Hak Terpelihara.</p>
    </footer>
</body>
</html>
