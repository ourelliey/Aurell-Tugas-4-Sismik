# Aurell-Tugas-4-Sismik
# Traffic Light 4 Arah - Arduino Uno

## Deskripsi

Project ini merupakan simulasi sistem **traffic light 4 arah** menggunakan Arduino Uno. Sistem dirancang untuk mengatur lalu lintas secara otomatis dengan urutan **Utara → Timur → Selatan → Barat** dan berjalan terus menerus.

Setiap arah memiliki tiga lampu yaitu merah, kuning, dan hijau yang bekerja sesuai dengan aturan dasar lampu lalu lintas.

---

## Fitur Sistem

* Sistem berjalan otomatis (looping)
* Urutan lampu searah jarum jam
* Tidak ada lebih dari satu lampu hijau aktif
* Lampu kuning berkedip sebagai transisi
* Perpindahan lampu berjalan teratur

---

## Komponen yang Digunakan

* Arduino Uno
* LED merah, kuning, dan hijau
* Resistor 220 Ohm
* Breadboard
* Kabel jumper

---

## Cara Kerja Sistem

Sistem diawali dengan semua lampu dalam kondisi merah. Kemudian satu arah akan menyala hijau selama beberapa detik, sementara arah lainnya tetap merah. Setelah itu, lampu kuning akan berkedip sebagai tanda perpindahan sebelum kembali ke merah.

Proses ini dilanjutkan ke arah berikutnya sesuai urutan yang telah ditentukan dan akan terus berulang secara otomatis.

---

## Tujuan Project

* Memahami penggunaan GPIO pada Arduino
* Menerapkan logika kontrol sederhana
* Mensimulasikan sistem lalu lintas
* Melatih pemrograman dasar mikrokontroler

---

## 👩‍💻 Author

**Aurellia Nabila Rahma Putri**
NIM: H1H024066

---

## 📎 Catatan

Project ini dibuat sebagai bagian dari tugas mata kuliah **Sistem Mikrokontroler**.
