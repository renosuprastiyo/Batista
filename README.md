# Batista

Batista adalah Batch data platform yang dibangun menggunakan teknologi Python, Spark, Airflow, Presto dalam lingkungan cluster dan berjalan diatas Virtual Machine.

Platform ini berjalan di lokal sehingga hardware requirement yang dibutuhkan yaitu PC/Laptop/Mac dengan processor setara core i5 dan ram minimal 16GB agar sistem berjalan dengan baik. Dalam project ini saya menggunakan Macbook Pro Retina core i7 dengan ram 16GB.

Data platform ini nantinya akan mengambil beberapa data diantaranya data terstruktur dari relational database yaitu MySQL dan untuk data tidak terstrukturnya berupa file excel dan ada juga data NoSQL dari MongoDB.

Untuk use case yang digunakan adalah Fashion Ecommerce data yang akan diambil dari MySQL dan data invoice procurement dari file excel untuk MongoDB menyimpan data inquiry yaitu data pencarian barang oleh user di website/apps.

Berikut ini arsitektur sistem yang akan dibangun

![Arsitektur-Batista](https://github.com/renosuprastiyo/Batista/blob/master/architecture.png)

Pengembangannya sendiri terdiri dari beberapa tahapan antara lain :

<ol>
  <li>[Setup Infrastruktur](https://github.com/renosuprastiyo/Batista/blob/master/setup_infrastructure.md)</li>
  <li>[Data Modelling](https://github.com/renosuprastiyo/Batista/blob/master/data_modelling.md)</li>
  <li>[Coding](https://github.com/renosuprastiyo/Batista/blob/master/coding.md)</li>
  <li>[Go Live](https://github.com/renosuprastiyo/Batista/blob/master/go_live.md)</li>
</ol>

Have Fun!!
