# Pedagogi

Dunia teknologi informasi merupakan dunia yang luas. Tidak memungkinkan untuk mengajarkan dan memberikan bekal ke pembelajar tentang semua hal. Oleh karena itu, sekolah ini lebih menekankan pada kekuatan konsep melalui _mastery-based learning_ (MBL) sehingga memudahkan adaptasi pembelajar ke dunia industri serta penguatan pada karir mereka kelak. Konsep yang kuat tidak dilakukan dengan cara memberikan kuliah-kuliah seperti pada perguruan tinggi tetapi melalui latihan dan pembelajaran praktik yang intensif dengan pemahaman ke arah konsep. Pembelajar hanya akan melanjutkan ke proses berikutnya jika berhasil menunjukkan pemahaman mendalam (_deep understanding and mastery_) pada proses tersebut. Repo ini selanjutnya akan menjelaskan tentang pedagogi yang digunakan di NEO-X School. 

## Garis Besar Umum

Secara umum, aliran proses kelas adalah sebagai berikut. 

![Aliran proses kelas di NEO-X School](./img/mekanisme-kelas-NEO-X.png)

Pembelajar sebaiknya memahami aliran proses ini untuk memahami kerangka besar sebelum masuk ke dalam hal-hal yang sifatnya detail teknis. Selain itu, pembelajar juga akan mengetahui apa yang akan terjadi dengan proyek _capstone_ yang dibuat oleh pembelajar tersebut secara individu maupun bersama tim. Perlu diketahui, hasil dari proyek _capstone_ merupakan artefak (dengan lisensi) bebas dan _open source_. Ini berarti pembelajar atau siapapun juga bisa tetap mengembangkan di luar proses di NEO-X School jika berminat ingin mengembangkan sendiri secara lebih lanjut. Ada beberapa hal yang perlu dipastikan supaya tidak terjadi kebingungan:

1. Untuk proyek _capstone_ individu, lisensi wajib _free / open source_ dan hak cipta ada pada pembelajar yang bersangkutan.
2. Untuk proyek _capstone_ tim, lisensi wajib _free / open source_ . Jika melibatkan _engineers_ dari NEO-X secara signifikan, maka hak cipta ada pada PT Neo Akselerasi Indonesia. Jika proses dilaksanakan mayoritas secara mandiri, maka hak cipta ada pada tim yang bersangkutan.

## Proses Pembelajaran

Pedagogi yang digunakan oleh NEO-X School merupakan adaptasi dari [Disciplined Agile](https://www.pmi.org/disciplined-agile/introduction-to-disciplined-agile) yang digunakan untuk proses pembelajaran. Proses pembelajaran yang diuraikan di bagian ini adalah proses pembelajaran default. Pada prosesnya, mentor dan pembelajar akan menentukan WoW (_Way of Working_) yang lebih sesuai untuk *batch* tersebut dengan pertimbangan utama sebaagi berikut:

1. Proses bisa *online* maupun *offline*. Jam dimulai dan berakhir tetap.
2. Presentasi setelah selesai penyelesaian *backlog* pada *timeframe* tertentu wajib dilaksanakan secara offline.
3. Target dan proses pengerjaan tetap sama, masalah *online* atau *offline* hanya masalah platform.

### Ketentuan Umum

* Pendidikan dilaksanakan pada hari kerja (senin - jumat), dari jam 09:00 - 16:00.
* Peserta menggunakan laptop sendiri, RAM minimal 16 GB atau sesuai keperluan kelas (bisa dengan spesifikasi yang lebih baik).
* Pakaian dan asesoris pembelajar tidak diatur secara khusus. Meskipun demikian, jika terjadi kasus tertentu, NEO-X School berhak menentukan penggunaan pakaian maupun asesoris yang diperbolehkan.
* Kehadiran sifatnya mutlak. Ketidakhadiran akan menjadi perhatian khusus dan bisa mengarah ke dihentikannya peserta dari proses pendidikan. Masalah seperti ini akan menjadi perhatian internal dan akan dirapatkan oleh internal NEO-X School untuk tindak lanjut dari kondisi tersebut.
* Waktu untuk beribadah tidak boleh diganggu. Pembelajar dipersilahkan meninggalkan kelas untuk mengerjakan ibadah. Jam untuk ibadah ini tidak ditulis secara khusus tetapi pembelajar dipersilahkan melaksanakan sesuai dengan jam masing-masing.
* Pembelajar diminta semaksimal mungkin berkontribusi ke proyek-proyek open source yang ada di GitHub.

### *Tools*

* NEO-X School menggunakan Linux dan / atau OS berbasis UNIX lainnya. Secara khusus, NEO-X School tidak meng-*endorse* distro tertentu. 
* NEO-X School menggunakan [Git](https://git-scm.com/) sebagai alat pengelolaan kode sumber (*source code*) dan [GitHub](https://github.com/) sebagai platform hosting kode sumber.
* NEO-X School menggunakan [Zed](https://zed.sh/) sebagai IDE. Penggunaan Zed diwajibkan karena memungkinkan kolaborasi dengan tim secara lebih baik. Dalam proses pembelajaran, Zed akan digunakan untuk menulis kode dan mengelola proyek. Penggunaan Zed memungkinkan tim berada dalam konteks yang sama saat pengembangan proyek sehingga memudahkan proses *debugging* atau *troubleshooting*.

### Tahap Pendidikan

![Garis besar proses pembelajaran di NEO-X School](./img/NEO-X-School-00-umum.png)

Tahap pendidikan ada 3:

* Tahap *incubator*: pembelajar dianggap mempunyai cukup dasar untuk masuk ke proses. Tahap ini berisi pemberian teori, praktik, dan latihan intensif dengan tujuan untuk membentuk mental dan _skill_. 
* Tahap *capstone*: pembelajar dianggap siap untuk masuk ke industri. Pada tahap ini, pembelajar akan mendapatkan tantangan terkait materi secara langsung. Tahap ini mempunyai 2 kemungkinan, yaitu:
  1. Bergabung ke tim pengembang software dalam bentuk **internship**. Kemungkinan ini terjadi jika ada proyek riil. Pembelajar dilibatkan secara langsung dalam tim dan dibimbing untuk mengerjakan proyek riil tersebut.
  2. **Proyek mandiri**. Kemungkinan ini terjadi jika tidak ada proyek riil. Situasi ini pada dasarnya mempunyai 2 kemungkinan, yaitu tahap **inisiator** dan tahap **team player**. Pada tahap *initiator*, pembelajar dianggap mempunyai kemampuan yang mencukupi dan mempunyai mental serta inisiatif yang baik dalam materi terkait. Pada tahap ini, pembelajar berinisiatif membuat software sesuai keinginan pribadi. Pada tahap *team player*, pembelajar dianggap mempunyai kemampuan individual yang memadai dan bisa menggunakan kemampuan individual mereka untuk pembuatan software secara berkelompok.
* Tahap *profesional*. Pada tahap ini, NEO-X akan menempa pembelajar dengan berbagai proses pembelajaran yang terkait dengan profesionalisme.

### Incubator

![Proses *incubator* di NEO-X School](./img/NEO-X-School-01-incubator.png)

_Tujuan_

Memberikan dasar teori dan praktik yang kuat terhadap materi

_Aktivitas Harian_

Setiap hari, akan dilakukan pemberian materi serta latihan intensif dengan alokasi waktu sebagai berikut:

- Sebelum jam 9: presensi kedatangan
- Jam 9 - 10: pemberian materi, penjelasan serta contoh-contoh oleh mentor.
- Jam 10 - 12: latihan materi dari mentor.
- Jam 13 - 16: latihan kasus lebih kompleks.
- jam 16: presensi pulang.

Setelah selesai, hasil untuk setiap hari di-push ke repo GitHub dengan nama repo **NEO-X**. Pada repo tersebut:

1. Buat file README.md berisi **learning outcomes**
2. Buat direktori `incubator` dan `capstone`. 

Pada direktori `incubator`, buat direktori sesuai dengan timeframe dan hari pelaksanaan:

```
Timeframe-Hari
```

- Timeframe: Timeframe saat pengerjaan (2 digit)
- Hari: Hari saat pengerjaan (2 digit)

Contoh:

`02-03`: repo untuk timeframe `2`, hari ke `3`.

Pada repo tersebut, buat `README.md` dengan isi minimal:

- Judul: Materi hari tersebut
- Oleh: nama pembelajar
- Tanggal
- Ringkasan materi
- Penjelasan tentang isi repo
- Lisensi

Pada repo tersebut, isikan juga berbagai hasil file yang dikerjakan pada hari itu dengan struktur bebas. File serta strukturnya dijelaskan di dalam file README.md di atas.

Berikut adalah contoh direktori yang dibuat:

![Struktur direktori](img/struktur-dir.png)

Peserta diwajibkan posting ke akun media sosial LinkedIn peserta serta salah satu media sosial lainnya (Facebook, Threads, IG, dan lain-lain), berisi materi yang sudah ditulis di dalam GitHub tersebut dan menyertakan URL ke repo yang mereka buat. Proses ini merupakan salah satu metriks evaluasi penilaian.

Pada akhir dari *timeframe*, akan dilakukan evaluasi pemahaman oleh mentor. Evaluasi dilaksanakan secara bebas tetapi transparan. Mentor harus menjelaskan apa saja yang akan dievaluasi dan kemudian melaksanakan evaluasi tersebut. Setiap evaluasi akan dibuatkan berita acara. Evaluasi ini dilakukan untuk mewujudkan MBL. Beberapa contoh evaluasi yang bisa dilakukan:

* Ujian teori (tes lisan terkait pemahaman pembelajar).
* Ujian praktik (tes *coding* / *programming*).

Hasil dari pengujian ini adalah kelanjutan pembelajar di tahap berikutnya: melanjutkan di proses berikutnya atau menguatkan kembali sisi-sisi tertentu sesuai evaluasi dari mentor. Perlu diketahui, evaluasi ini bukan merupakan hal yang bersifat kaku. Pembelajar bisa kembali mengerjakan proses-proses sebelumnya sampai kemudian mendapatakan pemahamana yang mendalam dan kemudian melanjutkan ke proses berikutnya. Hanya saja, jika ini terjadi maka pembelajar yang bersangkutan harus bekerja lebih keras lagi untuk mengikuti *timeframe* sampai selesai.

### Capstone Mandiri - Initiator

_Tujuan_

Pembelajar melaksanakan penugasan terkait materi secara komprehensif. Hasil akhir dari proses ini adalah artefak dengan lisensi free / open source yang diletakkan pada repo Git (GitHub). _Capstone_ harus direncanakan dengan baik dalam bentuk _milestones_ dan tiket-tiket untuk milestones (dari awal sampai rilis). File README.md diletakkan pada repo untuk menjelaskan tentang isi dari repo. Berbagai artefak seperti arsitektur software, milestones, dan dokumentasi tentang software tersebut diletakkan di berbagai file berformat Markdown di direktori docs.

_Timeframe pertama_

* Hari 1 dan 2: pembelajar mencari tema dari proyek _capstone_.
* Hari 3: pembelajar mendiskusikan dengan mentor terkait proyek _capstone_ yang akan dibuat, fitur-fitur, serta milestones untuk menyelesaikan proyek _capstone_ tersebut. Pembelajar (dengan bantuan mentor) menyiapkan infrastruktur.
* Akhir hari 3: dibuat repo dan dalam repo tersebut dibuat README terkait no 2 di atas.

_Timeframe kedua_

* Hari 1 - timeframe selesai: pembelajar mulai mengerjakan proyek _capstone_. Pembelajar mengerjakan pembuatan software dan melengkapi dokumentasi. GitHub releases berisi berbagai rilis (versi Beta, RC1, RC2, dan seterusnya sampai dengan rilis).
* Hari terakhir _timeframe_, pembelajar mempresentasikan hasil pekerjaan. Tim akademik dan mentor melakukan penilaian serta pengujian. Hasil penilaian ini menentukan apakah pembelajar berhasil masuk ke tahap berikutnya atau gagal. Jika gagal, pembelajar akan diberi waktu untuk memperbaiki hasil dan kemudian akan dilakukan evaluasi ulang.

### Capstone Mandiri - *Team Work*

_Tujuan_

Tahap ini digunakan untuk melatih kemampuan bekerjasama antar pembelajar. Team ditentukan oleh akademik dan terdiri atas 3-5 pembelajar. Tim telah dibentuk sebelum memasuki tahap ini. Pada tahap ini, tim bekerja sama untuk mengerjakan task proyek _capstone_ untuk dinilai.

_Timeframe pertama_

* Hari 1 dan 2: tim melakukan *brainstorming* untuk menentukan proyek _capstone_ yang akan dibuat.
* Hari 2: pemberian berbagai materi sesuai konteks proyek _capstone_ serta penggunaan GitHub untuk mengelola proyek bersama.
* Hari 3: tim mendiskusikan dengan mentor terkait proyek _capstone_ yang akan dibuat, fitur-fitur, serta *milestones* untuk menyelesaikan proyek _capstone_ tersebut. Tim (dengan bantuan mentor) menyiapkan infrastruktur untuk penyelesaian proyek _capstone_.
* Akhir hari 3: dibuat repo dan dalam repo tersebut dibuat README terkait no 2 di atas.

_Timeframe kedua_ 

* Hari 1 - selesai (sesuai rancangan): pembelajar mulai mengerjakan pembuatan proyek _capstone_ secara iteratif. Pembelajar mengikuti ritme pengerjaan proyek, termasuk mengalami *deadline*, *pull request* ditolak (jika ada), *stand up meeting*, dan lain-lain.

Pada akhir _timerame_ kedua, bagian akademik serta mentor melakukan evaluasi komprehensif terhadap kemampuan dari pembelajar dengan melihat hasil GitHub personal maupun tim. Pada hari ini, tim mempresentasikan hasil kerja kelompok. Bagian akademik serta para mentor memutuskan pembelajar yang berhasil lulus dari NEO-X School serta pembelajar yang tidak berhasil lulus dari NEO-X School.

### Profesional

Pada proses ini, para pembelajar akan diberikan wawasan maupun pengalaman yang akan membantu mereka dalam mengembangkan diri sebagai profesional di masa depan.
