Jarkom-Modul-3-ITB01-2022

# :zap: **Jarkom-Modul-4-ITB01-2022** :zap:

| Nama                               | NRP            |
|------------------------------------|----------------|
| 	:adult: Rafael Nixon              | 05311940000025 |
| 	:adult: Fairuz Azka Maulana       | 5027201017     |
| 	:adult: Muhammad Firdho Kustiawan | 5027201005     | 
<br/>

# :large_blue_circle: **Topologi Soal Shift 4.1** :large_blue_circle: 

<img src="/img/soal_shift_4.1.png">
<br>

# :large_blue_circle: **VLSM** :large_blue_circle: 
### :triangular_flag_on_post: **Topologi VLSM**
<img src="/img/VLSM.png">
<br>

### :triangular_flag_on_post: **Tabel VLSM**
Dalam menyelesaikan soal VLSM, Kami menggunakan Cisco Packet Tracer. Kami urutkan terlebih dahulu node yang membutuhkan paling banyak host. Kemudian kita menggunakan table tersebut untuk menentukan subnet mask pada PC Guideau. Karena PC Guideau membutuhkan 1000 host, sehingga kita memiliki subnet mask /22. Begitu pun seterusnya sehingga kita mendapatkan data sebagai berikut:
<img src="/img/Tabel-VLSM.png">
<br>

### :rocket: **Tree pada VLSM** 
Berdasarkan table yang telah kami buat dapat ditentukan Tree dari VLSM sebagai berikut:
<img src="/img/Tree-VLSM.png">

### :rocket: **Konfigursi Network** 
Pada router TheWitch akan di konfigurasikan ip sebagai berikut
<img src="/img/TheWitch.png">
<br>

Pada PC Ashaf akan di konfigurasikan ip sebagai berikut
<img src="/img/Ashaf.png">
<br>

Pada PC Guideau akan di konfigurasikan ip sebagai berikut
<img src="/img/Guideau.png">
<br>

Pada PC Johan akan di konfigurasikan ip sebagai berikut
<img src="/img/Johan.png">
<br>

Dan pada server1 akan di konfigurasikan ip sebagai berikut
<img src="/img/Server1.png">
<br>

### :rocket: **Konfigurasi dari TheMinister ke pc** 
Pada router The Minister, atur interface yang mengarah ke PC Guideau:
<img src="/img/TheMinister-Fa00-keGuideau.png">
<br>

### :rocket: **Konfigurasi dari TheMinister ke Router** 
Pada router The Minister, atur interface yang mengarah ke router Dauntless:
<img src="/img/TheMinister-Fa01-keRouterDauntless.png">
<br>

Pada router The Minister, atur interface yang mengarah ke router TheOrder:
<img src="/img/TheMinister-Fa01-keRouterTheOrder.png">
<br>

### :rocket: **Routing TheMinister ke subnet** 
Pada router The Minister, atur routing mengarah ke SubnetA2:
<img src="/img/TheMinister-Routing-keSubnetA2.png">
<br>

Pada router The Minister, atur routing mengarah ke SubnetA7:
<img src="/img/TheMinister-Routing-keSubnetA7.png">
<br>

### :rocket: **Contoh Demo dari PC Phanora ke PC Ashaf** 
Berikut merupakan contoh demo mengirim paket dari PC phanora ke PC Ashaf:
<img src="/img/contohPhanoraKeAshaf.jpg">
<img src="/img/contohPhanoraKeAshaf2.jpg">
<br>




# :large_blue_circle: **CIDR** :large_blue_circle:
Blabla

### :triangular_flag_on_post: **Topologi CIDR**
<img src=".....">
<br>

### :triangular_flag_on_post: **Tabel CIDR**
Untuk pembagian IP pada tabel CIDR di bawah ini kami membagi IP beserta prefix nya sesuai dengan topologi pembagian di atas 
<img src="/img/Tabel-CIDR.png">
Dan berikut juga merupakan tahapan kami mengelompokkan subnet-subnet menjadi satu dalam bentuk tabel
<img src="/img/steppembagian.png">
<br>


### :rocket: **Contoh Konfigurasi IP dan Gateway PC** 
Kami masih terdapat error ketika menyoba konfigurasi 1 subnet
<br>

### :rocket: **Contoh Konfigurasi Gateway dan Routing Router** 
Kami masih terdapat error ketika menyoba konfigurasi 1 subnet
<br>


# :large_blue_circle: **KENDALA** :large_blue_circle:
Kami masih belom mengetahui bagaimana cara konfigurasi di CIDR
