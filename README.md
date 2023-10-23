# Project Ubiquitous Computing

## Intro
Project UbiCom ini bertemakan Sistem Keamanan Rumah Berbasis Face Recognition

## Latar Belakang
Sistem keamanan rumah sangat dibutuhkan di masa sekarang ini. Mengingat semakin banyaknya kasus pencurian ketika kondisi rumah sedang ditinggalkan penghuninya. Dilansir dari web databoks.katadata.co.id, kasus kejahatan yang paling banyak terjadi di Indonesia (Januari-April 2023) adalah kasus pencurian. 

Maka dari itu, diperlukan teknologi yang dapat membantu penghuni rumah untuk memantau kondisi rumahnya setiap saat. Salah satunya dengan menggunakan teknologi face recognition (pengenalan wajah). Wajah merupakan bagian tubuh yang memiliki keunikan tertentu sehingga dapat digunakan untuk membedakan seseorang. Nantinya teknologi tersebut dapat melakukan pendeteksian wajah berdasarkan wajah para penghuni rumah. Jika bukan wajah penghuni rumah yang terdeteksi, maka sistem akan menganggap orang tersebut sebagai orang asing.

Referensi: https://databoks.katadata.co.id/datapublish/2023/07/18/pencurian-kejahatan-paling-banyak-di-indonesia-sampai-april-2023

## Branding
- Merk: Piruma
- Inspirasi merk: Gabungan dari dua kata bahasa Indonesia yaitu "Rumah" dan "Pintar"
- Tagline: Sistem keamanan untuk rumah anda
- Campaign: Menjadikan rumah lebih aman
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
Metode Haar-cascade Classifier sebagai metode pengenalan wajah untuk mengklasifikasikan penghuni rumah dan orang asing. Metode ini dipilih karena kemudahannya dalam implementasi menggunakan library opencv.
 
## Struktur Data
![tabel relasi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Tabel%20Relasi_ubikom.drawio%20(1).png)

## Arsitektur Sistem
![arsitektur sistem](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Arsitektur%20Sistem_ubikom.drawio.png)

## Deskripsi Teknologi
- Software development: PHP & MySQL.  
- Sensor kamera: Raspberry pi. Raspberry pi merupakan mini komputer yang memiliki prosesor yang lebih kuat dibandingkan arduino dan dapat menjalankan perangkat lunak yang memerlukan pemrosesan citra yang kompleks. Sehingga raspberry pi lebih cocok digunakan untuk face recognition.
  (Alternatif: Kamera laptop)
- Library OpenCV. OpenCV merupakan perangkat lunak open source yang dapat digunakan dalam pengenalan wajah dan mendukung pemrosesan gambar atau video secara real-time.

## User Experience (UX) Design
![login](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%201.png)
![home](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%202.png)
![deteksi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%203.png)
![hasil deteksi](https://github.com/nurdilafarha/Ubiquitous-Computing/blob/main/Frame%204.png)
