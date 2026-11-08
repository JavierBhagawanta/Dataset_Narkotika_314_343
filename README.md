# Dataset Narkotika PN Madiun

Tugas 2 UTS Temu Kembali Informasi · Universitas Muhammadiyah Malang · Semester ganjil 2026/2027

**Dosen pengampu** Galih W. W.

| Anggota | NIM |
| --- | --- |
| Andi Tri Hanggoro Pamungkas | 202310370311343 |
| Javier Bhagawanta | 202310370311314 |

## Cakupan dataset

Kumpulan dokumen perkara Pidana Khusus dengan klasifikasi Narkotika dan Psikotropika dari **Pengadilan Negeri Madiun (PN Mad)**. Tahun dikelompokkan menurut tanggal putus.

| Tahun putus | PDF |
| --- | ---: |
| 2023 | 18 |
| 2024 | 20 |
| 2025 | 12 |
| **Total** | **50** |

Arsip memuat 2.055 halaman PDF. Nama berkas diseragamkan berdasarkan nomor perkara dan isi PDF dipertahankan. Setiap PDF memiliki nomor perkara dan hash SHA-256 yang unik dalam arsip.

## Struktur repositori

| Berkas | Isi |
| --- | --- |
| [Dataset/Narkotika.zip](Dataset/Narkotika.zip) | Folder `Narkotika/` berisi 50 PDF dari Direktori Putusan Mahkamah Agung RI |
| [Overview/Overview.xlsx](Overview/Overview.xlsx) | Ringkasan 50 dokumen dan catatan sumber per dokumen |
| `README.md` | Cakupan, cara penggunaan, catatan seleksi, dan daftar tautan resmi |

## Cara menggunakan

1. Unduh dan ekstrak `Dataset/Narkotika.zip` untuk membuka PDF.
2. Buka `Overview/Overview.xlsx`. Lembar **Overview** memuat lima kolom sesuai soal, yaitu **No**, **No Putusan**, **Lembaga Peradilan**, **Barang Bukti**, dan **Amar Putusan**.
3. Gunakan lembar **Verifikasi** untuk mencocokkan nama PDF, tanggal putus, halaman amar, jenis dokumen, dan tautan ke sumber resmi.

Amar diambil dari bagian **Mengadili** atau **Menetapkan** hingga sebelum penutup. Kolom Barang Bukti mengikuti butir barang bukti dalam amar. Spasi dan pemisah baris dirapikan untuk Excel. Untuk sel dengan teks panjang, pilih sel dan perluas bilah rumus. Pada perkara **111/Pid.Sus/2023/PN Mad**, bagian amar tidak memuat butir penetapan barang bukti sehingga kolomnya mencatat kondisi tersebut.

## Sumber dan catatan seleksi

Sumber PDF dan metadata berasal dari [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/direktori.html). Daftar berikut merujuk ke halaman detail masing-masing dokumen.

- **Jenis dokumen.** PDF perkara **107/Pid.Sus/2024/PN Mad** berjudul **Penetapan**. Arsip ini mempertahankan dokumen tersebut dari paket sumber sehingga komposisinya 49 putusan dan 1 penetapan.
- **Status berkekuatan hukum tetap (BHT).** Status BHT belum terverifikasi untuk 50 dokumen. Manifest sumber mencatat bahwa keterangan BHT tidak tercantum pada halaman detail yang diperiksa.

## Daftar dokumen

| No | Nomor perkara dan sumber resmi | Tanggal putus | Jenis |
| ---: | --- | --- | --- |
| 1 | [7/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee845a0d08bc148893313532373539.html) | 2023-02-21 | Putusan |
| 2 | [13/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef298d29b4bff68829323035393333.html) | 2023-02-23 | Putusan |
| 3 | [27/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea452faf29dcebb21303735373539.html) | 2023-04-13 | Putusan |
| 4 | [28/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea452f6e4757c83d8303735373533.html) | 2023-04-13 | Putusan |
| 5 | [25/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea452dafe70248aab303735373036.html) | 2023-04-17 | Putusan |
| 6 | [35/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea4526186f45a8bb5303735333432.html) | 2023-05-11 | Putusan |
| 7 | [36/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea452833d6d229364303735343339.html) | 2023-05-11 | Putusan |
| 8 | [49/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea45237ffc396c026303735323332.html) | 2023-05-17 | Putusan |
| 9 | [47/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee99e9e45da52291d8303230303333.html) | 2023-06-08 | Putusan |
| 10 | [48/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee9469d0d94ce883ba303230313039.html) | 2023-06-13 | Putusan |
| 11 | [51/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee98b401fb175488fe313330323138.html) | 2023-06-13 | Putusan |
| 12 | [109/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea452854d15f4a751303735343432.html) | 2023-09-27 | Putusan |
| 13 | [110/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea4525f09faeca3ee303735333338.html) | 2023-09-27 | Putusan |
| 14 | [111/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeea4525a41ebbea80d303735333330.html) | 2023-09-27 | Putusan |
| 15 | [121/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef298cecf773f6a033323035373531.html) | 2023-11-09 | Putusan |
| 16 | [132/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee8ee99734e216bd05303230303431.html) | 2023-11-23 | Putusan |
| 17 | [137/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee8ee99f77188689c8303230303534.html) | 2023-11-23 | Putusan |
| 18 | [142/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaee99e9d94f976ca345303230303134.html) | 2023-12-13 | Putusan |
| 19 | [139/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeeaf7a259827e2a452313233363034.html) | 2024-01-04 | Putusan |
| 20 | [149/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeec5eb2db979089789303230303337.html) | 2024-02-05 | Putusan |
| 21 | [150/Pid.Sus/2023/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeec5eb27a1142caec0303230303236.html) | 2024-02-05 | Putusan |
| 22 | [9/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeedbebc1393cacba89303230303130.html) | 2024-03-05 | Putusan |
| 23 | [10/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeedbebc1e0b036a9a2303230303131.html) | 2024-03-05 | Putusan |
| 24 | [5/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeee6ec175993f6a9c1303230303137.html) | 2024-03-14 | Putusan |
| 25 | [6/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeee6ec2c33401a9ac4303230303532.html) | 2024-03-14 | Putusan |
| 26 | [7/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeee6ec1a30fe0c83e9303230303232.html) | 2024-03-14 | Putusan |
| 27 | [22/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeef1ec73864dc69ddd303230303334.html) | 2024-03-28 | Putusan |
| 28 | [23/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaeef1ec723bf786b4e5303230303332.html) | 2024-03-28 | Putusan |
| 29 | [24/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef298d8b1789a4b2c3323130323137.html) | 2024-04-24 | Putusan |
| 30 | [25/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef08f21fa559f0841c303930393037.html) | 2024-05-02 | Putusan |
| 31 | [72/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef65e6c1507f6894ca313631323033.html) | 2024-08-29 | Putusan |
| 32 | [73/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaef65e6bfd89b98b40d313631323030.html) | 2024-08-29 | Putusan |
| 33 | [82/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0992528ccb6bc9df0313630323132.html) | 2024-09-24 | Putusan |
| 34 | [85/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf098329ba44c20a701313130353537.html) | 2024-10-02 | Putusan |
| 35 | [86/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf09818109f68a4b7bb303735353537.html) | 2024-10-16 | Putusan |
| 36 | [95/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad48d58408a985a313235303531.html) | 2024-11-13 | Putusan |
| 37 | [96/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad488ca1eeeb5d3313235303433.html) | 2024-11-13 | Putusan |
| 38 | [107/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad487dcbbf4a480313235303432.html) | 2024-11-13 | Penetapan |
| 39 | [125/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaefd3052a78e27e8a2e313235343231.html) | 2025-01-09 | Putusan |
| 40 | [124/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf09832920d40c2a143313130353431.html) | 2025-01-21 | Putusan |
| 41 | [126/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0a7cd233de5709ffe303733393534.html) | 2025-01-21 | Putusan |
| 42 | [135/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf09cd7bdbb1c1880e4303835383036.html) | 2025-02-06 | Putusan |
| 43 | [133/Pid.Sus/2024/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaefeda8f023521289ef313033323131.html) | 2025-02-11 | Putusan |
| 44 | [1/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf099251b4517c8a079313630313439.html) | 2025-02-20 | Putusan |
| 45 | [45/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0992543ebafc0a6af313630323538.html) | 2025-07-24 | Putusan |
| 46 | [58/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf07f367a280600aa34313630303430.html) | 2025-08-21 | Putusan |
| 47 | [51/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad4de54c4409c42313235333037.html) | 2025-08-28 | Putusan |
| 48 | [40/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad485f13342a7c3313235303339.html) | 2025-09-11 | Putusan |
| 49 | [66/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0bad486d836e8a5f0313235303430.html) | 2025-09-11 | Putusan |
| 50 | [75/Pid.Sus/2025/PN Mad](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0a7cd120eca8aae1c303733393236.html) | 2025-10-09 | Putusan |
"# Dataset_Narkotika_314_343" 
"# Dataset_Narkotika_314_343" 
#   D a t a s e t _ N a r k o t i k a _ 3 1 4 _ 3 4 3  
 #   D a t a s e t _ N a r k o t i k a _ 3 1 4 _ 3 4 3  
 