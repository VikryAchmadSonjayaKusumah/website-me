# website-me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Besar Jaringan Komputer</title>
    <style>
    </style>
</head>
<body>
    <div class="container">
        <h1>Profil Mahasiswa</h1>
        <div class="pr![WhatsApp Image 2024-12-26 at 21 05 57_04f6a3af](https://github.com/user-attachments/assets/46581da7-f3b5-4b13-8482-7bf7b291f8fd)
ofile">
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
