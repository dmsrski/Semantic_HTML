NAMA : Dimas Riski Anggoro
NIM  : 2205101023
# Semantic_HTML
Latihan praktikum HTML
Analisis kekurangan pada file index.html:

Kekurangan Tag HTML Dasar (<html>, <head>, <body>)

-Kekurangan tag-tag dasar seperti <html>, <head>, dan <body> dapat mengakibatkan struktur dokumen tidak sesuai standar HTML. Meski browser modern biasanya dapat mentoleransi dan menafsirkan dokumen HTML yang tidak lengkap, hal ini tetap merupakan praktik yang buruk dalam pengembangan web karena mengurangi keterbacaan dan mempersulit debugging atau validasi markup.
Solusi: Tambahkan tag dasar ini di awal dan akhir dokumen untuk memastikan struktur HTML yang benar dan agar kode lebih mudah dipahami dan di-maintain oleh developer lain.
Kekurangan Tag <link> untuk Menyertakan CSS Eksternal

-Tanpa tag <link> untuk menyertakan file CSS eksternal, Anda hanya bisa menggunakan inline atau internal CSS. Ini berarti bahwa semua gaya harus didefinisikan dalam file HTML, yang dapat mengurangi modularitas dan menghambat pemeliharaan kode. CSS eksternal memberikan pengaturan gaya yang lebih bersih, terpisah dari markup HTML, sehingga memudahkan pembaruan desain tanpa harus menyentuh file HTML secara langsung.
Solusi: Gunakan tag <link> di dalam elemen <head> untuk menyertakan file CSS eksternal, yang akan memisahkan konten dan gaya, sehingga halaman lebih mudah dikelola.
Kurangnya Meta Tag untuk Pengaturan Dokumen

-Tidak adanya meta tag, seperti charset atau viewport, bisa menyebabkan masalah tampilan, terutama di perangkat seluler. Meta tag membantu dalam penentuan karakter yang digunakan (misalnya UTF-8), serta memberikan skala yang sesuai untuk perangkat mobile, sehingga halaman tampak lebih responsif dan ramah pengguna.
Solusi: Tambahkan meta tag di dalam elemen <head> untuk mengatur karakter dan responsivitas halaman.
Kekurangan Struktur Semantik

-Kurangnya elemen semantik seperti <header>, <footer>, <main>, atau <section> dapat mengurangi keterbacaan HTML dan aksesibilitas halaman. Elemen-elemen semantik ini memudahkan mesin pencari dan pembaca layar untuk memahami konten secara lebih baik.
Solusi: Gunakan elemen semantik untuk memisahkan bagian-bagian halaman dan meningkatkan aksesibilitas dan SEO (Search Engine Optimization).
Dengan memperbaiki kekurangan ini, file index.html akan lebih baik secara struktur, mudah di-maintain, lebih ramah pengguna, dan lebih sesuai dengan standar pengembangan web.
