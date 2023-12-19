# Jarkom-Modul-5-B25-2023

## Nama Anggota :
| No | Nama| NRP|
| ------- | ------- | ------- |
| 1 | Muhamad Faiz Fernanda | 5025211186|
| 2| Tigo S Yoga | 5025211125 |

### Topology 
![gambar topology](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/f4e5ac1d-4a7b-44fd-8e80-3f4cc5b4d007)
### Subnetting
![plotting subnetting](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/8a8b6955-8ac1-4bdf-aa61-110203b6aac5)
#### Tree
![Retrospectives (3)](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/fa9fb6f0-16a8-4f4c-89aa-5575e2ffed8b)
#### VLSM Table
![vlsm](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/3bedeada-6fe3-42ba-8c5d-12bf71351766)
#### Ip Distribution
![IP distribution](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/40645f8d-4a12-4dce-8108-a6c76bc6ce7b)
### Node Configuration 
#### Network Configuration and Node Rputing 
- #### Aura
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.21.14.149
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.21.14.145
	netmask 255.255.255.252

Menerima 
mengirim 
A9
route add -net 10.21.0.0 netmask 255.255.248.0 gw 10.21.14.150
A10
route add -net 10.21.8.0 netmask 255.255.252.0 gw 10.21.14.150
A5 
route add -net 10.21.14.136 netmask 255.255.255.252 gw 10.21.14.146
A6
route add -net 10.21.14.140 netmask 255.255.255.252 gw 10.21.14.146
A4
route add -net 10.21.12.0 netmask 255.255.255.252 gw 10.21.14.146
A3
route add -net 10.21.14.0 netmask 255.255.255.252 gw 10.21.14.146
A2
route add -net 10.21.14.132 netmask 255.255.255.252 gw 10.21.14.146
A1
route add -net 10.21.14.128 netmask 255.255.255.252 gw 10.21.14.146

```
- #### Heiter 
```
auto eth0
iface eth0 inet static
	address 10.21.14.150
	netmask 255.255.255.252
  gateway 10.21.14.149

auto eth1
iface eth1 inet static
	address 10.21.0.1
	netmask 255.255.248.0

auto eth2
iface eth2 inet static
	address 10.21.8.1
	netmask 255.255.252.0

menerima 
aura(a8)
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.14.149

```

- #### TurkRegion 
```
auto eth0
iface eth0 inet static
	address 10.21.0.2
	netmask 255.255.248.0
  gateway 10.21.0.1



```

- #### Sein
```
auto eth0
iface eth0 inet static
	address 10.21.8.2
	netmask 255.255.252.0
  gateway 10.21.8.1
```
- #### TurkRegion
```
auto eth0
iface eth0 inet dhcp

```
- #### GroberForest
```
auto eth0
iface eth0 inet dhcp
```
- #### Frieren 
```
auto eth0
iface eth0 inet static
	address 10.21.14.146
	netmask 255.255.255.252
  gateway 10.21.14.145

auto eth1
iface eth1 inet static
	address 10.21.14.141
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.21.14.137
	netmask 255.255.255.252

```
- #### Frieren 
```
auto eth0
iface eth0 inet static
	address 10.21.14.146
	netmask 255.255.255.252
  gateway 10.21.14.145

menerima 
aura (A7)
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.14.145
mengirim 
A4
route add -net 10.21.12.0 netmask 255.255.254.0 gw 10.21.14.138
A3
route add -net 10.21.14.0 netmask 255.255.255.128 gw 10.21.14.138
A2
route add -net 10.21.14.132 netmask 255.255.255.252 gw 10.21.14.138
A1
route add -net 10.21.14.128 netmask 255.255.255.252 gw 10.21.14.138
```
- #### Stark
```
auto eth0
iface eth0 inet static
	address 10.21.14.142
	netmask 255.255.255.252
  gateway 10.21.14.141
```
- #### Himmel
```
auto eth0
iface eth0 inet static
	address 10.21.14.138
	netmask 255.255.255.252
  gateway 10.21.14.137

auto eth1
iface eth1 inet static
	address 10.21.12.1
	netmask 255.255.254.0

auto eth2
iface eth2 inet static
	address 10.21.14.1
	netmask 255.255.255.128

menerima 
Frieren (A5)
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.14.137

mengirim 
A1
route add -net 10.21.14.128 netmask 255.255.255.252 gw 10.21.14.2
A2
route add -net 10.21.14.132 netmask 255.255.255.252 gw 10.21.14.2
```
- #### LaubHils
```
auto eth0
iface eth0 inet dhcp
```
- #### SchwerMountain
```
auto eth0
iface eth0 inet dhcp
```
- #### Fern
```
auto eth0
iface eth0 inet static
	address 10.21.14.2
	netmask 255.255.255.128
  gateway 10.21.14.1

auto eth1
iface eth1 inet static
	address 10.21.14.133
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.21.14.129
	netmask 255.255.255.252
menerima 
himmel A3
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.14.1
mengirim

```
- #### Ritcher
```
auto eth0
iface eth0 inet static
	address 10.21.14.134
	netmask 255.255.255.252
    gateway 10.21.14.133
```
- #### Revolte
```
auto eth0
iface eth0 inet static
	address 10.21.14.130
	netmask 255.255.255.252
  gateway 10.21.14.129
```

### DHCP set-up
- #### Revolte - dhcpd.conf
```
subnet 10.21.14.128 netmask 255.255.255.252 {
   option routers 10.21.14.129;
}
#A2
subnet 10.21.14.132 netmask 255.255.255.252 {
  
}
#A5
subnet 10.21.14.136 netmask 255.255.255.252 {
   option routers 10.21.14.137;
}
#A6
subnet 10.21.14.140 netmask 255.255.255.252 {
  
}
#A7
subnet 10.21.14.144 netmask 255.255.255.252 {
   option routers 10.21.14.145;
}
#A8
subnet 10.21.14.148 netmask 255.255.255.252 {
    option routers 10.21.14.150;
}


#laubhils
subnet 10.21.12.0 netmask 255.255.254.0 {
    range 10.21.12.2 10.21.13.1;
    option routers 10.21.12.1;
    option broadcast-address 10.21.13.255;
    option domain-name-servers 10.21.14.134;
    default-lease-time 720;
    max-lease-time 5760;
}
#schwermountain
subnet 10.21.14.0 netmask 255.255.255.128 {
    range 10.21.14.3 10.21.14.66;
    option routers 10.21.14.1;
    option broadcast-address  10.21.14.127;
    option domain-name-servers 10.21.14.134;
    default-lease-time 720;
    max-lease-time 5760;
}
#turkregion
subnet 10.21.0.0 netmask 255.255.248.0 {
    range 10.21.0.2 10.21.4.4;
    option routers 10.21.0.1;
    option broadcast-address  10.21.7.255;
    option domain-name-servers 10.21.14.134;
    default-lease-time 720;
    max-lease-time 5760;
}
#Grobforest
subnet 10.21.8.0 netmask 255.255.252.0 {
    range 10.21.8.3 10.21.10.5;
    option routers 10.21.8.1;
    option broadcast-address  10.21.11.255;
    option domain-name-servers 10.21.14.134;
    default-lease-time 720;
    max-lease-time 5760;
}

```
- #### DHCP - isc-dhcp-relay
```
SERVERS="10.21.14.130"  
INTERFACES="eth0 eth1 eth2"
OPTIONS=
```
- #### DNS SERVER
  Setiing pada  /etc/bind/named.conf.options
```
options {
        directory "/var/cache/bind";

        forwarders {
                192.168.122.1;
        };

        auth-nxdomain no;
        listen-on-v6 { any; };
};
```
### Soal-No-1
Agar topologi yang kalian buat dapat mengakses keluar, kalian diminta untuk mengkonfigurasi Aura menggunakan iptables, tetapi tidak ingin menggunakan MASQUERADE.

#### Penyelesaian 
Didalam Node Aura kita menambahkan script dibawah ini 
```
ETH0_IP=$(ip -4 addr show eth0 | grep -oP '(?<=inet\s)\d+(\.\d+){3}')

iptables -t nat -A POSTROUTING -o eth0 -j SNAT --to-source $ETH0_IP
```
Lalu pada setiap node di tambahkan ``` nameserver 192.168.122.1 ``` pada ``` /etc/resolv.conf ```

#### Hasil Testing
- **AURA**

![No 1 Aura](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/1d0449d5-0cfd-4822-8dd9-dd19da1bb48b)
- **Client**

![no 1 client](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/beb68d5c-6e5b-4011-814d-176ec10777e6)
### Soal-No-2
Kalian diminta untuk melakukan drop semua TCP dan UDP kecuali port 8080 pada TCP.

#### Penyelesaian 
Untuk menyelesaikan problem di atas maka di perlukan sytax seperti di bawah ini :
```
# Drop semua koneksi UDP
iptables -A INPUT -p udp -j DROP

# Drop semua koneksi TCP kecuali port 8080
iptables -A INPUT -p tcp ! --dport 8080 -j DROP
iptables -A INPUT -p tcp -j DROP
```
#### Hasil Testing
- Dari Sender

![No 2 sender](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/6144a21b-6eb7-4eac-9b83-a0d86e324410)
- Dari Receiver

![no 2 receiver](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/6564d017-0702-480e-b022-1d73bc297ce9)

### Soal-No-3
Kepala Suku North Area meminta kalian untuk membatasi DHCP dan DNS Server hanya dapat dilakukan ping oleh maksimal 3 device secara bersamaan, selebihnya akan di drop

#### Penyelesaian 
Untuk menyelesaikan problem di atas maka di perlukan sytax seperti di bawah ini :
```
iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
iptables -A INPUT -p icmp -m connlimit --connlimit-above 3 --connlimit-mask 0 -j DROP

```
#### Hasil Testing
Bisa di lihat pada client ```TurkRegion``` ping tidak dapat di lakukan karena ada nya pembatasan maximal 3 client

![no 3 testing](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/6e238bea-60ad-489a-83c9-8c6d77342829)

### Soal-No-4
Lakukan pembatasan sehingga koneksi SSH pada Web Server hanya dapat dilakukan oleh masyarakat yang berada pada GrobeForest.

#### Penyelesaian 
Untuk menyelesaikan problem di atas maka di perlukan sytax seperti di bawah ini :
```
#pada Sein
# Allow SSH from a specific IP range
iptables -A INPUT -p tcp --dport 22 -m iprange --src-range 10.21.8.3-10.21.10.5 -j ACCEPT

# Drop SSH from all other sources
iptables -A INPUT -p tcp --dport 22 -j DROP

```

#### Hasil Testing
Terlihat dari Hasil Testing bahwa yang muncul hanya yang berada di GrobForest sedangkan client lainnya tidak menerima pesan

![No 4 testing](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/27714bc3-8844-4ca8-b1da-1a8c1c23e12a)

### Soal-No-5
Selain itu, akses menuju WebServer hanya diperbolehkan saat jam kerja yaitu Senin-Jumat pada pukul 08.00-16.00.

#### Penyelesaian 
Untuk menyelesaikan problem di atas maka di perlukan sytax seperti di bawah ini :
```
# Allow HTTP access only during working hours (Monday-Friday, 08:00-16:00)
iptables -A INPUT -p tcp --dport 80 -m time --timestart 08:00 --timestop 16:00 --weekdays Mon,Tue,Wed,Thu,Fri -j ACCEPT

# Drop other HTTP traffic
iptables -A INPUT -p tcp --dport 80 -j DROP

```
#### Hasil Testing
Terlihat hasil testing bahwa saat waktu server bukan berada di antara 08:00-16:00 walau di hari yang kita tentukan, maka client tidak menerima pesan yang di kirim web server (Sein)

![No5 hasil](https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/101172294/13736ce7-5dfb-4b25-b6b1-79776844de53)

### Soal-No-6
Lalu, karena ternyata terdapat beberapa waktu di mana network administrator dari WebServer tidak bisa stand by, sehingga perlu ditambahkan rule bahwa akses pada hari Senin - Kamis pada jam 12.00 - 13.00 dilarang (istirahat maksi cuy) dan akses di hari Jumat pada jam 11.00 - 13.00 juga dilarang (maklum, Jumatan rek).

#### Penyelesaian 
Tambahkan script pada `Sein` dan `Stark` sebagai Web Server :
```
# Drop akses pada hari Senin-Kamis jam 12:00 - 13:00
iptables -A INPUT -p tcp --dport 80 -m time --timestart 12:00 --timestop 13:00 --weekdays Mon,Tue,Wed,Thu -j DROP

# Drop akses pada hari Jum'at pada 11:00 - 13:00
iptables -A INPUT -p tcp --dport 80 -m time --timestart 11:00 --timestop 13:00 --weekdays Fri -j DROP
```

#### Hasil Testing

https://github.com/faizfernanda/Jarkom-Modul-5-B25-2023/assets/88433109/1eb5c451-a4f5-4d13-a309-0fd416708a39

### Soal-No-7
Karena terdapat 2 Web Server, kalian diminta agar setiap client yang mengakses Sein dengan Port 80 akan didistribusikan secara bergantian pada Sein dan Stark secara berurutan dan request dari client yang mengakses Stark dengan port 443 akan didistribusikan secara bergantian pada Sein dan Stark secara berurutan.

#### Penyelesaian 
Tambahkan script pada `Sein` dan `Stark` sebagai Web Server :
- Sein
  ```
  iptables -A PREROUTING -t nat -p tcp -d 10.21.8.2 --dport 80 -m statistic --mode nth --every 2 --packet 0 -j DNAT --to-destination 10.21.8.2:80

  iptables -A PREROUTING -t nat -p tcp -d 10.21.8.2 --dport 80 -j DNAT --to-destination 10.21.14.138:80
  ```

- Stark
  ```
  iptables -A PREROUTING -t nat -p tcp -d 10.21.8.2 --dport 443 -m statistic --mode nth --every 2 --packet 0 -j DNAT --to-destination 10.21.8.2:443

  iptables -A PREROUTING -t nat tcp -d 10.21.8.2 --dport 443 -j DNAT --to-destination 10.21.14.138:443
  ```

#### Hasil Testing


### Soal-No-8
Karena berbeda koalisi politik, maka subnet dengan masyarakat yang berada pada Revolte dilarang keras mengakses WebServer hingga masa pencoblosan pemilu kepala suku 2024 berakhir. Masa pemilu (hingga pemungutan dan penghitungan suara selesai) kepala suku bersamaan dengan masa pemilu Presiden dan Wakil Presiden Indonesia 2024.

#### Penyelesaian 
Tambahkan script pada `Sein` dan `Stark` sebagai Web Server :
- Sein
  ```
  iptables -A INPUT -s 10.21.14.130 -m time --datestart 2023-10-19T00:00 --datestop 2024-02-15T00:00 -j DROP
  ```
  
- Stark
  ```
  iptables -A INPUT -s 10.21.14.130 -m time --datestart 2023-10-19T00:00 --datestop 2024-02-15T00:00 -j DROP
  ```

#### Hasil Testing


### Soal-No-9
Sadar akan adanya potensial saling serang antar kubu politik, maka WebServer harus dapat secara otomatis memblokir  alamat IP yang melakukan scanning port dalam jumlah banyak (maksimal 20 scan port) di dalam selang waktu 10 menit. 
(clue: test dengan nmap)

#### Penyelesaian 
Tambahkan script pada `Sein` dan `Stark` sebagai Web Server :
- Sein dan Stark
  ```
  iptables -N portscan

  iptables -A INPUT -m recent --name portscan --update --seconds 600 --hitcount 20 -j DROP
  iptables -A FORWARD -m recent --name portscan --update --seconds 600 --hitcount 20 -j DROP

  iptables -A INPUT -m recent --name portscan --set -j ACCEPT
  iptables -A FORWARD -m recent --name portscan --set -j ACCEPT
  ```

#### Hasil Testing


### Soal-No-10
Karena kepala suku ingin tau paket apa saja yang di-drop, maka di setiap node server dan router ditambahkan logging paket yang di-drop dengan standard syslog level. 

#### Penyelesaian 
Tambahkan script pada setiap node server dan router :
 ```
 iptables -A INPUT -j LOG --log-level debug --log-prefix "Dropped Packet" -m limit --limit 1/second --limit-burst 10
 ```

#### Hasil Testing
