<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Festival Sains Nusantara 2026</title>
</head>
<body>

    <!-- Menampilkan Nama dan NIM agar terlihat di web -->
    <div style="background-color: #f0f0f0; padding: 10px; border-bottom: 2px solid #ccc; text-align: center;">
        <p style="margin: 0;"><strong>Nama:</strong> Dimas Amare Pratomo | <strong>NIM:</strong> 103032400112</p>
    </div>

    <!-- Navigasi -->
    <nav style="margin-top: 15px;">
        <h2>Festival Sains Nusantara 2026</h2>
        <a href="#beranda">Beranda</a> |
        <a href="#acara">Acara</a> |
        <a href="#jadwal">Jadwal</a> |
        <a href="#pendaftaran">Pendaftaran</a>
    </nav>

    <hr>

    <!-- Bagian Beranda -->
    <section id="beranda">
        <h1>Festival Sains Nusantara 2026</h1>
        <p><strong>Tema:</strong> Explore Science, Inspire the Future</p>
        <p><strong>Penyelenggara:</strong> Nusantara Science Community</p>
        <p><strong>Deskripsi:</strong></p>
        <p>Festival Sains Nusantara 2026 merupakan kegiatan yang menghadirkan seminar, workshop, dan kompetisi sains bagi pelajar, mahasiswa, dan masyarakat umum.</p>
        
        <!-- Pastikan file gambar bernama gambar-festival.png ada di folder yang sama -->
        <img src="gambar-festival.png" alt="Gambar Festival Sains Nusantara" width="500">

        <h3>Informasi Acara:</h3>
        <ul>
            <li>Tanggal: 21 November 2026.</li>
            <li>Waktu: 08.00-17.00 WIB.</li>
            <li>Tempat: Gedung Sains Nusantara.</li>
        </ul>
    </section>

    <hr>

    <!-- Bagian Acara -->
    <section id="acara">
        <h2>Kegiatan Acara</h2>
        <div id="workshop" class="kegiatan">
            <h3>Workshop Sains</h3>
            <p>Peserta dapat mengikuti kegiatan eksperimen dan pembelajaran sains secara langsung melalui workshop yang disediakan.</p>
        </div>
        <div id="kompetisi" class="kegiatan">
            <h3>Kompetisi Sains</h3>
            <p>Kompetisi memberikan kesempatan kepada peserta untuk menampilkan ide dan proyek sains mereka.</p>
        </div>
        <div id="seminar" class="kegiatan">
            <h3>Seminar Sains</h3>
            <p>Seminar menghadirkan pembicara untuk berbagi pengetahuan tentang perkembangan sains dan teknologi terkini.</p>
        </div>
    </section>

    <hr>

    <!-- Bagian Jadwal -->
    <section id="jadwal">
        <h2>Jadwal Kegiatan</h2>
        <table border="1" cellspacing="0" cellpadding="8">
            <caption>Jadwal Festival Sains Nusantara 2026</caption>
            <thead>
                <tr>
                    <th rowspan="2">Hari</th>
                    <th rowspan="2">Waktu</th>
                    <th colspan="2">Program</th>
                    <th rowspan="2">Kategori</th>
                </tr>
                <tr>
                    <th>Sesi</th>
                    <th>Materi</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td rowspan="5">Jumat</td>
                    <td>08.00-09.00</td>
                    <td>Pembukaan</td>
                    <td>Opening Ceremony</td>
                    <td>Umum</td>
                </tr>
                <tr>
                    <td>09.00-11.00</td>
                    <td>Workshop</td>
                    <td>Eksperimen Fisika</td>
                    <td>Pelajar</td>
                </tr>
                <tr>
                    <td>09.00-11.00</td>
                    <td>Workshop</td>
                    <td>Dasar Data Science</td>
                    <td>Mahasiswa</td>
                </tr>
                <tr>
                    <td>11.00-12.00</td>
                    <td>Seminar</td>
                    <td>Teknologi dan Masa Depan</td>
                    <td>Umum</td>
                </tr>
                <tr>
                    <td>13.00-15.00</td>
                    <td>Workshop</td>
                    <td>Robotika Dasar</td>
                    <td>Pelajar</td>
                </tr>
                <tr>
                    <td rowspan="4">Sabtu</td>
                    <td>08.00-10.00</td>
                    <td>Kompetisi</td>
                    <td>Science Project</td>
                    <td>Pelajar</td>
                </tr>
                <tr>
                    <td>08.00-10.00</td>
                    <td>Kompetisi</td>
                    <td>Data Challenge</td>
                    <td>Mahasiswa</td>
                </tr>
                <tr>
                    <td>10.00-12.00</td>
                    <td>Seminar</td>
                    <td>Inovasi Energi</td>
                    <td>Umum</td>
                </tr>
                <tr>
                    <td>13.00-15.00</td>
                    <td>Seminar</td>
                    <td>Kecerdasan Buatan</td>
                    <td>Umum</td>
                </tr>
                <tr>
                    <td rowspan="2">Minggu</td>
                    <td>08.00-10.00</td>
                    <td>Kompetisi</td>
                    <td>Robotik Nusantara</td>
                    <td>Pelajar</td>
                </tr>
                <tr>
                    <td>10.00-12.00</td>
                    <td>Penutupan</td>
                    <td>Closing Ceremony</td>
                    <td>Umum</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td colspan="5">Jadwal kegiatan dapat mengalami perubahan sesuai kondisi penyelenggaraan acara.</td>
                </tr>
            </tfoot>
        </table>
    </section>

    <hr>

    <!-- Bagian Pendaftaran -->
    <section id="pendaftaran">
        <h2>Formulir Pendaftaran</h2>
        <form action="#" method="POST">
            <label for="nama">Nama Lengkap:</label><br>
            <input type="text" id="nama" name="nama" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="telepon">Nomor Telepon:</label><br>
            <input type="tel" id="telepon" name="telepon" required><br><br>

            <label for="institusi">Institusi / Asal Sekolah:</label><br>
            <input type="text" id="institusi" name="institusi" required><br><br>

            <label>Jenis Kelamin:</label><br>
            <input type="radio" id="laki" name="kelamin" value="Laki-laki" required>
            <label for="laki">Laki-laki</label>
            <input type="radio" id="perempuan" name="kelamin" value="Perempuan" required>
            <label for="perempuan">Perempuan</label><br><br>

            <label for="tanggal_lahir">Tanggal Lahir:</label><br>
            <input type="date" id="tanggal_lahir" name="tanggal_lahir" required><br><br>

            <label>Kategori Peserta:</label><br>
            <input type="radio" id="pelajar" name="kategori" value="Pelajar" required>
            <label for="pelajar">Pelajar</label>
            <input type="radio" id="mahasiswa" name="kategori" value="Mahasiswa" required>
            <label for="mahasiswa">Mahasiswa</label>
            <input type="radio" id="umum" name="kategori" value="Umum" required>
            <label for="umum">Umum</label><br><br>

            <label>Pilihan Kegiatan:</label><br>
            <input type="checkbox" id="keg1" name="kegiatan" value="Workshop Eksperimen Fisika">
            <label for="keg1">Workshop Eksperimen Fisika</label><br>
            
            <input type="checkbox" id="keg2" name="kegiatan" value="Workshop Dasar Data Science">
            <label for="keg2">Workshop Dasar Data Science</label><br>
            
            <input type="checkbox" id="keg3" name="kegiatan" value="Seminar Teknologi dan Masa Depan">
            <label for="keg3">Seminar Teknologi dan Masa Depan</label><br>
            
            <input type="checkbox" id="keg4" name="kegiatan" value="Workshop Robotika Dasar">
            <label for="keg4">Workshop Robotika Dasar</label><br>
            
            <input type="checkbox" id="keg5" name="kegiatan" value="Kompetisi Science Project">
            <label for="keg5">Kompetisi Science Project</label><br>
            
            <input type="checkbox" id="keg6" name="kegiatan" value="Kompetisi Data Challenge">
            <label for="keg6">Kompetisi Data Challenge</label><br>
            
            <input type="checkbox" id="keg7" name="kegiatan" value="Seminar Inovasi Energi">
            <label for="keg7">Seminar Inovasi Energi</label><br>
            
            <input type="checkbox" id="keg8" name="kegiatan" value="Seminar Kecerdasan Buatan">
            <label for="keg8">Seminar Kecerdasan Buatan</label><br>
            
            <input type="checkbox" id="keg9" name="kegiatan" value="Kompetisi Robotik Nusantara">
            <label for="keg9">Kompetisi Robotik Nusantara</label><br><br>

            <label for="kebutuhan_khusus">Kebutuhan Khusus atau informasi tambahan yang perlu diperhatikan panitia:</label><br>
            <textarea id="kebutuhan_khusus" name="kebutuhan_khusus" rows="4" cols="50"></textarea><br><br>

            <button type="submit">Daftar Sekarang</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy;2026 Nusantara Science Community</p>
    </footer>

</body>
</html>
