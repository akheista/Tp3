<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Diri</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 20px;
        }

        #profile-container {
            display: flex;
            gap: 20px;
        }

        #profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
        }

        #profile-info {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 8px;
            border: 1px solid #ddd;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        .button-container {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Profile Diri</h1>

    <div id="profile-container">
        <div>
            <img id="profile-image" src="Khei.jpg" alt="Foto Profil"> <!-- Tag 'img' untuk menampilkan gambar -->
        </div>

        <div id="profile-info">
            <h2>Nama:</h2>
            <p>Kheista Aulia Rizkia</p> <!-- Tag 'p' untuk paragraf -->

            <h2>Tentang Saya:</h2>
            <p>Halo semuanya, Perkenalkan nama saya Kheista Aulia Rizkia dari jurusan Teknologi Infomari fakultas Informatika angkatan 2022. Saya lahir pada Februari 2003 Tasik Malaya, hobi saya membaca Webtoon, menonton series, Menulis cerita, Menggambar, menonton film. </p> <!-- Tag 'p' untuk paragraf -->

            <h2>Informasi Kontak:</h2>
            <table> <!-- Tag 'table' untuk menampilkan data dalam format tabel -->
                <tr> <!-- Tag 'tr' untuk baris dalam tabel -->
                    <th>Email:</th> <!-- Tag 'th' untuk header kolom dalam tabel -->
                    <td>kheista@student.telkomuniversity.ac.id</td> <!-- Tag 'td' untuk data dalam kolom tabel -->
                </tr>
                <tr> <!-- Tag 'tr' untuk baris dalam tabel -->
                    <th>Nomor Telepon:</th> <!-- Tag 'th' untuk header kolom dalam tabel -->
                    <td>+62895412035709</td> <!-- Tag 'td' untuk data dalam kolom tabel -->
                </tr>
            </table>

            <h2>Keahlian:</h2>
            <ul> <!-- Tag 'ul' untuk daftar tidak terurut -->
                <li>Menulis</li> <!-- Tag 'li' untuk item dalam daftar -->
                <li>Menggambar</li> <!-- Tag 'li' untuk item dalam daftar -->
                <li>Translator</li> <!-- Tag 'li' untuk item dalam daftar -->
            </ul>

            <h2>Hubungi Saya:</h2>
            <form> <!-- Tag 'form' untuk membuat formulir -->
                <label for="nama">Nama:</label> <!-- Tag 'label' untuk label input -->
                <input type="text" id="nama" name="nama" required> <!-- Tag 'input' untuk input teks -->

                <label for="email">Email:</label> <!-- Tag 'label' untuk label input -->
                <input type="text" id="email" name="email" required> <!-- Tag 'input' untuk input teks -->

                <label for="pesan">Pesan:</label> <!-- Tag 'label' untuk label input -->
                <textarea id="pesan" name="pesan" rows="4" cols="50" required></textarea> <!-- Tag 'textarea' untuk input teks area -->

                <div class="button-container"> <!-- Tag 'div' untuk grouping elemen -->
                    <button type="submit" class="button">Kirim</button> <!-- Tag 'button' untuk tombol submit -->
                </div>
            </form>

            <h2>Media Sosial Saya:</h2>
            <a href="https://www.instagram.com/ikheiiaa?igsh=MTF2Z2JkNmtxem1tZw==" target="_blank">Instagram</a> <!-- Tag 'a' untuk link -->
        </div>
    </div>
</body>
</html>
