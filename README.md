# Jarkom-Modul-4-IT13-2024

## Anggota Kelompok IT 13

| Nama Lengkap          | NRP        |
| --------------------- | ---------- |
| Muhammad Dzaky Ahnaf  | 5027231039 |
| Muhammad Nafi Firdaus | 5027231045 |

## Topologi CPT 

![alt text](Topo_CPT.png)

## CIDR
### Definisi 
CIDR (Classless Inter-Domain Routing) adalah metode dalam jaringan komputer untuk mengalokasikan alamat IP dan mengatur rute IP dengan lebih efisien. Berbeda dengan sistem subnetting berbasis classful (di mana jaringan dibagi dalam kelas-kelas A, B, dan C dengan ukuran subnet yang sudah tetap), CIDR memperkenalkan fleksibilitas dengan menggunakan notasi prefix untuk menunjukkan panjang subnet mask. Hal ini memungkinkan pembagian alamat IP sesuai kebutuhan, tanpa harus bergantung pada batasan kelas.

## Pembagian Subnet 

![alt text](CIDR_A.png)

## Tabel Routing 
| Nama Subnet          | Rute       | Jumlah IP       | Netmask      | 
| -- | ---------- | ---------- | ---------- |
| A1  | Hololive -> HoloID | 2 | /30 | 
| A2 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A3  |Hololive -> HoloID -> AREA-15 -> Switch6 -> Moona -> Switch6 -> Risu -> Switch -> Lofi | 661 | /22 | 
| A4 | Hololive -> HoloID -> holoro | 2 | /30 | 
| A5  | Hololive -> HoloID -> holoro -> Switch7 -> Ollie -> Switch7 -> Anya -> Switch7 -> Reine | 34 | /26 | 
| A6 | Hololive -> HoloID -> holoh3ro | 2 | /30 | 
| A7  | Hololive -> HoloID -> holoh3ro -> Switch8 -> Zeta -> Switch8 -> Kaela -> Switch8 -> Kobo | 29 | /33 | 
| A8 | Hololive -> HoloJP | 2 | /30 | 
| A9  |Hololive -> HoloJP -> Switch1 -> DEV_IS -> Switch1 -> GEN:0 | 3 | /29 | 
| A10 |Hololive -> HoloJP -> Switch1 -> DEV_IS -> Re:Gloss -> Ririka_Raden -> Re:Gloss -> Ao -> Re:Gloss-> Hajime_Kanade | 14 | /28 | 
| A11  | Hololive -> HoloJP -> Switch1 -> GEN:0 -> Switch3 -> MiComet -> Switch3 -> Sora_Robo_AZK -> Switch3 -> GEN:1 | 2045 | /21 | 
| A12 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A13  | Hololive -> HoloID | 2 | /30 | 
| A14 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A15  | Hololive -> HoloID | 2 | /30 | 
| A16 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A17  | Hololive -> HoloID | 2 | /30 | 
| A18 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A19  | Hololive -> HoloID | 2 | /30 | 
| A20 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A21  | Hololive -> HoloID | 2 | /30 | 
| A22 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
