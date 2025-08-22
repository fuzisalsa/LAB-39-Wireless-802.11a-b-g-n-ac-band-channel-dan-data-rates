# LAB-39-Wireless-802.11a-b-g-n-ac-band-channel-data-rates-
tanggal 22 agustus 2025

# wireless 802.11
 Institute of Electrical and Electronics Engineers (IEEE) mengembangkan standar WLAN pertama pada tahun 1997, yang dikenal sebagai 802.11. Standar IEEE 802.11 (a, b, g, n, dan ac) adalah serangkaian spesifikasi untuk teknologi jaringan Wi-Fi yang menentukan cara perangkat komunikasi nirkabel mengirim dan menerima data. Setiap standar ini mewakili generasi dan kemampuan yang berbeda, dengan peningkatan berurutan pada kecepatan data, frekuensi operasional (2,4 GHz atau 5 GHz), dan teknologi canggih seperti MIMO (Multiple-Input, Multiple-Output) dan beamforming.

**Ringkasan Standar Wi-Fi Berdasarkan Generasi:**  

**802.11a/b/g:**   
Standar-standar awal yang memiliki kecepatan dan teknologi yang terbatas.   
**802.11b:** Beroperasi pada pita 2,4 GHz dengan kecepatan maksimal 11 Mbps.    
**802.11g:** Menggunakan pita 2,4 GHz dan memiliki kecepatan yang lebih tinggi, hingga 54 Mbps.    
**802.11a:** Beroperasi pada pita 5 GHz, juga dengan kecepatan hingga 54 Mbps.     
**802.11n (Wi-Fi 4):**   
Standar yang memperkenalkan teknologi MIMO, yang memungkinkan transmisi data ke beberapa antena, sehingga meningkatkan throughput. dan Mampu beroperasi pada pita 2,4 GHz dan 5 GHz. serta Mendukung hingga 4 aliran spasial untuk transmisi data yang lebih baik.    
**802.11ac (Wi-Fi 5):**   
Standar yang jauh lebih canggih dibandingkan pendahulunya. Bekerja eksklusif pada pita frekuensi 5 GHz untuk mengurangi interferensi. Menggunakan beamforming, yang memfokuskan sinyal ke perangkat tertentu daripada menyebarkannya ke segala arah. Memperkenalkan MU-MIMO (Multi-User, Multiple-Input, Multiple-Output) yang memungkinkan router untuk mengirimkan data ke beberapa klien secara bersamaan, sehingga meningkatkan efisiensi jaringan. dan Mendukung hingga 8 aliran spasial pada beberapa versi gelombang kedua (Wave 2). 

# band   
Band adalah rentang frekuensi kerja yang digunakan perangkat wireless untuk melakukan komunikasi data. Pada mikrotik, band yang tersedia menyesuaikan dengan standar IEEE 802.11, yaitu sekumpulan protokol jaringan wireless yang dikembangkan oleh Institute of Electrical and Electronic Engineers (IEEE). Protokol 802.11 ini mengatur cara perangkat mengakses media wireless, cara trsnamisi data, kecepatan maksimal, teknik modulasi, hingga kompabilitas antar perangkat.

**Ada beberapa band di router mikrotik:**   
**2Ghz-b**, bekerja di frekuensi 2,4Ghz. Menggunakan protokol 802.11b dengan data rate maksimum 11 Mbit/s.    
**2Ghz-b/g**, juga bekerja di frekuensi 2,4Ghz. Menggunakan protokol 802.11b dan 802.11g. protokol 802.11g hampir sama seperti 802.11b akan tetapi melakukan transmisi dengan basis OFDM seperti 802.11a sehingga protokol 802.11g bisa mencapai 54 Mbit/s.   
**2Ghz-b/g/n**, bekerja di frekuensi 2,4Ghz. Menggunakan protokol 802.11b, 802.11g dan 802.11n. Pengembangan dari standart protokol 802.11, ditambah dengan kemampuan multiple-input multiple-output (MIMO). Dengan tambahan fitur MIMO ini, secara teori maksimal data rate yang bisa dicapai adalah 300 Mbit/s.   
**2Ghz-only G**, bekerja di frekuensi 2,4Ghz, hanya menggunakan protokol  802.11g.  
**2Ghz-only N**, bekerja di frekuensi 2,4Ghz, hanya menggunakan protokol  802.11n.   
**5Ghz-a**, bekerja di frekuensi 5 Ghz. Menggunakan protokol 802.11a, maximum data rate yang bisa dicapai adalah 54 Mbit/s.   
**5Ghz-a/n**, bekerja di frekuensi 5 Ghz. Menggunakan protokol 802.11a dan 802.11n.   
**5Ghz-only N**, bekerja di frekuensi 5 Ghz dan hanya menggunakan protokol  802.11n.   

# konfigurasi band dan frekuensi di mikrotik
1. wireless > > wifi interface > klik (wlan1) > pilih tab wireless, pilih band dan frequency

![m]()

![m]()

# channel
Channel adalah jalur komunikasi berupa segmen frekuensi radio tertentu yang digunakan oleh perangkat nirkabel (seperti router, laptop, atau smartphone) untuk mengirim dan menerima data dalam pita frekuensi tertentu seperti 2.4 GHz, atau 5 GHz. Channel bekerja pada lapisan fisik (Physical Layer) dalam model OSI, karena berkaitan langsung dengan gelombang elektromagnetik yang digunakan untuk membawa data antar perangkat. Channel juga merupakan bagian dari sistem multiple access dalam jaringan wireless, yang memungkinkan banyak perangkat menggunakan medium udara secara efisien tanpa saling mengganggu.

**2.4 GHz**
Band 2.4 GHz adalah salah satu pita frekuensi yang digunakan dalam jaringan Wi-Fi (wireless LAN), tepatnya dalam rentang 2.400 hingga 2.4835 GHz. Terdapat 14 channel di pita 2.4 GHz, masing-masing berjarak 5 MHz, tetapi lebar setiap channel adalah 20 MHz, sehingga channel-channel ini saling tumpang tindih (overlap). Supaya tidak overlap, gunakan channel dengan jarak jauh. 

**2.5 GHz**
# sumber
https://citraweb.com/artikel_lihat.php?id=70
