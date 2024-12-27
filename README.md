# website-me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Besar Jaringan Komputer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 100%;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            background-color: red;
        }

        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .profile-photo {
            width: 150px;
            height: 250px;
            margin-right: 20px;
            object-fit: cover;
        }

        .profile-info {
            flex: 1;
        }

        .description {
            margin-top: 20px;
        }

        button {
            padding: 10px 15px;
            background-color: red;
            color: black;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Profil Mahasiswa</h1>
        <div class="profile">
            <img src="WhatsApp Image 2024-12-26 at 21.05.57.jpeg" alt="" class="profile-photo">
            <div class="profile-info">
                <h2>Nama: Vikry Achmad Sonjaya Kusumah</h2>
                <p>NIM: 607012400001</p>
                <p>Kelas: 48-02</p>
                <p>Matakuliah: Jaringan Komputer</p>
            </div>
        </div>
        <div class="description">
            <h3>Pengertian Jaringan Komputer</h3>
            <p id="description-text">
                Jaringan komputer adalah kumpulan komputer, perangkat, dan sistem lainnya yang saling terhubung dan berkomunikasi satu sama lain melalui media transmisi atau saluran komunikasi. Tujuan utama dari jaringan komputer adalah untuk memungkinkan berbagi sumber daya, data, dan informasi antara perangkat yang terhubung.</p>
            <button onclick="toggleDescription()">Tampilkan/Sembunyikan Deskripsi</button>
        </div>
    </div>
    <script>
        function toggleDescription() {
            const descriptionText = document.getElementById('description-text');
            if (descriptionText.style.display === 'none') {
                descriptionText.style.display = 'block';
            } else {
                descriptionText.style.display = 'none';
            }
        }
    </script>
</body>
</html>
