# CODEQUEST
## Game Edukasi Pemrograman untuk Anak Sekolah Dasar

### 1. Deskripsi Singkat

CodeQuest adalah platform pembelajaran pemrograman berbasis game 2D yang dirancang untuk mengenalkan konsep dasar coding kepada anak sekolah dasar melalui petualangan interaktif.

Dalam permainan ini, anak mengendalikan karakter dengan menulis kode, bukan menggunakan tombol arah. Setiap instruksi yang ditulis akan diterjemahkan menjadi gerakan atau tindakan karakter untuk menyelesaikan misi.

Materi pembelajaran disusun secara bertahap, mulai dari variabel, function, hingga looping. Dengan pendekatan belajar sambil bermain, CodeQuest bertujuan membantu anak memahami logika pemrograman melalui pengalaman langsung dan menyenangkan.

### 2. Deskripsi Lengkap

#### Latar Belakang

Kemampuan memahami pemrograman dan berpikir komputasional semakin relevan dalam pendidikan. Namun, bagi anak sekolah dasar yang belum pernah mengenal coding, mempelajari konsep pemrograman dapat terasa abstrak dan sulit dipahami jika langsung diperkenalkan melalui materi teoritis.

Salah satu pendekatan yang dapat digunakan adalah pembelajaran berbasis permainan (*game-based learning*). Anak tidak hanya membaca materi, tetapi langsung menerapkan konsep yang dipelajari untuk menyelesaikan suatu permasalahan.

CodeQuest dikembangkan sebagai media pembelajaran interaktif yang menggabungkan materi pemrograman dasar dengan permainan petualangan 2D. Anak akan diberikan materi singkat, contoh kode, dan tantangan yang mengharuskan mereka menyusun instruksi untuk mengendalikan karakter.

#### Permasalahan yang Ingin Diselesaikan

1. Pembelajaran pemrograman bagi pemula dapat terasa abstrak dan kurang menarik jika hanya disampaikan melalui teori.
2. Anak membutuhkan media pembelajaran yang memberikan pengalaman langsung dalam memahami hubungan antara kode dan hasil eksekusinya.
3. Anak perlu diperkenalkan pada konsep dasar pemrograman secara bertahap sebelum mempelajari bahasa pemrograman yang lebih kompleks.
4. Media pembelajaran coding perlu dirancang sesuai dengan tingkat pemahaman dan karakteristik anak sekolah dasar.

#### Solusi yang Ditawarkan

CodeQuest menyediakan lingkungan permainan 2D yang memungkinkan anak mempelajari konsep pemrograman dengan cara mengendalikan karakter melalui kode.

Setiap materi memiliki tiga tahapan:

1. **Learn:** Anak mempelajari konsep dasar melalui penjelasan singkat dan contoh kode.
2. **Practice:** Anak mencoba menulis dan menjalankan kode pada lingkungan permainan.
3. **Challenge:** Anak menyelesaikan misi dengan menerapkan konsep yang telah dipelajari.

#### Materi Pembelajaran

**A. Variabel**

Anak belajar menyimpan nilai dan menggunakan nilai tersebut dalam program.

Contoh:
```python
langkah = 3
maju(langkah)
```

Tantangan: Mengatur jumlah langkah agar karakter mencapai tujuan.

**B. Function**

Anak belajar membuat fungsi untuk mengelompokkan instruksi dan menggunakannya kembali.

Contoh:
```python
def maju():
    gerak(1)

maju()
```

Tantangan: Membuat fungsi untuk menggabungkan beberapa gerakan agar karakter dapat melewati rintangan.

**C. Looping**

Anak belajar mengulang instruksi tanpa harus menuliskan perintah yang sama berkali-kali.

Contoh:
```python
for i in range(3):
    maju()
```

Tantangan: Menggunakan perulangan untuk melewati beberapa blok atau menyelesaikan jalur permainan.

Catatan: Sintaks pada contoh merupakan gambaran pembelajaran. Implementasi awal dapat menggunakan subset Python atau sintaks sederhana berbahasa Indonesia yang diterjemahkan menjadi instruksi permainan.

#### Mekanisme Permainan

Game menggunakan tampilan 2D side-scrolling platformer dengan kamera statis.

Karakter dan lingkungan dibuat sederhana menggunakan bentuk geometris. Platform terdiri dari blok-blok yang memiliki garis pembatas sebagai penanda jarak. Satu blok merepresentasikan satu satuan langkah.

Anak dapat memberikan instruksi seperti:
```python
maju(3)
lompat()
maju(2)
serang()
```

Setelah menekan tombol Run, sistem membaca kode, memeriksa instruksi, kemudian menjalankannya secara berurutan di dalam permainan.

Jika instruksi benar dan karakter berhasil mencapai tujuan, misi dinyatakan selesai. Jika terjadi kesalahan, sistem memberikan petunjuk agar anak dapat memperbaiki programnya.

### 3. Target Pengguna

**Pengguna utama:**
- Anak sekolah dasar, khususnya yang baru mengenal pemrograman.
- Anak yang ingin belajar dasar-dasar coding melalui permainan interaktif.

**Pengguna pendukung:**
- Guru sebagai pendamping pembelajaran.
- Orang tua yang ingin mengenalkan pemrograman kepada anak.

### 4. Fitur Utama

1. **Learning Module:** Materi pembelajaran coding yang disusun berdasarkan tingkat kesulitan.
2. **Interactive Code Editor:** Editor untuk menulis dan mengubah kode.
3. **2D Adventure Game:** Lingkungan permainan untuk menjalankan instruksi yang dibuat anak.
4. **Code Execution:** Sistem untuk membaca, memeriksa, dan menjalankan kode.
5. **Mission Challenge:** Tantangan yang mengharuskan anak menerapkan materi pembelajaran.
6. **Feedback System:** Petunjuk ketika kode salah atau misi belum berhasil.
7. **Learning Progress:** Pencatatan level dan materi yang telah diselesaikan.

### 5. Use Case

#### Aktor

**1. Anak (Player)**

Pengguna utama yang mempelajari materi dan menyelesaikan tantangan permainan.

**2. Guru/Admin**

Pengguna yang mengelola materi, level, dan tantangan pembelajaran. Untuk prototipe awal, pengelolaan ini dapat dilakukan langsung melalui data yang disiapkan oleh tim pengembang.

#### Daftar Use Case Anak

| Use Case | Deskripsi |
|---|---|
| Melihat materi | Anak membuka materi coding yang tersedia. |
| Mempelajari konsep | Anak membaca penjelasan dan contoh kode. |
| Memulai permainan | Anak memasuki level permainan. |
| Menulis kode | Anak menulis instruksi pada editor. |
| Menjalankan kode | Anak menekan tombol Run untuk menjalankan program. |
| Memperbaiki kode | Anak memperbaiki kesalahan berdasarkan petunjuk. |
| Menyelesaikan misi | Anak mencapai tujuan permainan dengan program yang benar. |
| Melihat progres | Anak melihat materi dan level yang telah diselesaikan. |

#### Daftar Use Case Guru/Admin

| Use Case | Deskripsi |
|---|---|
| Mengelola materi | Menambah dan mengubah materi pembelajaran. |
| Mengelola level | Menentukan susunan platform dan tujuan permainan. |
| Mengelola tantangan | Menentukan instruksi dan kondisi keberhasilan misi. |
| Melihat progres | Memantau perkembangan pembelajaran anak. |

#### Alur Utama Penggunaan

1. Anak membuka aplikasi.
2. Anak memilih dunia atau materi pembelajaran.
3. Sistem menampilkan penjelasan dan contoh kode.
4. Anak mempelajari materi.
5. Anak membuka misi permainan.
6. Anak menulis kode pada editor.
7. Anak menekan tombol Run.
8. Sistem memeriksa dan menjalankan kode.
9. Karakter bergerak sesuai instruksi.
10. Sistem memeriksa apakah tujuan misi telah tercapai.
11. Jika berhasil, anak mendapatkan status penyelesaian dan dapat melanjutkan ke tantangan berikutnya.

### 6. Pembanding dengan Platform Sejenis

CodeQuest memiliki sejumlah platform pembelajaran sejenis yang dapat dijadikan referensi, antara lain:

| Platform | Pendekatan | Fokus Pembelajaran |
|---|---|---|
| Scratch | Pemrograman visual berbasis blok | Membuat game, animasi, dan cerita interaktif. |
| Code.org | Kursus dan aktivitas pembelajaran interaktif | Dasar ilmu komputer dan computational thinking. |
| Lightbot | Puzzle dengan instruksi berbentuk ikon | Sequence, function/procedure, looping, dan conditional. |
| Kodable | Game edukasi dengan jalur belajar bertahap | Sequence, function, variable, loop, dan konsep coding lainnya. |
| **CodeQuest** | Game petualangan 2D dengan penulisan kode | Variabel, function, looping, dan penerapan instruksi melalui karakter. |

#### Analisis Perbandingan

**Scratch**

Scratch memungkinkan anak membuat cerita interaktif, animasi, dan permainan menggunakan blok pemrograman visual. Scratch juga menyediakan lingkungan untuk membagikan hasil karya dengan komunitas.

Perbedaan CodeQuest: CodeQuest berfokus pada penyelesaian misi dalam game yang sudah disiapkan dengan menulis instruksi berbasis teks, bukan membuat proyek kreatif secara bebas menggunakan blok visual.

**Code.org**

Code.org menyediakan kurikulum dan aktivitas ilmu komputer untuk siswa sekolah dasar, termasuk pembelajaran konsep pemrograman melalui aktivitas interaktif.

Perbedaan CodeQuest: CodeQuest menggabungkan materi dan tantangan dalam satu mekanisme permainan petualangan 2D dengan editor kode sebagai sarana utama interaksi.

**Lightbot**

Lightbot merupakan salah satu pembanding terdekat karena pemain harus menyusun instruksi untuk mengendalikan karakter dan menyelesaikan puzzle. Konsep yang diajarkan mencakup urutan instruksi, prosedur, perulangan, dan percabangan.

Perbedaan CodeQuest: CodeQuest dirancang menggunakan lingkungan platformer dengan platform bertingkat, gerakan, lompatan, dan serangan. Selain itu, anak berlatih menulis instruksi berbentuk teks, bukan hanya menyusun ikon perintah.

**Kodable**

Kodable menyediakan pembelajaran coding berbasis permainan dengan materi bertahap. Platform ini mengenalkan konsep melalui aktivitas drag-and-drop dan secara bertahap memperkenalkan kode tertulis, termasuk JavaScript pada Kodable Creator.

Perbedaan CodeQuest: CodeQuest berfokus pada pengalaman mengendalikan karakter menggunakan kode dalam satu lingkungan permainan petualangan, dengan tujuan mengenalkan struktur kode yang menyerupai Python sejak tahap pembelajaran awal.

#### Potensi Pembeda CodeQuest

CodeQuest tidak bertujuan menggantikan platform pembelajaran coding yang sudah ada. Fokus pengembangannya adalah menawarkan pendekatan pembelajaran yang berbeda melalui:

1. **Text-based learning:** Anak mulai mengenal bentuk penulisan kode, bukan hanya menyusun blok atau ikon.
2. **Game-based execution:** Kode yang ditulis menghasilkan aksi langsung di dalam permainan.
3. **Progressive learning:** Materi disusun dari variabel, function, hingga looping.
4. **Python-oriented approach:** Pembelajaran dirancang sebagai pengenalan menuju pemrograman Python.
5. **Localized learning:** Materi dan instruksi dapat disajikan dalam bahasa Indonesia agar lebih mudah dipahami oleh anak yang baru belajar.

### 7. Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Laravel | Backend, pengelolaan data, dan autentikasi. |
| Inertia.js | Penghubung backend Laravel dengan frontend React. |
| React | Antarmuka aplikasi, materi, dan editor kode. |
| Phaser.js | Game engine untuk permainan 2D. |
| Database | Menyimpan materi, level, akun, dan progres pembelajaran. |

### 8. Ruang Lingkup MVP

Untuk pengembangan awal dalam hackathon satu hari, fitur dibatasi menjadi:

- Satu halaman utama pembelajaran.
- Tiga kelompok materi: variabel, function, dan looping.
- Satu lingkungan permainan 2D dengan kamera statis.
- Karakter berbentuk kotak dan platform berbentuk blok.
- Perintah gerak maju, mundur, lompat, dan satu jenis serangan.
- Editor kode sederhana.
- Sistem pemeriksaan kode dan eksekusi instruksi.
- Beberapa misi untuk demonstrasi pembelajaran.
- Indikator penyelesaian level.

Fitur lanjutan seperti akun guru, dashboard kelas, leaderboard, banyak dunia permainan, AI tutor, dan interpreter Python lengkap dapat dikembangkan setelah MVP selesai.

### 9. Tujuan Akhir

CodeQuest diharapkan dapat menjadi media pembelajaran alternatif yang membantu anak sekolah dasar mengenal pemrograman sejak dini melalui aktivitas yang interaktif.

Dengan menghubungkan kode yang ditulis dengan tindakan nyata di dalam permainan, anak diharapkan dapat memahami bahwa pemrograman bukan sekadar menghafal sintaks, tetapi menyusun instruksi, memecahkan masalah, menguji program, dan memperbaiki kesalahan.
