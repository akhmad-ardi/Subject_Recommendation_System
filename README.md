# Laporan Proyek Sistem Rekomendasi Mata Pelajaran - Akhmad Ardiansyah Amnur

## Project Overview

Dalam era globalisasi dan perkembangan teknologi yang pesat, siswa dihadapkan pada pilihan mata pelajaran yang semakin beragam dan kompleks. Pemilihan mata pelajaran yang tepat merupakan langkah penting dalam menentukan jalur pendidikan dan karir siswa di masa depan. Namun, proses pemilihan ini seringkali menjadi tantangan bagi siswa, terutama mereka yang belum memiliki pemahaman yang mendalam mengenai minat, bakat, dan potensi diri.

Kurangnya informasi dan pemahaman mengenai berbagai pilihan mata pelajaran dapat menyebabkan siswa merasa bingung dan kesulitan dalam mengambil keputusan. Akibatnya, siswa mungkin memilih mata pelajaran yang kurang sesuai dengan minat dan bakat mereka, yang dapat berdampak pada motivasi belajar, prestasi akademik, dan bahkan pilihan karir di masa depan.

Untuk mengatasi permasalahan ini, diperlukan sebuah sistem yang dapat membantu siswa dalam memilih mata pelajaran yang paling sesuai dengan minat, bakat, dan potensi mereka. Sistem rekomendasi mata pelajaran hadir sebagai solusi untuk menjawab kebutuhan ini.

**Mengapa Proyek Ini Penting untuk Diselesaikan?**

Proyek sistem rekomendasi mata pelajaran memiliki beberapa justifikasi yang membuatnya penting untuk diselesaikan:

1. **Personalisasi Pembelajaran**: Setiap siswa memiliki karakteristik, minat, dan bakat yang unik. Sistem rekomendasi memungkinkan personalisasi pembelajaran yang lebih baik dengan menyesuaikan rekomendasi mata pelajaran dengan kebutuhan dan preferensi individu siswa. Hal ini dapat meningkatkan motivasi, keterlibatan, dan hasil belajar siswa secara keseluruhan.

2. **Peningkatan Efisiensi**: Proses pemilihan mata pelajaran secara manual dapat memakan waktu dan tenaga. Sistem rekomendasi dapat menyederhanakan proses ini dengan memberikan informasi yang relevan dan akurat kepada siswa, sehingga mereka dapat membuat keputusan yang lebih cepat dan tepat.

3. **Peningkatan Kepuasan Siswa**: Ketika siswa memilih mata pelajaran yang sesuai dengan minat dan bakat mereka, mereka cenderung lebih termotivasi dan puas dengan pengalaman belajar mereka. Hal ini dapat berdampak positif pada prestasi akademik dan perkembangan pribadi siswa.

4. **Dukungan Pengambilan Keputusan**: Sistem rekomendasi menyediakan informasi yang komprehensif dan mudah diakses, membantu siswa (dan orang tua mereka) dalam membuat keputusan yang lebih baik mengenai pilihan mata pelajaran.

5. **Relevansi dengan Kebutuhan Industri**: Sistem rekomendasi dapat dirancang untuk mempertimbangkan kebutuhan industri dan pasar kerja saat ini. Dengan demikian, siswa dapat memilih mata pelajaran yang tidak hanya menarik bagi mereka, tetapi juga relevan dengan prospek karir mereka di masa depan.

6. **Mengatasi Keterbatasan Informasi**: Seringkali siswa memiliki keterbatasan informasi mengenai berbagai pilihan mata pelajaran dan dampaknya terhadap jalur karir mereka. Sistem rekomendasi membantu mengatasi keterbatasan ini dengan menyediakan informasi yang terstruktur dan mudah dipahami.

7. **Peningkatan Efisiensi Penggunaan Sumber Daya**: Dengan membantu siswa memilih mata pelajaran yang tepat sejak awal, sistem rekomendasi dapat mengurangi kemungkinan siswa untuk berganti jurusan atau mengulang mata pelajaran di kemudian hari. Hal ini dapat menghemat waktu, biaya, dan sumber daya pendidikan.

Dengan berbagai justifikasi ini, proyek sistem rekomendasi mata pelajaran memiliki potensi besar untuk meningkatkan kualitas pendidikan dan membantu siswa mencapai potensi maksimal mereka.

Refrensi:

- [Sistem Rekomendasi Nilai Mata Kuliah Menggunakan Metode Content-Based Filtering](http://www.jurnal.upnyk.ac.id/index.php/semnasif/article/view/1148) 

## Business Understanding

Pada bagian ini, Anda perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Pernyataan masalah dalam proyek ini mengidentifikasi kesenjangan atau tantangan yang perlu diatasi oleh sistem rekomendasi mata pelajaran.

1. Siswa kesulitan memilih mata pelajaran yang sesuai dengan minat, bakat, dan tujuan karir mereka karena kurangnya informasi dan pemahaman yang mendalam mengenai berbagai pilihan mata pelajaran.

2. Proses pemilihan mata pelajaran seringkali memakan waktu dan tenaga, baik bagi siswa maupun guru.

3. Kurikulum yang ada belum secara optimal memfasilitasi personalisasi pembelajaran berdasarkan preferensi individu siswa.

### Goals

Tujuan proyek ini adalah untuk memberikan solusi terhadap pernyataan masalah yang telah diidentifikasi.

1. Mengembangkan sistem rekomendasi berbasis konten yang menyediakan informasi komprehensif dan mudah diakses mengenai berbagai pilihan mata pelajaran, termasuk deskripsi mata pelajaran, waktu belajar dalam sepekan, kehadiran di kelas, dan aspirasi karir siswa.

2. Membangun sistem rekomendasi yang efisien dan efektif, sehingga mempermudah dan mempercepat proses pemilihan mata pelajaran bagi siswa dan guru.

3. Membuat sistem rekomendasi yang mampu menyesuaikan rekomendasi mata pelajaran dengan kebutuhan dan preferensi individu siswa, sehingga mendukung personalisasi pembelajaran.

### Solution statements
Untuk mencapai tujuan-tujuan tersebut, berikut adalah beberapa pendekatan solusi yang dapat dipertimbangkan:

- **Sistem Rekomendasi Berbasis Konten (Content-Based Filtering)**:
    Pendekatan ini merekomendasikan mata pelajaran berdasarkan mata pelajaran, waktu belajar dalam sepekan, kehadiran di kelas, dan aspirasi karir siswa. Sistem akan mencari kecocokan antara konten mata pelajaran dengan profil siswa untuk memberikan rekomendasi yang relevan.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai jumlah data, kondisi data, dan informasi mengenai data yang digunakan. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya, uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data beserta insight atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model sisten rekomendasi yang Anda buat untuk menyelesaikan permasalahan. Sajikan top-N recommendation sebagai output.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menyajikan dua solusi rekomendasi dengan algoritma yang berbeda.
- Menjelaskan kelebihan dan kekurangan dari solusi/pendekatan yang dipilih.

## Evaluation
Pada bagian ini Anda perlu menyebutkan metrik evaluasi yang digunakan. Kemudian, jelaskan hasil proyek berdasarkan metrik evaluasi tersebut.

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.