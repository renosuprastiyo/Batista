# Batista

Batista adalah Batch data platform yang dibangun menggunakan teknologi Python, Spark, Airflow, Kudu, Presto dalam lingkungan cluster dan berjalan didalam Kubernetes(k8s).

Hardware Requirement yang dibutuhkan yaitu PC/Laptop/Mac dengan processor setara core i5 dan ram minimal 16GB agar sistem berjalan dengan baik. Dalam project ini saya menggunakan Macbook Pro Retina core i7 dengan ram 16GB.

Data platform ini nantinya akan mengambil data dari banyak sumber diantaranya MariaDB, Kong, GDocs dan MongoDB.

Untuk use case yang digunakan adalah Fashion Ecommerce data yang akan diambil dari MariaDB, MongoDB menyediakan data UMKM onboarding, Kong menyediakan REST API Third Party data digital marketing dan GDocs menyediakan data pencapaian tiap sales.

Untuk ER-Diagram pada MariaDB seperti dibawah ini menggunakan lucid chart

![ER-Diagram-Batista](https://github.com/renosuprastiyo/Batista/blob/master/ER-Diagram-Batista.png)

Untuk Datawarehouse pada data lake menggunakan star schema dengan scd type 1 dimana dimension table hanya menyimpan data terakhir dan tidak menyimpan data historical

![Datawarehouse-Batista](https://github.com/renosuprastiyo/Batista/blob/master/Datawarehouse-Batista.png)
