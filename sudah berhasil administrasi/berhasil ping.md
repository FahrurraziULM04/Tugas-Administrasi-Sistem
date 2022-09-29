# Langkah - Langkah Ping Pada Debian
----
## langkah pertama
----
sebelum memulai instalasi pastikan untuk menginstal debian terlebih dahulu pada komputer atau virtual-box kemudian atur sehingga adapter pertamamenjadi host-only dan pastikan langkah pengerjaan benar

<img src = "Screenshot 2022-09-27 124913.png" alt = "masukan jenis jaringan terminal">

*"Masukan Jaringan Terminal dan ubah menjadi Host-Only"*

----
## langkah kedua
----
kemudian login dan masukan username serta password untuk masuk ke debian lalu buka activity dan ketikan terminal

<img src = "Screenshot 2022-09-27 130717.png" alt = "Masuk Ke Super User Lalu Cek Ip  adress menggunakan ip-a">

*"Masuk Ke Super User Lalu Cek Ip  adress menggunakan ip-a"*

----
## langkah ketiga
----
kemudian atur ip pada adapter agar bisa mengakses alamat  ip dengan mengetikan nano /etc/network/interfaces agar jaringan nya bisa terhubung dan pengaturan allow-hotplug enp0s3 agar kabel ethernet bisa mengakses slot ethernet dan jenis interface dengan internet statis iface enp0s3 dan dengan alamat address dan atur agar alamat ip menjadi tipe c *192.168* kemudian ada netmask *255.255.255.* dan kosongkan di titik terakhir sehingga *255.255.255.0 dan atur gateway mirip dengan ip address dan bedakan ujung ip nya.

<img src = "Screenshot 2022-09-27 133618.png" alt = "Kemudian Atur Alamat Pada Adapter">

*"Kemudian Atur Alamat Pada Adapter"*

----
## langkah ke empat
----

kemudian atur ping hingga bisa di akses pada windows ke debian jika sudah berhasil maka akses bisa dilakukan contohnya pada 192.168.174.3 hingga bisa menghasilkan ping dibawah.

<img src = "Screenshot 2022-09-27 133020.png" alt = "Hasil bisa dilihat pada gambar berikut">

*"Hasil bisa dilihat pada gambar berikut"*





