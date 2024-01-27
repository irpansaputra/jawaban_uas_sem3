# nama : irpan saputra
nim : i.2210911

kelas : ilmu komputer sem3 sore



jawaban :
 (1.) 
 {
  "sub": "1234567890",
  "name": "John Doe",
  "iat": 1516239022
}


(2.)
Aspek                        | Arsitektur Monolitik                    | Arsitektur Microservices
-----------------------------|-----------------------------------------|----------------------------
Struktur Aplikasi            | Satu unit besar, terintegrasi sebagai satu aplikasi tunggal. | Terdiri dari banyak layanan terpisah yang dapat dikembangkan dan diimplementasikan secara independen.
Skalabilitas                 | Skalabilitas vertikal dengan meningkatkan daya komputasi pada satu mesin. | Skalabilitas horizontal dengan menambahkan instansi dari layanan yang spesifik.
Pengembangan dan Pemeliharaan| Pembaruan dan pengembangan memerlukan perubahan pada seluruh monolit. | Layanan dapat dikembangkan, diuji, dan diterapkan secara independen. Pemeliharaan lebih mudah karena fokus pada layanan tertentu.
Ketergantungan Teknologi Bahasa Pemrograman | Satu bahasa pemrograman untuk seluruh aplikasi. | Beragam bahasa pemrograman dapat digunakan untuk setiap layanan sesuai kebutuhan.
Ketergantungan Komponen Teknologi | Komponen saling tergantung dan berbagi database umum. | Layanan dapat memiliki teknologi dan database yang berbeda-beda. Ketergantungan diatur melalui antarmuka API.
Pengelolaan Data             | Satu database tunggal yang digunakan oleh seluruh aplikasi. | Setiap layanan memiliki database sendiri-sendiri, dan data diatur sesuai kebutuhan layanan tersebut.

(3). Middleware merupakan perangkat lunak yang dapat memberikan banyak manfaat bagi pengembangan dan pemeliharaan aplikasi. Dengan penerapan middleware yang tepat, organisasi dapat meningkatkan efisiensi, produktivitas, skalabilitas, keamanan, dan interoperabilitas dari aplikasi-aplikasinya.
-keuntungan penerapan dari middlewere
1. Meningkatkan efisiensi dan produktivitas. Middleware dapat membantu menyederhanakan proses komunikasi antar elemen, sehingga dapat meningkatkan efisiensi dan produktivitas dalam pengembangan dan pemeliharaan aplikasi.
2. Meningkatkan skalabilitas. Middleware dapat membantu aplikasi untuk menskalakan ukuran dan kinerjanya sesuai dengan kebutuhan.
3. Meningkatkan keamanan. Middleware dapat membantu melindungi aplikasi dari serangan dan penyalahgunaan.
4. Meningkatkan interoperabilitas. Middleware dapat membantu aplikasi untuk berkomunikasi dengan aplikasi lain yang berbeda platform atau bahasa pemrograman.

(4.) Unit testing adalah jenis pengujian perangkat lunak di mana komponen atau unit kecil dari program (biasanya suatu fungsi atau metode) diuji secara terpisah untuk memastikan bahwa unit tersebut berfungsi sesuai dengan spesifikasi yang diharapkan. Tujuan utama dari unit testing adalah untuk memastikan bahwa setiap bagian kecil dari aplikasi berperilaku dengan benar, sesuai dengan desain dan fungsionalitas yang diinginkan.

beberapa motod yang ada di unit testing
1. Black Box Testing
2. White Box Testing
3. CGray Box Testing
4. Test-Driven Development (TDD)
5. Behavior-Driven Development (BDD)
6. Mutation Testing
7. Fuzz Testing
8. Boundary Testing

(5.) Kontainerisasi, Docker, dan Kubernetes adalah teknologi yang penting untuk pengembangan dan penyebaran aplikasi modern. Kontainerisasi memungkinkan pengembang untuk mengemas aplikasi dan semua dependensinya ke dalam unit yang portabel dan scalable. Docker adalah platform perangkat lunak yang memudahkan pengembang untuk membuat, menjalankan, dan mengelola kontainer. Kubernetes adalah sistem open-source yang digunakan untuk mengelola kontainer di lingkungan yang besar dan kompleks.

(6.) Continuous Integration (CI) adalah praktik menggabungkan kode dari berbagai pengembang ke dalam satu repositori secara berkala. CI bertujuan untuk mendeteksi dan memperbaiki konflik kode sejak dini, sehingga dapat menghemat waktu dan biaya.

Continuous Delivery (CD) adalah praktik mendeploy kode ke lingkungan produksi secara otomatis. CD bertujuan untuk memungkinkan pengembang untuk merilis kode baru ke produksi dengan lebih cepat dan lebih sering.

tools yang di gunakan untuk CI/CD di antaranaya

-Jenkins

-CircleCI

-Travis CI

-GitLab CI/CD

-Azure Pipelines

-AWS CodePipeline