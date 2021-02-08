# Batista

Batista adalah Batch data platform yang dibangun menggunakan teknologi Python, Spark, Airflow, Presto dalam lingkungan cluster dan berjalan didalam Kubernetes(k8s).

Platform ini berjalan di lokal sehingga hardware requirement yang dibutuhkan yaitu PC/Laptop/Mac dengan processor setara core i5 dan ram minimal 16GB agar sistem berjalan dengan baik. Dalam project ini saya menggunakan Macbook Pro Retina core i7 dengan ram 16GB.

Data platform ini nantinya akan mengambil beberapa data diantaranya data terstruktur dari relational database yaitu MySQL dan untuk data tidak terstrukturnya berupa file excel dan ada juga data NoSQL dari MongoDB.

Untuk use case yang digunakan adalah Fashion Ecommerce data yang akan diambil dari MySQL dan data invoice procurement dari file excel untuk MongoDB menyimpan data inquiry yaitu data pencarian barang oleh user di website/apps.

Untuk ER-Diagram pada MySQL seperti dibawah ini menggunakan lucid chart

![ER-Diagram-Batista](https://github.com/renosuprastiyo/Batista/blob/master/ER-Diagram-Batista.png)

Untuk Datawarehouse pada data lake menggunakan star schema dengan scd type 1 dimana dimension table hanya menyimpan data terakhir dan tidak menyimpan data historical

![Datawarehouse-Batista](https://github.com/renosuprastiyo/Batista/blob/master/Datawarehouse-Batista.png)
