# client-server
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
install terlebih dahulu network manager dengan net tools, perintah nya yaitu *apt install network-manager* dan *apt install net-tools* 

<img src="install_network_manager_dan_net_tools.png">

---
**kedua**
---
kemudian atur ip address dengan mengetikan *nano /etc/network/interfaces* kemudian atur dengan konfigurasi seperti pada gambar berikut untuk ip address yang utama enp0s3 dan untuk ip yang akan di ping menggunakan enp0s8.

<img src="atur_ip_primary_dan_ip_sekunder_untuk_melakukan_ping.png">

---
**ketiga**
---
kemudian restart jaringan dengan menggunakan *systemctl restart networking* dan *systemctl restart networking.service* untuk memulai ulang konfigurasi agar bisa mengubah ip yang telah di edit tadi.

<img src="restart_jaringan_dengan_mengetikan_perintah_sebagai_berikut.png">

---
**keempat**
---
lalu lihat alamat ip yang sudah di restart dengan mengetikan perintah *sudo ifconfig* seperti pada gambar dibawah.

<img src="lihat_hasil_dengan_mengetikan_sudo_ifconfig.png">

---
**kelima**
---
lakukan ping ip pada linux dengan mengetikan perintah *ping 192.168.42.1* untuk memanggil ip jika berhasil maka akan muncul tampilan sebagai berikut.

<img src="coba_lakukan_ping_pada_ip_di_linux_jika_berhasil_akan_muncul_hasil_sebagai_berikut.png">

---
**keenam**
---
lalu coba lakukan ping pada windows jika berhasil maka akan muncul tampilan sebagai berikut.

<img src="coba_ping_ip_linux_dengan_cmd_windows.png">
