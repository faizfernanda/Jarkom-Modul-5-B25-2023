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
- #### GroberForest
```
auto eth0
iface eth0 inet static
	address 10.21.8.3
	netmask 255.255.252.0
  gateway 10.21.8.1

```
- #### GroberForest
```
auto eth0
iface eth0 inet static
	address 10.21.8.3
	netmask 255.255.252.0
  gateway 10.21.8.1
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
iface eth0 inet static
	address 10.21.12.2
	netmask 255.255.254.0
  gateway 10.21.12.1
```
- #### SchwerMountain
```
auto eth0
iface eth0 inet static
	address 10.21.14.3
	netmask 255.255.255.128
  gateway 10.21.14.1
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