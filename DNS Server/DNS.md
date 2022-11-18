# DNS
---
## langkah-langkah nya sebagai berikut
---
## Nama Kelompok
1. Fahrurrazi 
2. Rizky Ahmad
3. Fahrul Ikhsan Hidayatullah
---
**pertama**
---
install dns terlebih dahulu dengan mengetikan perintah *apt install bind9 dnsutils* setelah itu akan muncul tampilan sebagai berikut.

<img src="Gambar/install_dns_terlebih_dahulu.png">

---
**kedua**
---
setelah melakukan instalasi masuk ke dalam folder bind9 dengan mengetikan perintah *cd /etc/bind* dan lihat list file dengan mengetikan perintah *ls* setelah itu baru akan muncul hasil seperti digambar.

<img src="Gambar/masuk_ke_folder_bind_kemudian_lihat_list_file.png">

---
**ketiga**
---
copy folder dari db local ke db azi dan dari db 127 ke db 55 dengan cara mengetikan perintah *cp db local db azi* dan *cp db 127 db 55* setelah selesai maka akan muncul hasil seperti pada gambar berikut.

<img src="Gambar/copy_db_local_ke_db_azi.png">

<img src="Gambar/copy_db_127_ke_db_55.png">

---
**keempat**
---
langkah selanjut nya tinggal melakukan konfigurasi seperti gambar dibawah dengan cara mengetikan perintah *nano db azi* dan *nano db 55* hingga mendapat hasil sebagai berikut.

<img src="Gambar/atur_isi_database_azi_dengan_konfigurasi_sebagai_berikut.png">

<img src="Gambar/atur_isi_database_55_dengan_konfigurasi_sebagai_berikut.png">

---
**kelima**
---
langkah kelima kita tinggal mengaktifkan bind9 nya dengan cara mengetikan perintah *systemctl start bind9*.

<img src="Gambar/coba_cek_status_bind9.png">

---
**keenam**
---
langkah ke enam jika sudah selesai maka kita bisa mencari alamat dns dengan cara mengetikan perintah *nslookup azi042001.net*.

<img src="Gambar/cari_alamat_dengan_mengetikan_nslookup_nama_domain.png">



