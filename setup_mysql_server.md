# Setup MySQL Server

Berikutnya kita akan menyiapkan server mysql dengan mengclone vm Ubuntu18 yang telah kita buat sebelumnya. Pastikan vm Ubuntu18 dalam keadaan mati ketika akan diclone.

![Clone-VM](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_1_clone.png)

Pada konfigurasi clone pastikan dicheck Reinitialize MAC Address dan pilih tipe full clone

![Config-Clone](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_2_config_clone.png)

Kemudian nyalakan vm MySQL tersebut dan login menggunakan user pada vm Ubuntu

![Login-VM](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_3_login.png)

Setelah login kita akan membuat non-root user yaitu mysql-ersu dan menambahkannya sebagai user sudo

![Add-Newuser](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_4_adduser.png)

Tambahkan user baru tersebut di baris terakhir file sudo sehingga tidak perlu mengetikkan password ketika menggunakan perintah sudo

![Visudo](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_5_visudo.png)
