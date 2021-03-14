# Setup MySQL Server

Berikutnya kita akan menyiapkan server mysql dengan mengclone vm Ubuntu18 yang telah kita buat sebelumnya. Pastikan vm Ubuntu18 dalam keadaan mati ketika akan diclone.

![Clone-VM](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_1_clone.png)

Pada konfigurasi clone pastikan dicheck Reinitialize MAC Address dan pilih tipe full clone

![Config-Clone](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_2_config_clone.png)

Kemudian nyalakan vm MySQL tersebut dan login menggunakan user pada vm Ubuntu

![Login-VM](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_3_login.png)

Setelah login kita akan membuat non-root user yaitu mysql-ersu dan menambahkannya sebagai user sudo

![Add-Newuser](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_4_adduser.png)

Tambahkan user baru tersebut di baris terakhir file sudo sehingga tidak perlu mengetikkan password ketika menggunakan perintah sudo, tekan CTRL + o, tekan enter, tekan CTRL + x untuk menyimpan perubahan dan keluar dari editor

![Visudo](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_5_visudo.png)

Ubah hostname dengan nama yang baru kemudian login ulang

![Set-Hostname](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_6_sethostname.png)

![Relogin](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_7_relogin.png)

Ganti ip address dengan yang baru dalam hal ini alamat ip addresnya 192.168.63.10

![Set-IP](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_8_setipaddress.png)

![Set-IP-2](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_8_setipaddress_2.png)

Ganti nat dengan alamat baru 10.0.2.10

![Set-NAT](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_9_setnat.png)

![Set-NAT-2](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_9_setnat_2.png)

Kemudian terapkan perubahan network ini dengan command berikut

![Apply-Network-Change](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_10_apply_network_change.png)

Berikutnya kita akan menginstal paket mysql di sistem operasi ubuntu ini

![Install-MySQL-Package](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_11_install_mysql_package.png)

Setelah selesai lakukan instalasi mysql

![Install-MySQL-Server](https://github.com/renosuprastiyo/Batista/blob/master/resources/2_12_install_mysql_server.png)
