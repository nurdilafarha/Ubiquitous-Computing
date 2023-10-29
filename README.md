# Project Ubiquitous Computing

## Intro
Project UbiCom ini bertemakan Sistem Keamanan Rumah Berbasis Face Recognition

## Latar Belakang
Keamanan rumah merupakan hal penting yang selalu menjadi perhatian bagi pemilik rumah. Rumah harus dapat memberikan rasa aman bagi para penghuninya. Sistem yang dapat membantu pemilik rumah dalam upaya mengamankan rumahnya sangat diperlukan. Terutama di masa sekarang ini dimana kasus pencurian merupakan kasus kejahatan yang paling banyak terjadi di Indonesia. Biasanya pencurian terjadi ketika rumah sedang ditinggalkan penghuninya

Untuk mengatasi masalah tersebut, maka diperlukan suatu sistem yang dapat membantu penghuni rumah untuk memantau kondisi rumahnya setiap saat. Salah satunya yaitu dengan menggunakan teknologi face recognition (pengenalan wajah). Sistem keamanan rumah berbasis face recognition merupakan suatu inovasi yang bertujuan untuk meningkatkan tingkat keamanan dan kenyamanan di lingkungan rumah. Wajah merupakan bagian tubuh yang memiliki keunikan tertentu sehingga dapat digunakan untuk membedakan seseorang. Nantinya teknologi tersebut dapat melakukan pendeteksian wajah para penghuni rumah. Jika bukan wajah penghuni rumah yang terdeteksi, maka sistem akan menganggap orang tersebut sebagai orang asing atau tidak dikenal.

## Branding
- Merk: Piruma
- Inspirasi merk: Gabungan dari dua kata bahasa Indonesia yaitu "Rumah" dan "Pintar". Ini bermakna bahwa sistem ini merupakan sistem rumah pintar yang dapat membantu pengguna dalam menjaga keamanan rumahnya.
- Tagline: Sistem keamanan untuk rumah anda
- Campaign: Menjadikan rumah lebih aman dengan pengenalan wajah secara real-time melalui kamera
- Target user: Pemilik rumah yang jarang ada di rumah
- User experience theme: Mudah digunakan

## User Story
<table>
    <thead>
        <tr>
            <th>Sebagai</th>
            <th>Saya Ingin bisa</th>
            <th>Sehingga</th>
            <th>Prioritas</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Sistem</td><td>Mendeteksi wajah dari kamera</td><td>Dapat mengenali wajah penghuni rumah</td><td>5/5</td>
        </tr>
        <tr>
            <td>Sistem</td><td>Menampilkan data hasil deteksi wajah</td><td>Penghuni rumah dapat mengetahui siapa saja yang masuk ke rumah</td><td>4/5</td>
        </tr>
    </tbody>
</table>

## Metode dan Algoritma
Algoritma Haar-cascade classifier merupakan metode machine learning yang digunakan sebagai metode pengenalan wajah untuk mengklasifikasikan penghuni rumah dan orang asing yang tidak dikenal. OpenCV telah menyediakan berbagai algoritma computer vision di dalamnya yang dapat digunakan secara mudah dan gratis oleh para developer. Maka, metode ini dipilih karena kemudahannya dalam implementasi menggunakan library openCV.
 
## Struktur Data
![tabel relasi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Tabel%20Relasi_ubikom.drawio%20(1).png)

## Arsitektur Sistem
![arsitektur sistem](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Arsitektur%20Sistem_ubikom.drawio.png)
---
Sensor yang digunakan pada sistem keamanan rumah dengan face recognition ini adalah sensor kamera. 

## Deskripsi Teknologi
- Edge Server : Raspberry pi. Raspberry pi merupakan mini komputer yang memiliki prosesor yang lebih kuat dibandingkan arduino dan dapat menjalankan perangkat lunak yang memerlukan pemrosesan citra yang kompleks. Sehingga Raspberry pi lebih cocok digunakan untuk face recognition.
- Sensor kamera : Kamera laptop Lenovo Ideapad 320. Kamrea laptop ini digunakan sebagai alternatif pengganti dari Raspberry pi yang memiliki harga yang cukup mahal.
- Software development: PHP & MySQL. PHP dan MySQL digunakan karena mudah dioperasikan dalam pembuatan web
- Library OpenCV : OpenCV merupakan perangkat lunak open source yang dapat digunakan dalam pengenalan wajah dan mendukung pemrosesan gambar atau video secara real-time. Bahasa pemrograman yang digunakan adalah python.

## User Experience (UX) Design
![login](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%201.png)
![home](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%202.png)
![deteksi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%203.png)
![hasil deteksi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%204.png)
