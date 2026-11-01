Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)indonesian translationMenggunakan Picture-in-Picture (Video Melayang)Menggunakan Picture-in-Picture (Video Melayang)# Belajar Sendiri Ilmu Komputer

> Dokumen ini adalah terjemahan dari [TeachYourselfCS](https://teachyourselfcs.com/). Untuk versi aslinya, [lihat di sini](https://teachyourselfcs.com/).

> Catatan: panduan ini telah diperbarui pada Mei 2020. Untuk versi sebelumnya, [lihat di sini](https://teachyourselfcs.com/2016/).

Jika Anda adalah seorang _engineer_ autodidak atau lulusan _bootcamp_, Anda berutang pada diri Anda untuk mendalami ilmu komputer. Untungnya, Anda bisa mendapat pendidikan ilmu komputer kelas dunia tanpa harus menghabiskan waktu dan uang untuk program sarjana 💸.

Ada banyak sumber belajar di luar sana, tapi beberapa lebih baik dari yang lain. Anda tidak perlu lagi artikel "200+ Kursus Online Gratis". Anda perlu jawaban dari pertanyaan ini:

- **Mata pelajaran** apa yang harus dipelajari, dan mengapa?
- Apa **buku atau seri video pembelajaran terbaik** untuk setiap mata pelajaran?

Panduan ini adalah upaya kami untuk menjawab pertanyaan tersebut.

## TL;DR:

Pelajari kesembilan mata pelajaran di bawah, dalam urutan yang disajikan, baik menggunakan buku teks atau seri video pembelajaran yang disarankan, tapi lebih ideal menggunakan keduanya. Targetkan 100-200 jam belajar untuk setiap topik, lalu ulas kembali topik favorit sepanjang karir Anda 🚀.

| Mata pelajaran                                                          | Mengapa dipelajari?                                                                                                                                                              | Buku                                                | Video                                |
| ----------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------ |
| **[Pemrograman](#pemrograman)**                                         | Jangan menjadi orang yang "tidak mengerti" sesuatu seperti rekursi.                                                                                                              | _Structure and Interpretation of Computer Programs_ | Berkeley CS 61A oleh Brian Harvey    |
| **[Arsitektur Komputer](#arsitektur-komputer)**                         | Jika Anda tidak memiliki pemahaman yang kuat tentang cara kerja komputer, semua abstraksi tingkat tinggi Anda akan rapuh.                                                        | _Computer Systems: A Programmer's Perspective_      | Berkeley CS 61C                      |
| **[Algoritma dan Struktur Data](#algoritma-dan-struktur-data)**         | Jika Anda tidak tahu cara menggunakan struktur data yang sering digunakan seperti tumpukan, antrian, pohon, dan grafik, Anda tidak akan dapat memecahkan masalah yang menantang. | _The Algorithm Design Manual_                       | Video perkuliahan oleh Steven Skiena |
| **[Matematika untuk Ilmu Komputer ](#math-for-cs)**                     | Ilmu komputer pada dasarnya adalah cabang matematika terapan, jadi mempelajari matematika akan memberi Anda keunggulan kompetitif.                                               | _Mathematics for Computer Science_                  | MIT 6.042J oleh Tom Leighton         |
| **[Sistem Operasi](#sistem-operasi)**                                   | Sebagian besar kode yang Anda tulis dijalankan oleh sistem operasi, jadi Anda harus tahu bagaimana mereka berinteraksi.                                                          | _Operating Systems: Three Easy Pieces_              | Berkeley CS 162                      |
| **[Jaringan Komputer](#jaringan-komputer)**                             | Internet telah menjadi suatu hal yang penting: pahami cara kerjanya untuk membuka potensi penuhnya.                                                                              | _Computer Networking: A Top-Down Approach_          | Stanford CS 144                      |
| **[Basis Data](#basis-data)**                                           | Data adalah bagian terpenting inti dari sebuah program, tetapi hanya sedikit yang memahami bagaimana sistem basis data bekerja.                                                  | _Readings in Database Systems_                      | Berkeley CS 186 oleh Joe Hellerstein |
| **[Bahasa Pemrograman dan Kompiler](#bahasa-pemrograman-dan-kompiler)** | Jika Anda memahami cara kerja bahasa pemrograman dan kompiler, Anda dapat menulis kode dengan lebih baik dan mempelajari bahasa pemrograman baru dengan lebih mudah              | _Crafting Interpreters_                             | Kursus online oleh Alex Aiken di edX |
| **[Sistem Terdistribusi](#sistem-terdistribusi)**                       | Saat ini, sebagian besar sistem adalah sistem terdistribusi.                                                                                                                     | _Designing Data-Intensive Applications_             | MIT 6.824                            |

## Masih terlalu banyak?

Jika mempelajari 9 topik selama beberapa tahun terasa berlebihan, kami sarankan Anda fokus hanya pada dua buku: _Computer Systems: A Programmer's Perspective_ dan _Designing Data-Intensive Applications_. Berdasarkan pengalaman kami, kedua buku ini memberikan manfaat yang sangat besar atas waktu yang diinvestasikan, terutama untuk _engineer_ autodidak dan lulusan _bootcamp_ yang bekerja pada aplikasi yang terhubung dengan jaringan. Kedua buku tersebut juga berfungsi sebagai pengantar untuk topik dan sumber belajar lain yang tercantum di atas.

## Mengapa mempelajari ilmu komputer?

<img align="right" width="480" src="https://teachyourselfcs.com/bilotta-tweet.png">

Ada 2 jenis _software engineer_: mereka yang memahami ilmu komputer dengan baik sehingga dapat melakukan pekerjaan yang menantang dan inovatif, dan mereka yang dapat bertahan hanya karena mereka terbiasa menggunakan _framework_, _library_ dan alat-alat lain.

Keduanya disebut _software engineer_, dan keduanya cenderung mendapat gaji yang sama di awal karir mereka. Tetapi _engineer_ jenis pertama punya perkembangan menuju pekerjaan yang lebih memuaskan dengan bayaran yang meningkat seiring waktu, baik itu dari pekerjaan biasa atau proyek _open source_ yang memberi terobosan baru, menjadi pemimpin dalam hal teknis, atau dari kontribusi sebagai individu berkualitas tinggi.

_Engineer_ jenis pertama menemukan cara mempelajari ilmu komputer secara mendalam, baik melalui cara konvensional atau dengan belajar tanpa henti sepanjang karir mereka. _Engineer_ jenis kedua biasanya hanya berada di atas, mempelajari alat dan teknologi tertentu daripada mempelajari fondasi yang mendasarinya, hanya menambah keterampilan baru ketika tren berubah.

Saat ini, jumlah orang yang memasuki industri ini meningkat pesat, sementara jumlah lulusan ilmu komputer relatif tetap. Kelebihan pasokan _engineer_ jenis kedua ini dapat mengurangi kesempatan kerja dan menjauhkan mereka dari pekerjaan yang lebih memuaskan pada industri ini. Apakah karena Anda ingin menjadi _engineer_ jenis pertama atau sekadar mencari keamanan kerja yang lebih tinggi, mempelajari ilmu komputer adalah satu-satunya jalan yang dapat diandalkan.

## Panduan mata pelajaran

### Pemrograman

<img align="right" width="200" src="https://teachyourselfcs.com/sicp.jpg">

Sebagian besar program sarjana ilmu komputer dimulai dengan "pengantar" pemrograman komputer. Versi terbaik dari kursus ini tidak hanya diperuntukkan bagi pemula, tetapi juga bagi mereka yang melewatkan konsep dan model pemrograman yang penting ketika pertama kali belajar.

Rekomendasi kami untuk topik ini adalah buku klasik _Structure and Interpretation of Computer Programs_, yang tersedia secara daring dan gratis baik sebagai [buku](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), maupun sebagai seri [video perkuliahan dari MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Meskipun seri video tersebut bagus, kami lebih menyarankan video kuliah SICP oleh Brian Harvey (untuk kursus 61A di Berkeley). Video kuliah ini lebih baik dan lebih pantas ditargetkan pada mahasiswa baru daripada video kuliah dari MIT.

Kami merekomendasikan untuk setidaknya menyelesaikan tiga bab pertama SICP beserta latihannya. Untuk latihan tambahan, Anda bisa mengerjakan masalah pemrograman seperti yang ada pada [exercism](https://exercism.org/).

Sejak panduan ini pertama kali diterbitkan pada tahun 2016, salah satu pertanyaan yang paling sering diajukan adalah apakah kami akan merekomendasikan rekaman terbaru kuliah 61A yang diajarkan oleh John DeNero, dan/atau buku panduannya [_Composing Programs_](https://composingprograms.com/), yang "sesuai dengan tradisi SICP" tetapi menggunakan Python. Menurut kami sumber belajar dari DeNero juga bagus, dan beberapa siswa mungkin akhirnya lebih menyukainya, tetapi kami tetap menyarankan SICP, Scheme, dan video kuliah oleh Brian Harvey sebagai rangkaian sumber belajar pertama untuk dicoba.

Mengapa? Karena SICP sangat unik dalam kemampuannya—setidaknya secara potensial—untuk mengubah pemahaman dasar Anda tentang komputer dan pemrograman. Tidak semua orang akan merasakannya. Beberapa akan membenci buku itu, bahkan ada yang tidak akan melewati beberapa halaman pertama. Tetapi potensi manfaatnya membuatnya layak untuk dicoba.

Jika Anda tidak dapat menikmati SICP, cobalah _Composing Programs_. Jika masih tidak sesuai, maka cobalah [_How to Design Programs_](https://htdp.org/). Jika tidak ada satu pun dari buku-buku ini yang memberi manfaat bagi Anda, mungkin itu pertanda bahwa Anda harus fokus pada topik lain untuk sementara waktu, dan meninjau kembali disiplin ilmu pemrograman dalam satu atau dua tahun ke depan.

Dan terakhir, satu poin klarifikasi: panduan ini TIDAK dirancang untuk mereka yang baru memulai pemrograman. Kami berasumsi bahwa Anda adalah seorang _programmer_ yang kompeten tanpa latar belakang ilmu komputer, yang ingin mengisi kesenjangan pengetahuan. Alasan kami menyertakan bagian tentang "pemrograman" hanyalah pengingat bahwa mungkin masih ada banyak hal untuk dipelajari. Bagi mereka yang belum pernah menulis kode sebelumnya, dan ingin memulai, Anda mungkin lebih suka panduan seperti ini.

### Arsitektur Komputer

<img align="right" width="200" src="https://teachyourselfcs.com/csapp.jpg">

> Perangkat keras adalah platformnya

– _Mike Acton, Engine Director Insomniac Games_

Arsitektur Komputer—kadang disebut "sistem komputer" atau "organisasi komputer"—adalah hal pertama yang patut dilihat pada komputasi di balik perangkat lunak. Dari pengalaman kami, inilah bagian yang paling sering diabaikan para _software engineer_ autodidak.

Buku pengantar favorit kami adalah [_Computer Systems: A Programmer's Perspective_](https://csapp.cs.cmu.edu/3e/home.html), dan kuliah pengantar arsitektur komputer yang menggunakan buku ini biasanya [akan mencakup](https://csapp.cs.cmu.edu/3e/courses.html) sebagian besar bab 1 sampai 6.

Kami menyukai buku _CS:APP_ karena pendekatannya yang praktis dan berorientasi pada pemrogram. Meskipun masih ada banyak hal tentang arsitektur komputer yang tidak terdapat dalam buku ini, _CS:APP_ sangat cocok sebagai pengantar bagi mereka yang ingin memahami sistem komputer terutama untuk membuat perangkat lunak yang lebih cepat, lebih efisien, dan lebih andal.

Bagi mereka yang lebih suka pengenalan topik arsitektur komputer yang lebih ringan dan seimbang antara perangkat keras dan perangkat lunak, kami menyarankan _The Elements of Computing Systems_, juga dikenal sebagai _Nand2Tetris_. Buku ini mencoba memberi Anda pemahaman yang padu tentang cara kerja segala sesuatu yang terdapat pada komputer. Setiap bab membangun bagian kecil dari keseluruhan sistem, mulai dari menulis _logic gate_ dasar dalam HDL, melalui CPU dan _assembler_, hingga aplikasi seukuran permainan Tetris.

Kami menyarankan Anda untuk membaca enam bab pertama buku ini dan menyelesaikan proyek latihannya. Hal ini dapat mengembangkan pemahaman Anda tentang hubungan antara arsitektur sebuah mesin dan perangkat lunak yang berjalan di atasnya.

Separuh pertama buku ini (dan semua proyek latihannya) tersedia secara gratis melalui [situs web _Nand2Tetris_](https://www.nand2tetris.org/). Materi buku ini juga tersedia dalam bentuk video melalui [kursus daring dari Coursera](https://www.coursera.org/learn/build-a-computer).

_Nand2Tetris_ menukar pembahasan yang mendalam dengan kesederhanaan dan keterpaduan. Khususnya dua konsep yang sangat penting dalam arsitektur komputer modern, yaitu _pipelining_ dan _memory hierarchy_, tetapi keduanya hampir tidak ada dalam buku ini.

Setelah Anda merasa nyaman dengan _Nand2Tetris_, kami sarankan untuk mencoba kembali buku _CS:APP_, atau mempertimbangkan [_Computer Organization and Design_](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269) oleh Patterson dan Hennessy, sebuah buku teks klasik yang sangat bagus. Anda tidak harus membaca setiap bagian dari buku ini; kami menyarankan Anda untuk mengikuti kuliah [CS61C](https://inst.eecs.berkeley.edu/~cs61c/sp15/) _Great Ideas in Computer Architecture_ dari Berkeley untuk bacaan tertentu dalam buku ini. Catatan kuliahnya tersedia secara daring, dan kuliah sebelumnya [terdapat di Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

### Algoritma dan Struktur Data

<img align="right" height="280" src="https://teachyourselfcs.com/polya.jpg">
<img align="right" height="280" src="https://teachyourselfcs.com/skiena.jpg">

> Saya hanya memiliki satu metode yang sangat saya anjurkan—berpikirlah sebelum menulis.

— _Richard Hamming_

Kami sependapat dengan pandangan yang telah diterima selama puluhan tahun bahwa pemahaman tentang algoritma dan struktur data yang umum digunakan adalah salah satu bekal paling berharga dari pendidikan ilmu komputer. Topik ini juga sangat baik untuk melatih kemampuan pemecahan masalah secara umum, yang akan bermanfaat di setiap bidang studi lainnya.

Ada ratusan buku yang tersedia, tetapi favorit kami adalah [_The Algorithm Design Manual_](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) karya Steven Skiena. Kecintaannya pada pemecahan masalah algoritmik terlihat jelas, dan ia biasanya berhasil menumbuhkan antusiasme serupa pada mahasiswa dan pembacanya. Menurut kami, dua buku yang lebih sering direkomendasikan (CLRS dan Sedgewick) cenderung terlalu menekankan pembuktian bagi mereka yang mempelajari materi ini terutama untuk membantu memecahkan masalah praktis.

Bagi yang lebih menyukai video perkuliahan, [Skiena dengan murah hati menyediakan video kuliahnya secara daring](https://www3.cs.stonybrook.edu/~skiena/373/videos/). Kami juga sangat menyukai kursus Tim Roughgarden, yang tersedia [di Coursera](https://www.coursera.org/specializations/algorithms) dan [di tempat lain](http://timroughgarden.org/videos.html). Pilihan antara gaya mengajar Skiena dan Roughgarden bergantung pada preferensi masing-masing. Sebenarnya, ada puluhan alternatif yang bagus, jadi jika Anda menemukan yang Anda sukai, kami menyarankan Anda untuk tetap mengikutinya!

Untuk latihan, pendekatan yang kami sukai adalah mengerjakan soal-soal di [Leetcode](http://leetcode.com). Soal-soalnya cenderung menarik, disertai solusi dan pembahasan yang cukup baik. Soal-soal tersebut juga membantu Anda mengukur kemajuan melalui pertanyaan yang umum digunakan dalam wawancara teknis di perusahaan perangkat lunak yang lebih kompetitif. Kami menyarankan Anda mengerjakan sekitar 100 soal Leetcode secara acak sebagai bagian dari pembelajaran Anda.

Terakhir, kami sangat merekomendasikan [_How to Solve It_](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/) sebagai panduan pemecahan masalah secara umum yang sangat bagus dan unik; isinya sama relevannya untuk ilmu komputer maupun matematika.

### Matematika untuk Ilmu Komputer

> Jika orang tidak percaya bahwa matematika itu sederhana, itu hanya karena mereka tidak menyadari betapa rumitnya kehidupan.

— _John von Neumann_

Dalam beberapa hal, ilmu komputer adalah cabang matematika terapan yang berkembang pesat. Meskipun banyak _software engineer_ berusaha—dan dengan tingkat keberhasilan yang berbeda-beda—untuk mengabaikan hal ini, kami mendorong Anda untuk mempelajari matematika secara langsung. Jika berhasil, Anda akan memiliki keunggulan kompetitif yang sangat besar dibandingkan mereka yang tidak melakukannya.

Bidang matematika yang paling relevan bagi ilmu komputer secara umum disebut “matematika diskrit”. “Diskrit” adalah kebalikan dari “kontinu”, dan istilah ini secara longgar mencakup berbagai topik menarik dalam matematika terapan di luar kalkulus. Karena definisinya tidak tegas, tidak masuk akal untuk mencoba mempelajari seluruh cakupan matematika diskrit. Tujuan yang lebih realistis adalah membangun pemahaman praktis tentang logika, kombinatorika dan probabilitas, teori himpunan, teori graf, serta sedikit teori bilangan yang mendasari kriptografi. Aljabar linear juga patut dipelajari, mengingat pentingnya bidang ini dalam grafika komputer dan _machine learning_.

Sebagai titik awal untuk matematika diskrit, kami menyarankan [catatan kuliah László Lovász](https://cims.nyu.edu/~regev/teaching/discrete_math_fall_2005/dmbook.pdf). Profesor Lovász berhasil menyajikan materinya secara mudah dipahami dan intuitif, sehingga catatan ini lebih cocok sebagai titik awal daripada buku teks yang lebih formal.

Untuk pembahasan yang lebih lanjut, kami menyarankan [_Mathematics for Computer Science_](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf), catatan kuliah sepanjang buku untuk mata kuliah MIT dengan nama yang sama. Video perkuliahannya juga [tersedia secara gratis](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/video_galleries/video-lectures/), dan merupakan video yang kami rekomendasikan untuk matematika diskrit.

Untuk aljabar linear, kami menyarankan Anda memulai dengan seri video [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), lalu melanjutkan dengan [buku](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) dan [video perkuliahan](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/) Gilbert Strang.

### Sistem Operasi

<img align="right" width="200" src="https://teachyourselfcs.com/ostep.jpeg">

[_Operating System Concepts_](https://www.amazon.com/dp/1118063333/) ("_Dinosaur book_") dan [_Modern Operating Systems_](https://www.amazon.com/dp/1118063333/) adalah dua buku "klasik" tentang sistem operasi. Keduanya menuai kritik karena kurang jelas dan tidak ramah bagi siswa pada umumnya.

_Operating Systems: Three Easy Pieces_ adalah alternatif yang [tersedia gratis secara daring](https://pages.cs.wisc.edu/~remzi/OSTEP/). Kami sangat menyukai struktur dan keterbacaan buku ini, dan merasa bahwa latihan yang terdapat pada buku ini sangat bermanfaat.

Setelah OSTEP, kami ingin Anda mengeksplorasi beberapa keputusan pada rancangan sistem operasi tertentu, melalui beberapa buku "{nama sistem operasi} Internals" seperti [_Lions' commentary on Unix_](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/), [_The Design and Implementation of the FreeBSD Operating System_](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/), dan [_Mac OS X Internals_](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/). Untuk Linux, kami menyarankan buku Robert Love yang luar biasa, yaitu [_Linux Kernel Development_](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468).

Cara yang bagus untuk memperkuat pemahaman Anda tentang sistem operasi adalah dengan membaca _source code_ dari kernel sistem operasi kecil dan mencoba menambahkan fitur baru. Salah satu pilihan adalah [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), sebuah _port_ sistem operasi Unix V6 ke bahasa ANSI C dan arsitektur x86, yang dikembangkan untuk pembelajaran di MIT. Pada buku OSTEP terdapat lampiran [xv6 labs](https://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) yang penuh dengan ide-ide hebat untuk proyek-proyek potensial.

### Jaringan Komputer

<img align="right" width="200" src="https://teachyourselfcs.com/top-down.jpg">

> Anda tidak bisa menatap bola kristal dan melihat masa depan. Apa yang akan menjadi Internet di masa depan adalah apa yang dibuat oleh masyarakat.

— _Bob Kahn_

Mengingat begitu banyak rekayasa perangkat lunak ada di server dan klien web, salah satu bidang ilmu komputer yang paling penting adalah jaringan komputer. Siswa kami yang mempelajari jaringan secara autodidak menemukan bahwa mereka akhirnya memahami istilah, konsep, dan protokol yang telah berada di sekitar mereka selama bertahun-tahun.

Buku favorit kami tentang topik ini adalah [_Computer Networking: A Top-Down Approach_](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/). Proyek-proyek kecil dan latihan dalam buku ini sangat layak untuk dikerjakan, dan kami sangat menyukai _Wireshark labs_ yang telah mereka [sediakan gratis secara daring](http://www-net.cs.umass.edu/wireshark-labs/).

Bagi mereka yang lebih menyukai materi dalam bentuk video, kami menyarankan video kuliah [_Introduction to Computer Networking_](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS) dari Stanford yang sebelumnya ada pada platform belajar online mereka, tapi sayangnya sekarang hanya tersedia sebagai playlist tidak resmi di YouTube.

### Basis Data

<img align="right" width="200" src="https://teachyourselfcs.com/redbook.jpg">
<img align="right" width="200" src="https://teachyourselfcs.com/data-reality.jpg">

Belajar mandiri tentang sistem basis data membutuhkan lebih banyak usaha dibandingkan kebanyakan topik lainnya. Bidang ini relatif baru (berkembang setelah tahun 1970-an), dan ada insentif komersial yang kuat untuk merahasiakan berbagai gagasannya. Selain itu, banyak calon penulis buku teks yang mungkin sangat baik justru memilih bergabung dengan perusahaan atau mendirikan perusahaan sendiri.

Karena itu, kami menyarankan pembelajar mandiri untuk tidak langsung menggunakan buku teks, melainkan memulai dengan [rekaman kuliah CS 186](https://www.youtube.com/user/CS186Berkeley/videos), mata kuliah basis data Joe Hellerstein di Berkeley, lalu melanjutkan dengan membaca makalah.

Salah satu makalah yang sangat layak disebutkan bagi pelajar baru adalah “[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)”, yang memberikan gambaran umum tentang cara kerja sistem manajemen basis data relasional (RDBMS) dengan cara yang sulit ditemukan di tempat lain. Makalah ini dapat menjadi kerangka yang berguna untuk studi lebih lanjut.

_Readings in Database Systems_, yang lebih dikenal sebagai [“Red Book” untuk basis data](http://www.redbook.io/), adalah kumpulan makalah yang disusun dan disunting oleh Peter Bailis, Joe Hellerstein, dan Michael Stonebraker. Jika Anda sudah menguasai materi CS 186, Red Book sebaiknya menjadi sumber belajar berikutnya.

Jika Anda tetap ingin menggunakan buku teks pengantar, kami menyarankan [_Database Management Systems_](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/) karya Ramakrishnan dan Gehrke. Bagi pelajar yang lebih lanjut, buku klasik Jim Gray, [_Transaction Processing: Concepts and Techniques_](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902), patut dibaca, tetapi kami tidak menyarankannya sebagai sumber belajar pertama.

Terakhir, pemodelan data adalah aspek dalam bekerja dengan basis data yang sering diabaikan dan kurang baik diajarkan. Buku yang kami sarankan untuk topik ini adalah [_Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World_](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215).

### Bahasa Pemrograman dan Kompiler

<img align="right" width="200" src="https://teachyourselfcs.com/dragon.jpg">

> Jangan menjadi pemrogram yang hanya menulis kode berulang. Sebaliknya, buatlah alat untuk pengguna dan pemrogram lain. Belajarlah dari sejarah industri tekstil dan baja: apakah Anda ingin membangun mesin dan alat, atau sekadar mengoperasikannya?

— _Ras Bodik pada awal kuliah kompilernya_

Kebanyakan pemrogram mempelajari bahasa pemrograman, sedangkan kebanyakan ilmuwan komputer mempelajari _tentang_ bahasa pemrograman. Hal ini memberi ilmuwan komputer keunggulan tersendiri dibandingkan pemrogram, bahkan dalam bidang pemrograman! Pengetahuan mereka dapat diterapkan secara lebih luas; mereka mampu memahami cara kerja bahasa baru dengan lebih mendalam dan lebih cepat daripada mereka yang hanya mempelajari bahasa tertentu.

Buku pengantar yang kami sarankan adalah [_Crafting Interpreters_](https://craftinginterpreters.com/contents.html) karya Bob Nystrom, yang sangat bagus dan tersedia gratis secara daring. Buku ini tersusun dengan baik, sangat menyenangkan untuk dibaca, dan cocok bagi mereka yang tujuan utamanya adalah memahami bahasa pemrograman dan alat-alatnya dengan lebih baik. Kami menyarankan Anda meluangkan waktu untuk membaca dan mengerjakan seluruh buku ini, serta mencoba tantangan mana pun yang menarik bagi Anda.

Rekomendasi yang lebih tradisional adalah [_Compilers: Principles, Techniques & Tools_](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811), yang biasa disebut “Dragon Book”. Sayangnya, buku ini tidak dirancang untuk belajar mandiri, melainkan agar dosen dapat memilih materi untuk perkuliahan selama satu atau dua semester.

Jika Anda memilih menggunakan Dragon Book, Anda hampir pasti perlu memilih topik-topik tertentu, idealnya dengan bantuan seorang mentor. Bahkan, kami menyarankan agar Anda menggunakan Dragon Book sebagai referensi pelengkap untuk seri video perkuliahan. Seri yang kami rekomendasikan adalah [kuliah Alex Aiken di edX](https://www.edx.org/course/compilers).

### Sistem Terdistribusi

<img align="right" width="200" src="https://teachyourselfcs.com/ddia.jpg">

Semakin bertambahnya jumlah komputer, _penyebaran_ penggunaannya pun semakin luas. Jika sebelumnya pelaku bisnis akan membeli _mainframe_ yang lebih besar, saat ini sudah cukup lumrah bagi aplikasi kecil untuk berjalan di beberapa mesin. Sistem terdistribusi adalah studi tentang bagaimana memilih _trade-off_ yang terlibat dalam melakukan hal tersebut.

Buku yang kami sarankan untuk belajar mandiri adalah [_Designing Data-Intensive Applications_](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/) oleh Martin Kleppmann. Buku yang jauh lebih baik daripada buku teks tradisional, DDIA adalah buku yang sangat mudah dibaca yang dirancang untuk para praktisi tanpa mengorbankan kedalaman atau ketelitian.

Bagi yang mencari buku teks yang lebih tradisional atau lebih menyukai buku yang tersedia gratis secara daring, kami menyarankan [_Distributed Systems, 3rd Edition_](https://www.distributed-systems.net/index.php/books/ds3/) karya Maarten van Steen dan Andrew Tanenbaum.

Bagi yang lebih menyukai video, [MIT 6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) adalah mata kuliah pascasarjana yang sangat baik dengan video yang tersedia secara daring. Mata kuliah ini diajarkan oleh Robert Morris, dan bahan bacaannya tersedia [di sini](https://pdos.csail.mit.edu/6.824/schedule.html).

Apa pun buku teks atau sumber belajar tambahan yang Anda pilih, mempelajari sistem terdistribusi mutlak memerlukan membaca makalah. Daftar makalah yang bagus tersedia [di sini](http://dsrg.pdos.csail.mit.edu/papers/), dan kami sangat menganjurkan Anda mengikuti pertemuan komunitas [Papers We Love](http://paperswelove.org/) di daerah Anda.

## Pertanyaan yang sering diajukan

#### Untuk siapa panduan ini dibuat?

Kami paham bahwa Anda adalah seorang _software engineer_ autodidak, lulusan _bootcamp_ atau siswa SMA yang ingin tahu, atau mahasiswa yang ingin melengkapi pendidikan formal Anda dengan belajar mandiri. Pertanyaan tentang kapan memulai perjalanan ini sepenuhnya bersifat pribadi, tetapi kebanyakan orang cenderung mendapat manfaat dari memiliki beberapa pengalaman profesional sebelum menyelam terlalu jauh ke dalam teori ilmu komputer. Misalnya, kami melihat bahwa siswa suka belajar tentang sistem basis data jika mereka telah bekerja dengan basis data secara profesional, atau tentang jaringan komputer jika mereka pernah mengerjakan satu atau dua proyek aplikasi web.

#### Bagaimana dengan AI/grafis/topik favorit X?

Kami telah mencoba membatasi daftar kami pada topik ilmu komputer yang kami rasa perlu diketahui oleh setiap _software engineer_, terlepas dari spesialisasi atau industri, tetapi dengan fokus pada sistem. Dari pengalaman kami, ini akan menjadi topik dengan manfaat terbesar untuk sebagian besar _engineer_ autodidak dan lulusan _bootcamp_, dan memberikan dasar yang kuat untuk studi lebih lanjut. Selanjutnya, Anda akan berada dalam posisi yang jauh lebih baik untuk membaca buku teks atau makalah lanjutan dan mempelajari konsep utama tanpa banyak panduan. Berikut adalah titik awal yang kami sarankan untuk beberapa "topik pilihan" umum:

- Untuk topik kecerdasan buatan: selesaikan [kursus pengantar AI dari Berkeley](http://ai.berkeley.edu/) dengan menonton video dan mengerjakan proyek Pacman yang luar biasa. Untuk buku teks, gunakan _Artificial Intelligence: A Modern Approach_ oleh Russell dan Norvig.
- Untuk topik _machine learning_: selesaikan kursus di Coursera oleh Andrew Ng. Bersabarlah, dan pastikan Anda memahami dasar-dasarnya sebelum beralih ke topik baru yang menarik seperti _deep learning_.
- Untuk grafik komputer: pelajari materi [CS 184 Berkeley](https://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), dan gunakan [_Computer Graphics: Principles and Practice_](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) sebagai buku teks.

#### Seberapa ketat urutan yang disarankan?

Jika diperhatikan, semua mata pelajaran ini memiliki sejumlah bagian yang saling tumpang tindih, dan saling merujuk satu sama lain. Anda dapat mengambil contoh hubungan antara matematika diskrit dan algoritma: mempelajari matematika terlebih dahulu akan membantu Anda menganalisis dan memahami lebih dalam algoritma Anda, tetapi mempelajari algoritma terlebih dahulu akan memberikan motivasi dan konteks yang lebih besar untuk matematika diskrit. Idealnya, Anda akan mengunjungi kembali kedua topik ini berkali-kali sepanjang karier Anda.

Dengan demikian, urutan yang kami sarankan dapat membantu Anda _untuk langsung memulai_... jika Anda memiliki alasan kuat untuk memilih urutan yang berbeda, maka lakukanlah. Beberapa "prasyarat" yang menurut kami penting adalah: arsitektur komputer sebelum sistem operasi atau database, dan jaringan dan sistem operasi sebelum sistem terdistribusi.

#### Apa perbedaan panduan ini dengan kurikulum Open Source Society atau freeCodeCamp?

Ketika panduan ini pertama kali ditulis pada tahun 2016, [panduan OSS](https://github.com/open-source-society/computer-science) membahas terlalu banyak mata pelajaran, menyarankan sumber belajar yang tidak lebih baik dari kebanyakan, dan tidak memberikan alasan atau panduan seputar mengapa atau aspek apa dari kursus tertentu yang lebih bermanfaat. Kami berusaha untuk membatasi daftar kursus kami hanya untuk kursus yang _benar-benar harus Anda ketahui_ sebagai _software engineer_, terlepas dari spesialisasi Anda, dan untuk membantu Anda memahami mengapa setiap kursus disertakan. Di tahun-tahun berikutnya, kualitas panduan OSS telah meningkat, tetapi kami masih berpikir bahwa panduan ini memberikan jalur pembelajaran yang lebih jelas dan lebih terpadu.

freeCodeCamp sebagian besar berfokus pada pemrograman, bukan ilmu komputer. Untuk alasan mengapa Anda mungkin ingin mempelajari ilmu komputer, coba lihat [di atas](#mengapa-mempelajari-ilmu-komputer). Jika Anda baru memulai pemrograman, kami sarankan untuk memprioritaskan kurikulum tersebut, dan kembali ke panduan ini dalam satu atau dua tahun ke depan.

#### Bagaimana dengan bahasa pemrograman X?

Mempelajari bahasa pemrograman tertentu adalah hal yang sangat berbeda dengan mempelajari bidang pada ilmu komputer — mempelajari bahasa pemrograman jauh _lebih mudah_ dan _tidak lebih penting_ manfaatnya. Jika Anda sudah mengetahui beberapa bahasa pemrograman, kami sangat menyarankan Anda untuk mengikuti panduan kami dan menyesuaikan penguasaan bahasa pemrograman di sela waktu, atau setelah menyelesaikannya. Jika Anda telah mempelajari pemrograman dengan baik (seperti melalui _Structure and Interpretation of Computer Programs_), dan terutama jika Anda telah mempelajari kompiler, Anda hanya akan membutuhkan waktu setidaknya satu akhir pekan untuk mempelajari bahasa pemrograman baru, setelah itu Anda dapat mempelajarinya tentang _library_/_tooling_/ekosistem di tempat kerja.

#### Bagaimana dengan teknologi terbaru X?

Tidak ada satu teknologi pun yang lebih penting sehingga belajar menggunakannya harus menjadi bagian inti dari pendidikan Anda. Di sisi lain, adalah hal yang sangat bagus bahwa Anda bersemangat untuk mempelajari teknologi tersebut. Triknya adalah memulai dari bidang atau konsep yang mendasari teknologi tertentu, dan mempelajarinya secara mendalam sebelum melihat bagaimana teknologi terbaru Anda mengisi gambaran yang lebih besar.

#### Mengapa Anda masih merekomendasikan SICP?

Anda perlu mencoba buku SICP. Beberapa orang menganggap SICP mencengangkan, ciri yang hanya dimiliki oleh segelintir buku. Jika Anda tidak menyukainya, Anda dapat mencoba buku lain dan setelah itu mungkin kembali ke SICP.

#### Mengapa Anda masih merekomendasikan _Dragon book_?

_Dragon book_ masih merupakan sumber tunggal terlengkap untuk topik seputar kompiler. Buku tersebut sering mendapat reputasi buruk, biasanya karena terlalu menekankan pada topik tertentu yang kurang populer untuk dibahas secara detail, seperti _parsing_. Masalahnya adalah, buku itu tidak pernah dimaksudkan untuk dipelajari dari sampul ke sampul, hanya untuk menyediakan materi pembelajaran yang cukup bagi seorang instruktur untuk menyusun materi kuliah. Demikian pula, seorang pembelajar mandiri dapat memilih petualangan mereka melalui buku, atau lebih baik mengikuti saran yang telah dibuat oleh dosen dalam garis besar mata kuliah mereka.

#### Bagaimana saya bisa mendapatkan buku teks yang terjangkau?

Kebanyakan dari buku teks yang kami sarankan tersedia secara daring dan gratis, berkat kemurahan hati penulisnya. Untuk buku yang tidak tersedia gratis, kami sarankan untuk membeli buku bekas edisi lama. Sebagai aturan umum, jika suatu buku teks punya lebih dari beberapa edisi, kemungkinan besar edisi lama sudah cukup memadai. Jelas tidak mungkin versi terbaru 10x lebih baik daripada yang lama, meskipun harganya berbeda!

#### Siapa yang menulis panduan ini?

Panduan ini ditulis oleh [Oz Nova](https://twitter.com/oznova_) dan [Myles Byrne](https://twitter.com/quackingduck), dengan pembaruan pada tahun 2020 oleh Oz. Panduan ini dibuat berdasarkan pengalaman kami mengajar dasar-dasar ilmu komputer kepada lebih dari 1000 _engineer_ autodidak atau lulusan _bootcamp_ dalam kelompok kecil di San Francisco dan secara daring. Terima kasih kepada semua siswa kami atas masukan tentang sumber belajar mandiri.

Kami yakin Anda dapat mempelajari semua hal di atas, dengan waktu dan motivasi yang cukup. Tetapi jika Anda lebih menyukai program intensif, terstruktur, dan dibimbing oleh instruktur, Anda mungkin tertarik dengan program [Computer Science Intensive](https://bradfieldcs.com/csi/) dari kami. Kami [TIDAK](https://ozwrites.com/masters/) menyarankan untuk mengejar gelar magister.
