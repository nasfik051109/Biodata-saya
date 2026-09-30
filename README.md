<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Diri - Portofolio</title>
    <style>
        * {
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
        }
        body {
            background-color: #f4f7f6;
            color: #333;
            display: flex;
            justify-content: center;
            padding: 40px 20px;
        }
        .card {
            background-color: #ffffff;
            width: 100%;
            max-width: 600px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .header {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }
        /* Style untuk Foto Profil */
        .profile-img {
            width: 130px;
            height: 130px;
            border-radius: 50%; /* Membuat foto jadi bulat */
            object-fit: cover;
            border: 4px solid #ffffff;
            margin-bottom: 15px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        .header h1 {
            margin-bottom: 5px;
            font-size: 24px;
        }
        .header p {
            font-size: 14px;
            opacity: 0.9;
        }
        .content {
            padding: 30px;
        }
        .section-title {
            font-size: 16px;
            font-weight: bold;
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
            margin-bottom: 15px;
            margin-top: 20px;
        }
        .section-title:first-child {
            margin-top: 0;
        }
        .info-table {
            width: 100%;
            border-collapse: collapse;
        }
        .info-table td {
            padding: 8px 0;
            vertical-align: top;
        }
        .info-table td.label {
            font-weight: bold;
            width: 35%;
            color: #555;
        }
        ul {
            padding-left: 20px;
        }
        li {
            margin-bottom: 5px;
        }
        .footer {
            text-align: center;
            padding: 15px;
            background-color: #f9f9f9;
            font-size: 12px;
            color: #777;
            border-top: 1px solid #eee;
        }
    </style>
</head>
<body>

    <div class="card">
        <!-- Header Nama & Foto -->
        <div class="header">
            <!-- Tag Foto Profil -->
            <img src="foto2.jpg" alt="Foto Profil" class="profile-img">
            <h1>Nama Lengkap Anda</h1>
            <p>Siswa / Student / Web Developer</p>
        </div>

        <!-- Isi Data Diri -->
        <div class="content">
            
            <div class="section-title">BIODATA DIRI</div>
            <table class="info-table">
                <tr>
                    <td class="label">Nama Lengkap</td>
                   <td>: Muhammad Taufik Maulana</td>
                </tr>
                <tr>
                    <td class="label">Tempat, Tgl Lahir</td>
                    <td>: Banyumas, 05 November 2009</td>
                </tr>
                <tr>
                    <td class="label">Jenis Kelamin</td>
                    <td>: Laki-laki </td>
                </tr>
                <tr>
                    <td class="label">Alamat</td>
                    <td>: Jl. Banyumas Kemranj, RT 03/RW 01, Kejawar, Banyumas, Kab. Banyumas, Jawa Tengah.</td>
                </tr>
                <tr>
                    <td class="label">Email</td>
                    <td>: muhammadtaufikk12345@gmail.com</td>
                </tr>
            </table>

            <div class="section-title">PENDIDIKAN</div>
            <ul>
               <li><strong>SMK Negeri 1 Banyumas</strong> (2025 - Sekarang)</li>
                <li><strong>SMP Negeri 3 Banyumas</strong> (2022 - 2025)</li>
		<li><strong>SD Negeri 1 Kejawar</strong> (2016 - 2022)</li>
            </ul>

            <div class="section-title">KEAHLIAN</div>
            <ul>
				<li>Cyber Security</li>
            </ul>
                <li>HTML & CSS</li>
                <li>Dasar Pemrograman PHP</li>
                <li>Microsoft Office / Excel</li>
            </ul>
			<li>Menguasai Semua Bidang</li>
            </ul>

        </div>

        <div class="footer">
            &copy; 2026 Web Data Diri
        </div>
    </div>

</body>
</html>
