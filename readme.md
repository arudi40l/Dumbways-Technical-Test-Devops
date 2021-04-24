1.sangat penting, dimana dalam mengembang sebuah inovasi / aplikasi baru dari perusahaan, dibutuhkan alur dan cara kerja yang efektif, efisien, dan terorganisir agar mencapai hasil yang maksimal, baik untuk konsumen maupun perusahaan.
Dimulai dari proses Pengembangan awal di jaringan local, kemudian ke peer review dimana aplikasi kita dicheck, jika berhasil maka akan ada proses diskusi tanya jab tentang bug dan keamanan aplikasinya, jika lulus kita masuk ke pre-prod dimana aplikasi dicoba diluncurkan, dan terakhir di production dimana aplikasi benar2 bisa digunakan bebas di internet tanpa ada masalah.

2. openstack adalah salah satu software untuk cloud computing, sedangkan 
OpenStack merupakan project open source untuk platform cloud computing atau dalam bahasa Indonesia kita dapat mengenal OpenStack sebagai platform untuk komputasi awan dari berbagai tipe cloud.
 sama seperti openstuck dimana mereka menyediakan pengembangan suatu hal berbasis cloud (computing, storage, dll), hanya saja bedanya openstack itu opensource yang menjadikannya gratis dan bebas dikembangkan oleh orang lain, sedangkan aws berbayar dan closed source jadi source kodenya tidak dibagikan dan dikembangkan sendiri secara tertutup.

banyak perbedaan yang signifikan antara aws dan openstack, tetapi saya tidak akan membahas semuanya, yang saya bahas hanyalah 7 dari bawah yaitu :
- Speech atau Voice, AWS memilik Lex
- Text to speech tool, AWS memiliki Amazon Polly
- Personal Voice Asistant, AWS memiliki Alexa
- Application development platforms, AWS Memiliki Mobile HUB, Mobile SDK, Cognito
- AWS mendukung Machine Learning / NLP
- AWS Support IOT
- AWS memiliki Kinesis untuk  Streaming ANalytic Data
sedangkan openstuckk tidak mendukung satu hal pun dari hal diatas

ini dikarenakan memang dari awal openstuckk hanya fokus untuk cloud computing dan cloud storage, juga lisensinya yang opensource mungkin menjadi kurangnya perkembangan aplikasi tersebut.

3. https://youtu.be/KOyLertNUAs

4. untuk mengembangkan aplikasi tingkat tinggi, memperpendek proses pengembangan aplikasi yang membuatnya efektif dan efisien dalam bekerja, dan nanti hasilnya adalah kepuasan kepada customer. Itulah sesuatu yang diinginkan setiap perusahaan.
dimulai dari memulai membuat versi aplikasi, kita build aplikasinya, kemudian masuk ke CI, kita compile, validasi kelayakan, review pengkodeannya, mentest aplikasinya, jika berhasil selanjutnya masuk ke CD, kita Deploy / sebarkan aplikasinya untuk di test ke server, kita tingkatkan peformanya jika ada yang kurang, dan terakhir kita gunakan aplikasinya baik bagi kita, konsumen ataupun masyarakat.

5. - tutup port yang tidak digunakan
- gunakan enkripsi
- selalu update aplikasi yang digunakan
- rutin pantau jalan pekerjaan baik ketika ontime (bekerja) ataupun offtime (ketika sedang tidak bekerja)

6. cara kerjannya adalah pertama si aplikasi (contoh nginx untuk web server) mengecek kepada seluruh server yang terhubung, kemudian memantau mana yang "backend-nya"(sistem webnya) lebih kecil, nah yang paling kecil itulah nanti ayng akan ditambahkan bebannya. dengan kata lain http & load balancer adalah cara untuk mengoptimalkan beban pada server dimana yang kecil (trafficnya) ditambahkan dan yang besar dikurangkan.

7. Reverse Proxy adalah sebutan untuk aplikasi atau software yang terhubung diantara pengguna dan web server. tujuan dari reverse proxy diantaranya adalah untuk keamanan ataupun meringankan beban server (cache). jadi semisal seorang client 1 pernah mengakses web asdf.com, nah ketika ada client 2 yang mencoba membuka web yang sudah pernah dibuka client yang lain, si reverse proxy akan mengunduh berkas yang dibutuhkan untuk menjadikannya cache, dimana nanti ketika server diminta web yang sama, server tidak perlu mencoba terhubung ke webnya, cukup mengambil dari cache.

8. https://youtu.be/a5LgvakBxlc